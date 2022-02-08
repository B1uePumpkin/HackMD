# GitHub上傳步驟


:::success
此方法可適用於任一開發環境
:::
## 初次
1. 開啟CMD
1. cd到要上傳之檔案的位置--->例如`cd C:\Users\yuhao\IdeaProjects\myproject`
4. 輸入`git config --global user.name "pc端使用者名稱"`<br>再輸入`git config --global user.email example@email.com`(把example@email.com替換為註冊Github的帳號)
4. 登入[Github](https://github.com/)
1. 創建一個新的空間，如圖 <br>![Imgur](https://i.imgur.com/QuY3LlE.png =40%x)

    &nbsp;
2. New--->取個名稱(其他可忽略)--->create<br>![Imgur](https://i.imgur.com/gIonqxE.png =80%x)
3. 這裡建議名稱不要取中文，否則顯示會是"-"![Imgur](https://i.imgur.com/cTYwDuj.png =80%x)
0. 再開啟CMD，依序輸入以下指令<small>(所有指令皆可在新創建的空間中找到)</small>![Imgur](https://i.imgur.com/UiYjtXz.png)
    1. `git init`
    2. `git add README.md` (打git add .就好)
    3. `git commit -m "first commit"` (""中為敘述，可任意更改)
    4. `git branch -M main`
    5. `git remote add origin https://github.com/B1uePumpkin/test.git` (https後的那串每個人都不同，結構為https://github.com/使用者名稱/空間名.git)
    6. `git push -u origin main` (意即push)


## 二次以後
:::success
下列方法為intellij無法直接從CMD上傳時使用
其他開發環境在第4點後直接在CMD `git push -u origin main` 即可
:::
1. 開啟CMD
2.  一樣cd 到你的檔案位置
3. `git add .`
4. `git commit "裡面打敘述"`
5. 出現類似以下圖片，代表成功建造上傳檔，接下來要到intellij (或你直接打git push也可以)<br>![Imgur](https://i.imgur.com/d5TAOK6.png)
6. 開啟intellij
7. 按下綠色push鍵
8. 選擇檔案並push
9. 若右下角出現<br>![Imgur](https://i.imgur.com/BOZu7WV.png)<br><br>恭喜成功，記得到Github查看哦               有問題問小卓(^^)


&nbsp;
---

###### tags:`程式設計` `110` `2021` 

<style>
.navbar-brand::after { content: " × FJUMIIA"; }
</style>
