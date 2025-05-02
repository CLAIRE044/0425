# 國家領導人查詢系統

這是一個使用 Google Gemini AI API 的網頁應用程式，可以查詢世界各國現任領導人的相關資訊。

## 功能特點

- 即時查詢各國領導人資訊
- 提供領導人的姓名、職位和就任時間
- 支援繁體中文輸出
- 簡潔易用的使用者介面
- 安全的 API 金鑰管理

## 使用方式

1. 開啟 `leader_query.html` 檔案
2. 輸入您的 Google AI API Key
3. 在搜尋欄位中輸入想查詢的國家名稱（例如：台灣、美國、日本）
4. 點擊查詢按鈕或按下 Enter 鍵

## 系統需求

- 現代網頁瀏覽器（Chrome、Firefox、Edge 等）
- 有效的 Google AI API Key

## 檔案說明

- `leader_query.html`: 主要的查詢介面
- `proxy-server.js`: Node.js 代理伺服器（可選用）
- `server.py`: Python 代理伺服器（可選用）

## 安全性說明

- API Key 僅儲存在記憶體中，重新整理頁面後需重新輸入
- 不會將 API Key 儲存在任何永久儲存空間
- 所有請求都通過 HTTPS 進行加密傳輸

## 注意事項

- 請勿將您的 API Key 分享給他人
- 每個 API Key 都有使用限制，請謹慎使用
- 資料來源依賴於 Google Gemini AI 的即時回應

## 技術支援

如果您在使用過程中遇到任何問題，請：
1. 確認 API Key 是否正確
2. 檢查網路連線狀態
3. 確認瀏覽器是否為最新版本

## 授權說明

本專案採用 MIT 授權條款。您可以自由使用、修改和分發本程式碼，但需保留原始著作權聲明。

## 開發者資訊

本專案使用以下技術：
- HTML5
- CSS3
- JavaScript (ES6+)
- Google Gemini AI API
