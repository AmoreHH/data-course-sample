
## 專案目的
- User-based collaborative filtering
- Item-based collaborative filtering
- 套件 surprise 實作 collaborative filtering

分別以上述三種方式，打造推薦系統。

## 工具
Python, Colab\
Package : pandas, numpy, plotly, surprise

## 資料基本描述
- 評論資料：2000-01-10 - 2018-10-02
    - 訓練資料：2000-01-10 - 2018-09-01
    - 測試資料：2018-09-01 - 2018-09-30


## 產生方式 
1. 針對原始資料新增篩選條件：\
    a. 清除重複資料\
    b. 僅保留2012年之後的評論\
    c. 保留評論數至少5筆的商品\
    d. 保留至少3筆評論的使用者 (僅用於user-based) 
    

## 推薦分數結果 (範例)
1. User-based : 0.0
2. Item-based : 0.0
3. 套件surprise: 0.001694915254237288

## 推薦分數結果 (使用篩選後的資料集)
1. User-based : 0.0
2. Item-based : 0.0
3. 套件surprise: \
        - User-based : 0.0\
        - Item-based : 0.003389830508474576
        
 
 
## 參考文章
1. [Building and Testing Recommender Systems With Surprise, Step-By-Step](https://towardsdatascience.com/building-and-testing-recommender-systems-with-surprise-step-by-step-d4ba702ef80b)
2. [User-Based and Item-Based Collaborative Filtering — Part 5](https://medium.com/fnplus/user-based-and-item-based-collaborative-filtering-b73d9b2badba)


