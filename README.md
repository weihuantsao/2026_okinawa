# 2026 沖繩親子旅 ＆ 慈霖幼兒園行事曆

本 repo 透過 **GitHub Pages** 一起 host 兩份**各自獨立**的頁面，用同一個網址前綴分享。
兩者皆為**自包含單一 HTML**、離線可開（地圖圖磚需連網載入）。

網址前綴：`https://weihuantsao.github.io/2026_okinawa/`

---

## 🏝️ 沖繩五天四夜親子包車行程規劃
- **檔案**：[`index.html`](index.html)
- **網址**：<https://weihuantsao.github.io/2026_okinawa/>
- **內容**：2026/10/29–11/2，9 位大人＋3 位幼童、兩台包車。含每日動線地圖（Leaflet）、當日時間軸、
  機票／飯店（BEB5・OMO5）／餐廳／包車訂位、購物攻略、古宇利島與各景點介紹、天氣等。
- **語系**：封面左上可切換「繁中／日本語」（記在瀏覽器裡；分享時可加 `?lang=ja` 直接開日文版）。
  日文放在 [`i18n/ja.js`](i18n/ja.js)，是 `{ 中文原句: 日文 }` 的字典，只在切到日文時才載入。
  **改了 index.html 的中文內文，要同步更新字典**，否則該句會顯示回中文；切到日文後在瀏覽器 console 執行
  `i18nMissing()` 可列出缺翻譯的句子。

## 📖 旅遊手冊（可列印・A4）
- **檔案**：[`handbook.html`](handbook.html)（排版原稿）・[`handbook.pdf`](handbook.pdf)（14 頁成品）
- **網址**：<https://weihuantsao.github.io/2026_okinawa/handbook.html>
- **內容**：從 `index.html` 重新編排成適合帶在身上的紙本：五天總覽、航班與集合、住宿與房間分配、
  每日時間表（含已訂餐廳電話地址、當日天氣）、預約／門票／現金清單、購物總覽、緊急聯絡、打包清單、花費備忘。
  不含地圖與互動元件。螢幕上看到的每一頁就是印出來的那一頁（A4 直式）。
- **重新產生 PDF**：改完 `handbook.html` 後用 Chrome 無頭模式輸出——
  `chrome --headless=new --no-pdf-header-footer --print-to-pdf=handbook.pdf file:///<絕對路徑>/handbook.html`
  （或直接開網頁按右上「列印／存成 PDF」）。內文有改時記得同步 `index.html` 的對應資訊，兩者目前對齊 v4.30。

## 🗓️ 慈霖幼兒園 115 學年度第一學期行事曆（互動版）
- **檔案**：[`TL_day.html`](TL_day.html)
- **網址**：<https://weihuantsao.github.io/2026_okinawa/TL_day.html>
- **內容**：2026/08–2027/01 互動月曆。可切換月份、點日期看當天「行政／教保活動」、依類別篩選、
  假日紅字、重點活動標星，並顯示每月學期主題、每週五固定事項與未指定日期的月度事項。

---

> 兩份頁面彼此**獨立、互不連結**，只是搭同一個 Pages 站台一起 host。
> 頁面右上／頁尾標有版本號（index.html），可辨識是否為最新版本。
> 實際資訊以官方公告 / 各訂位確認為準。
