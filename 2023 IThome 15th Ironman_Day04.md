# Day-4 Prompt詠唱術

## 0. 前言
前面講解完ChatGPT背後的原理後，今天開始進入詠唱環節吧~
基本上只要掌握兩大原則就能充分發揮他的能力:


## 1. 指示要清楚且具體
### 1.1. 使用分隔符號
- 使用`"""`、`===`、`‵‵‵`...等
- 是一個有效避免`Prompt Injection`的方式

:::danger
什麼是Prompt Injection?
這裡是屬於資安層面，有點偏離我們的主題，所以就用一句話簡單帶過:

***將惡意程式碼或指令插入提示文本中，以利用系統漏洞執行未授權操作或洩漏敏感資訊。***

:::
- 下方的例子是將文章用上下`===`隔開，防止與問題搞混
![](https://hackmd.io/_uploads/HyMyNCJa3.png)


### 1.2. 要模型輸出結構化的格式
- HTML
- python列表
- ...
- 下方的例子是將我想要得到的答案輸出成python的列表格式，方便我用在程式碼中等等
![](https://hackmd.io/_uploads/r1d94016n.png)


### 1.3. 要模型檢查條件是否符合
- 若符合[條件]則做A，否則做B
- 下方的例子是請ChatGPT判斷數量，多於三個就輸出成列表，反之則輸出成鍵值對

![](https://hackmd.io/_uploads/rkD88A1pn.png)


### 1.4. 少樣本提示(few-shot prompting)
- 事先提供幾個任務完成的例子
- 下方例子是先提供其中一個解答的格式，讓ChatGPT有例可循

![](https://hackmd.io/_uploads/HJ1HuCka2.png)

## 2.讓模型有時間思考
- 需要這麼做是因為LLM目前有一個大問題，就是很會瞎掰。所以接下來會教大家如何**強迫**ChatGPT思考

![](https://hackmd.io/_uploads/Hk2z90kan.png)
- 上圖很明顯原來哈利持有210塊，所以按照題目敘述應該最後會剩下195塊，但是ChatGPT省略了部分資訊導致答案錯誤


### 2.1. 指示模型，在給出答案前先制定自己的解法
- 下圖可以看到，當我們強制規定他必須怎麼思考時，基本就不會出錯
![](https://hackmd.io/_uploads/HJ9YI1lp3.png)


## 3. 其他實用的基礎功能
1. 生成(Write/Create)
2. 總結(Summarize)
3. 翻譯(Translate)
4. 重寫(Rewrite)
5. 括寫(Expand)
6. 解釋(Explain)
7. 簡化(Shorten)


## 4. 小祕訣
1. 角色扮演
    - ChatGPT很喜歡角色扮演，給他一個背景清晰、而且是某一領域專家的角色，他能夠更快進入你prompt的狀況內
![](https://hackmd.io/_uploads/HJRYE2gp2.png)


2. 讓ChatGPT提供你prompt
    - 可以問ChatGPT該如何下關鍵字來得到更理想的回答
![](https://hackmd.io/_uploads/SkOUrneT2.png)

## 5. 結語
今天的這些內容可以說是使用ChatGPT最大的重點，只有不會問的人，沒有ChatGPT不會的問題。所以盡全力去研究這神奇的prompt詠唱法吧!