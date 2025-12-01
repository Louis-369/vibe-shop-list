# ✈️ 世界口袋 To Buy (World Pocket To Buy)

這是一個專為旅行者設計的行動優先購物清單 App。不需要安裝任何 App，只需一個 HTML 檔案即可在瀏覽器中運行，並支援 PWA 安裝至手機主畫面。

## ✨ 特色功能

- **📱 行動優先設計**: 針對手機操作優化，支援滑動手勢 (左滑刪除、右滑購買)、震動回饋與單手操作介面。
- **💱 即時匯率換算**: 整合 API 抓取即時匯率，自動換算 JPY, KRW, USD, EUR 等幣別至 TWD。
- **🎨 24 節氣主題**: 獨家的動態主題系統，隨季節與節氣自動變換 App 色調與風格。
- **📋 智慧清單管理**:
  - 支援單筆輸入與**批次貼上** (自動辨識名稱與金額)。
  - 自訂排序 (拖曳排序)、分類篩選、購物助手標籤。
  - 拍照記錄商品與實購憑證。
- **💾 資料安全**: 資料儲存在瀏覽器本地 (LocalStorage)，並支援匯出/匯入備份 (JSON 檔案或純文字代碼)。

## 🛠️ 技術棧

此專案為單頁應用程式 (Single Page Application)，無需後端伺服器。

- **HTML5**: 語意化標籤與 PWA 設定。
- **CSS (Tailwind CSS)**: 使用 Tailwind CSS CDN 進行快速樣式開發與 RWD 設計。
- **JavaScript (Vanilla)**: 原生 JS 實作所有邏輯，包含 DOM 操作、資料存取、API 串接。
- **Libraries**:
  - [SortableJS](https://sortablejs.github.io/Sortable/): 處理拖曳排序。
  - [FontAwesome](https://fontawesome.com/): 圖示庫。
  - [Google Fonts](https://fonts.google.com/): 使用 "Noto Sans TC" 與 "Zen Maru Gothic" 字體。

## 🚀 如何使用

1.  下載專案中的 `index.html` 檔案。
2.  直接使用瀏覽器 (Chrome, Safari, Edge) 開啟該檔案即可使用。
3.  **手機體驗**: 在手機瀏覽器開啟後，選擇「加入主畫面」(Add to Home Screen)，即可像原生 App 一樣全螢幕使用。

## 📂 檔案結構

- `index.html`: 包含所有程式碼 (HTML/CSS/JS) 的核心檔案。

---

_祝您購物愉快！ Buy Happy!_ 🛍️
