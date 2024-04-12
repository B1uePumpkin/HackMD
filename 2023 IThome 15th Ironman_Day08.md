# Day-8 新聞大亂鬥-MixerBox News、NewsBreak、World News

[![hackmd-github-sync-badge](https://hackmd.io/qAhdbCF1TT2RE-pVYFz_mw/badge)](https://hackmd.io/qAhdbCF1TT2RE-pVYFz_mw)



## 0. 前言

昨天介紹了功能強大的聯網工具WebPilot之後，今天再追加介紹幾個一樣是聯網，不過是用來查詢新聞的plugin吧

## 1. MixerBox News、NewsBreak、World News

這邊就廢話不多說，直接實際測試我找到的三個新聞相關plugin

### 1.1. MixerBox News

- 首先我使用MixerBox News這個插件搜尋今年有關Elon Musk的新聞，但他只找到一篇
![](https://hackmd.io/_uploads/S1Nx7rZ62.png)
- 仔細看了一下背後運行情況，發現他只找了**INSIDE 硬塞的網路趨勢觀察**一個平台，可能是被硬塞進來的吧(不好笑
![](https://hackmd.io/_uploads/BJXPhQB1a.png)
- 後來我又試了幾次，就算不只限今年也是只有一篇，換主題改查ChatGPT就直接沒有找到任何新聞了，然後每個回應都會硬插他自己的廣告，估計這個插件就是來蹭流量的而已，所以下面一位~
![](https://hackmd.io/_uploads/HkR3wSb63.png)

### 1.2. NewsBreak

- 第二個嘗試的是NewsBreak，出來的回應就比前面的那個好多了，不但數量多而且還都有Summary和連結，要說唯一的缺點可能就是要再自己轉換成中文吧。(才怪，看不懂英文是你的缺點)
![](https://hackmd.io/_uploads/ryyldB-a3.png)

### 1.3. World News

- 最後試的是World News，他給的回應就都是中文了，而且摘要直接縮減成一句話，簡潔有力也有附來源和日期
![](https://hackmd.io/_uploads/H1aAur-T2.png)

## 2. 綜合比較
經過三種同為新聞查詢類型的插件測試後，根據他們的回覆及查看背後運行程式碼，我整理出一些他們之間的差異

### 2.1. 查詢方式
- MixerBox News的查詢條件包含地區、語言、關鍵字等，其實算完整，不過可能會因為條件過多導致查詢結果滿足條件過於困難，最後什麼都沒查到只能推廣告給使用者(又在臭)
![](https://hackmd.io/_uploads/Sk1vcBZph.png)

- NewsBreak對於下關鍵字這點就表現得比較好，會自行延伸使用者下的關鍵字。像這邊他除了我原本給他的Elon Musk以外，還自己延伸出"Tesla CEO", "SpaceX founder", "Musk"以及"BusinessEconomy"這個類別
![](https://hackmd.io/_uploads/Sk1Nor-a2.png)

- World News關鍵字這邊就很簡單只有我給的Elon Musk，不過少與有少的好處，這樣搜尋結果更多元。而且他跟前面兩個不同的點是，他放更多的心力在整理回應，他在回應給使用者的資訊更多元，有日期、摘要等等。
![](https://hackmd.io/_uploads/rk7g3SZ6h.png)





## 3. 結語

就結果來說，最推薦使用來搜尋新聞的plugin是==WebPilot==，想不到吧uwu。說實在，這類plugin其實挺雞肋的，除了World News簡潔有力的搜尋結果**稍微**助於使用者快速篩選外，基本上用WebPilot就能解決了，完全不需要額外插件甚至是來蹭流量打廣告的(對沒錯我又在臭)。今天實測主要是讓大家知道之後要篩選插件能怎麼評斷(還有WebPilot是多麼Powerful)。那就明天見啦!