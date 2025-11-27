# vibe-shop-list

# ShunMemo | 旬の買い物 🛍️

ShunMemo 是一款專為**日本/韓國旅遊購物**設計的漸進式網頁應用程式 (PWA)。
它結合了「日系可愛風格」與「實用購物功能」，幫助旅行者輕鬆管理購物清單、計算匯率，並解決語言溝通問題。

![App Preview](https://img.shields.io/badge/Style-Kawaii-pink) ![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20iOS%20%7C%20Android-blue) ![License](https://img.shields.io/badge/License-MIT-green)

## ✨ 特色功能 (Features)

### 🌸 沉浸式體驗

- **二十四節氣主題**：App 會根據當前日期自動變換配色與問候語（春櫻、夏海、秋楓、冬雪）。
- **日系可愛 UI**：使用圓潤的 `Zen Maru Gothic` 字體與和紙質感背景。

### ✈️ 出國購物優化

- **雙幣即時換算**：輸入當地價格（JPY/KRW），即時顯示換算後的台幣（TWD）參考價。
- **給店員看模式 (Clerk Mode)**：一鍵放大商品圖片與名稱，背景變暗，方便與店員溝通詢問。
- **用途分類標籤**：清楚標示「自用」、「送禮」或「代購（幫誰買）」。

### 📱 像 App 一樣好用

- **PWA 支援**：可加入手機主畫面，離線也能開啟（基本功能）。
- **備份與還原**：透過 Web Share API 直接將資料備份到 Apple 備忘錄或 Google Keep。
- **隱私優先**：所有資料皆儲存於瀏覽器 LocalStorage，不需註冊帳號，不相關伺服器。

---

## 🛠 技術規格 (Technical Specifications)

本專案採用 **Single Page Application (SPA)** 架構，無後端伺服器依賴。

| 項目         | 技術/工具                                          | 說明                                                |
| :----------- | :------------------------------------------------- | :-------------------------------------------------- |
| **核心架構** | HTML5, Vanilla JavaScript (ES6+)                   | 單一 `index.html` 檔案，零依賴建置                  |
| **樣式框架** | **Tailwind CSS** (v4 via CDN)                      | 快速切版與 RWD 響應式設計                           |
| **字體系統** | **Noto Sans TC** (思源黑體)<br>**Zen Maru Gothic** | 中文內容清晰不缺字<br>標題數字維持日系可愛感        |
| **資料儲存** | Browser **LocalStorage**                           | `shunmemo_items` (清單), `shunmemo_settings` (設定) |
| **外部 API** | ExchangeRate-API                                   | 獲取 TWD/JPY/USD/KRW 即時匯率                       |
| **圖標庫**   | Font Awesome 6 (Free)                              | 介面圖標                                            |
| **部署平台** | **GitHub Pages**                                   | 靜態網頁託管                                        |

---

## 🚀 快速開始 (Quick Start)

### 1. 線上體驗

前往：`https://您的帳號.github.io/shun-memo/` (請替換為您的實際網址)

### 2. 本地開發 (Local Development)

由於本專案為單一 HTML 檔案，您不需要安裝 Node.js 或 npm。

1.  複製專案：
    ```bash
    git clone https://github.com/your-username/shun-memo.git
    ```
2.  直接用瀏覽器打開 `index.html` 即可執行。
3.  推薦使用 VS Code 的 "Live Server" 插件進行即時預覽。

---

## 📲 安裝到手機 (PWA)

**iOS (Safari):**

1.  在 Safari 開啟網頁。
2.  點擊底部「分享」按鈕 (方框箭頭)。
3.  選擇「加入主畫面」。

**Android (Chrome):**

1.  在 Chrome 開啟網頁。
2.  點擊右上角選單 (三點)。
3.  選擇「安裝應用程式」或「加到主畫面」。

---

## 📂 檔案結構

```
shun-memo/
├── index.html      # 核心應用程式 (HTML/CSS/JS 全部整合於此)
└── README.md       # 專案說明文件
```

---

## 📝 版本紀錄

- **v2.1**: 修正繁體中文缺字問題 (Noto Sans TC)，優化設定開關動畫，修正數字鍵盤輸入。
- **v2.0**: 新增匯率換算、給店員看模式、備份還原機制。
- **v1.0**: 基礎購物清單功能，節氣主題變換。

---

## 📄 授權 (License)

Distributed under the MIT License. See `LICENSE` for more information.
