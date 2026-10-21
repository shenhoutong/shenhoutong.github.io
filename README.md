# 身後通

家人過世後要辦哪些事的導航網頁。回答最多 8 個簡單的問題，就能看到依自家情況、依期限排好的待辦清單。
每一項都寫了去哪裡辦，並附官方來源和查證日期；有期限的項目會估算出截止日。

- 網址：https://shenhoutong.github.io/
- 版本：v3.12

## 隱私

- 您的回答和打勾進度只存在您自己手機（或電腦）的瀏覽器裡，不會上傳到任何地方。
- 網頁加了安全設定（Content-Security-Policy），瀏覽器不准這個網頁在背景自己連到外部網站。
  只有您自己點官方連結、「回報錯誤或過時的資料」或超商列印的網站時，才會打開別的網站。
- 回報錯誤用 Google 表單：只會先填好是哪一頁和版本，不會帶您的回答。
- 這個網站放在 GitHub Pages。GitHub 會為了安全記錄訪客的 IP 位址（[GitHub 官方說明](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)）。

## 聲明

僅供參考，以官方公告為準；不是法律意見。有問題請自行詢問律師、地政士（代書）或辦理單位。
這是個人製作的參考工具，不是政府網站。

## 檔案

| 檔案 | 做什麼 |
| --- | --- |
| `index.html` | 整個工具（內容、畫面、程式都在這一個檔案） |
| `manifest.webmanifest` | 加到手機主畫面時的名稱和圖示 |
| `apple-touch-icon.png`、`icon-*.png`、`favicon*` | 主畫面和瀏覽器分頁的小圖示 |
| `og-image.png` | 在 LINE、Facebook 貼網址時顯示的預覽圖 |
| `.nojekyll` | 告訴 GitHub Pages 直接放檔案、不要另外轉換 |
