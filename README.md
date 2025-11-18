# youtube-ad-block

輕量的 YouTube 廣告攔截濾鏡（供 uBlock Origin 使用）

這個專案提供一組 uBlock Origin 的自訂過濾規則，用來在 YouTube（含 YouTube Music）上攔截廣告。配合瀏覽器擴充套件 uBlock Origin 使用即可生效。

---

## 快速開始（1 分鐘上手）
1. 安裝 uBlock Origin（主建議）
   - Chrome / Chromium: 在 Chrome Web Store 安裝 uBlock Origin  
     https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm
   - Firefox: 在 Firefox Add-ons 搜尋 uBlock Origin

2. 若有人無法使用上方版本，使用備用的「uBlock Origin Lite」
   - 備用擴充： https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh
   - 兩個擴充的 Dashboard 位置通常類似，你可以用下面其中一個（把 <extension-id> 換成上面對應的 id）：
     - chrome-extension://cjpalhdlnbpafiamejdnhcphjbkeiagm/dashboard.html#1p-filters.html
     - chrome-extension://ddkjiahejlhfcafbddmgiahcphecmpfh/dashboard.html#1p-filters.html
   - 或透過擴充功能圖示 → 設定（齒輪）→ Dashboard → 「My filters / 自訂過濾器」

3. 匯入本專案的過濾規則  
   - 開啟本專案中的 `Youtube AD block.txt`（或在 repo 找到相應規則檔）  
   - 將內容複製貼到 uBlock Origin 的「我的過濾器（My filters）」區塊 → 按下「套用變更（Apply changes）」

4. 完成，重新載入 YouTube 頁面確認廣告是否被攔截。

---

## 支援範圍
- YouTube（影片內廣告、片前廣告等）  
- YouTube Music

---

## 使用注意與責任聲明
- 使用過濾規則有可能改變 YouTube 的某些功能或顯示行為。  
- 若因使用本過濾規則導致帳號被封或其他不可預期的後果，作者不負任何責任。請自行評估風險後再使用。  
- 若遇到問題、誤判或想新增規則，歡迎在本倉庫開 Issue。

---

## 常見問題（FAQ）
Q: 為什麼有時候還會看到廣告？  
A: YouTube 會不時改變廣告投放或版面，過濾規則需要更新。請確認你已貼上最新的規則並重新整理頁面。

Q: 我如何回復為原本狀態？  
A: 移除 uBlock Origin 中「我的過濾器」裡貼上的規則，按下「套用變更」並重新整理 YouTube。

---

## 想要貢獻或回報
- 如果你發現規則失效、誤判或有改進建議，請在本 repo 開 Issue 或提 Pull Request。  
- 建議在 PR 中描述測試步驟與環境（瀏覽器、版本、是否有其他擴充套件等）。

---

## 授權與版權
- 如果你希望本專案有明確授權，請在倉庫新增 LICENSE 檔案（例如 MIT、Apache-2.0 等）。目前 README 並未指定授權，請視情況補上。

---

## 聯絡與給作者支持
如果你覺得本工具有用，請幫忙按個 Star ⭐。若有問題或建議，歡迎在 Issues 提問 — 我會盡量回覆。

祝使用愉快！
