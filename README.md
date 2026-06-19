# Rita Icon Studio · 圖示產生器

輸入文字（中／英）即可搜尋並產生對應圖示，調整風格與顏色後下載為**去背 PNG / JPG**。單一 HTML 檔，雙擊即用。

> 圖示資料來自 [Iconify](https://iconify.design)（20 萬+ 開源圖示），去背與匯出皆在瀏覽器本機完成，不上傳任何檔案。

## ✨ 功能

- 🔤 **中英文搜尋** — 輸入「地球 / 愛心 / 設定」或 `globe / heart`，內建約 200 組中英對照
- 🧩 **多格選擇** — 一個關鍵字同時列出多個不同來源／風格的圖示
- ✏️ **風格篩選** — 空心線條 / 實心填滿 / 彩色
- 📏 **線條粗細** — 線條型圖示可調 0.5–4.0
- 🎨 **換色 + 滴管** — 色票、色盤、HEX，支援瀏覽器滴管吸色（Chrome / Edge）
- 🖼 **去背下載** — 透明 PNG，或自訂白底／底色；亦可輸出 JPG
- 📦 **批次 ZIP** — 勾選多個圖示一次打包下載，可加檔名前綴
- 📐 **自訂尺寸** — 128 / 256 / 512 / 1024 或自訂 16–4096 px
- 💾 **記住設定** — 顏色、線粗、尺寸等自動保存（localStorage）

## 🚀 使用方式

直接下載 `index.html` 用瀏覽器開啟即可，無需安裝。

或線上開啟（啟用 GitHub Pages 後）：

```
https://<你的帳號>.github.io/rita-icon-studio/
```

## 🛠 技術

- 純前端：HTML + CSS + 原生 JavaScript（無建置流程）
- [Iconify API](https://iconify.design) — 圖示搜尋與 SVG 取得
- [JSZip](https://stuk.github.io/jszip/) — 批次打包
- Canvas — 本機 SVG → PNG / JPG 去背匯出

## 📄 授權

[MIT](LICENSE) © 2026 Rita
