# Richart 今日最佳方案（免費、無資料庫）

## 最簡單部署：GitHub Pages
1. 在 GitHub 建立新的 public repository，例如 `richart-reward-helper`。
2. 把此資料夾內的 4 個檔案上傳到 repository 根目錄。
3. Repository → Settings → Pages。
4. Source 選 `Deploy from a branch`，branch 選 `main`、資料夾選 `/ (root)`。
5. 等待 GitHub 顯示網址後，用 iPhone Safari 開啟。
6. Safari 分享 →「加入主畫面」。

GitHub Pages 免費，不需要資料庫。交易資料只儲存在該裝置瀏覽器 localStorage。

## OCR
- 點「辨識截圖」會使用 Tesseract.js 在裝置端辨識，圖片不會上傳到自建伺服器。
- OCR 套件與繁中模型第一次使用時會從公開 CDN 下載，因此需網路。
- 若 OCR 效果不佳，使用 iPhone 照片的「原況文字」複製整張截圖文字，再貼入網頁解析。

## 重要限制
- 商家回饋以台新銀行的特店代號/MCC為準，網頁只能估算。
- LINE Pay券未追蹤每月500點上限。
- 假日自動判斷包含週末及內建2026假日，可手動覆寫。
- 規則版本：2026-07-18。
