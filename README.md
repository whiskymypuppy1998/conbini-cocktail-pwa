# conbini-cocktail-pwa

# 便利商店調酒遊戲 (PWA 版)

這是一個 **便利商店食材調酒遊戲**，以 PWA (Progressive Web App) 製作，支援 iOS/Android 安裝到主畫面，像 App 一樣全螢幕運行。

## 🎮 遊戲玩法
1. 點擊「抽食材 1」與「抽食材 2」按鈕。
2. 隨機抽出兩個便利商店食材。
3. 發揮創意，用這兩個食材調出屬於你的飲品！

---

## 📱 功能特色
- **PWA 支援**：可加到手機主畫面，像 App 一樣打開。
- **離線快取**：使用 Service Worker，在無網路下也能運行。
- **全螢幕體驗**：安裝後沒有瀏覽器網址列。

---

## 📂 專案結構

```text
.
├─ index.html          # 主頁面
├─ style.css           # 樣式
├─ script.js           # 遊戲邏輯
├─ manifest.json       # PWA 設定
├─ service-worker.js   # 離線快取
└─ icons/              # App 圖示 (192x192, 512x512)
```

---

## 🚀 部署到 GitHub Pages
1. 建立一個新的 GitHub repository。
2. 上傳整個專案（包含 `index.html`、`manifest.json` 等）。
3. 到 **Settings → Pages**，將 branch 設定為 `main` 和 `/ (root)`。
4. 取得網址，例如：
https://你的帳號.github.io/drink-game/

---

## 📲 安裝到 iPhone/Android
1. 用 Safari/Chrome 打開遊戲網址。
2. 點選「分享 → 加到主畫面」。
3. 在桌面點擊 icon，即可全螢幕開啟遊戲。

---

## 🛠️ 開發備註
- 遊戲素材與邏輯皆為前端靜態檔案，無需後端。
- `manifest.json` 可修改名稱與顏色。
- 請替換 `icons/icon-192.png` 和 `icon-512.png` 為你的 App 圖示。

---

## 📌 版本
- **v1.0.0** 初版 (PWA 支援)
