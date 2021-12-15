# 微積分(一)A階段



::: spoiler 詞彙補給站
- tangent line 切線
- slope 斜率
- polynomial 多項式
- intervals 區間
- derivative  導函數
- differentiable 微分
- normal line 法線
- absolute maximum 最大值
- absolute minimum 最小值
- local maximum value 局部最大值
- local minimum value 局部最小值
- critical numbers 臨界數
- Inflection point 反曲點
::: 



## 1.函數有連續
- 有極限
- 左極限=右極限
- 函數在a的函數值=極限值

## 2.切線(Tangent Lines)
![Imgur](https://i.imgur.com/ztx9hOW.png)




## 3.斜率
![Imgur](https://i.imgur.com/KSoqk8Y.png)





## 4.微分所有公式
![Imgur](https://i.imgur.com/kGu3AiV.png)
![Imgur](https://i.imgur.com/kQRoRjp.png)


## 5.中間值定理(The Intermediate Value Theorem)(均值定理)
- 指平面上一段固定端點的可微曲線，兩端點之中必然有一點，它的斜率與連接兩端點的直線斜率相同
    - ==上述的意思是，如果f(x)是可微，則在[a,b]中必有一點c，其斜率 = a和b割線的斜率==
- 若f(a)、f(b)異號，則必與x軸有交點--->必有一根
- 假設在連續的封閉區間[a,b]並令 N 為 f(a)、f(b)之間的任意數，其中f(a)不等於f(b)。則(a,b)中存在一數c，使得f( c ) = N 。


## 6.費馬定理
- <https://www.youtube.com/watch?v=-UU3lSgaw8g>
    
    <例外>
    - (1)極限存在
    - (2)一次微分不存在 ---> 如圖 ![Imgur](https://i.imgur.com/BkjIZXd.png)


## 7.臨界數(critical numbers) ==*(包含穩定點)*==
1. 設一點c在函數上面
2. f( c )的一次微分 = 0 or 不存在


## 8.穩定點(駐點)
- c一定要在函數上
- f( c )的一次微分 = 0
    - v.s臨界數 ==(缺少一次微分->不存在)==


## 9.反曲點(Inflection point)
- 定義 : 凹性改變
    - f(x)的二階導函數為==0== 或 ==不存在==
    ::: info
    但還不一定是反曲點
    
    需藉由代前後值，結果為異號--->凹性改變
    :::
    







###### tags: `微積分` `110` `2021`

<style>
.navbar-brand::after { content: " × FJUMIIA"; }
</style>