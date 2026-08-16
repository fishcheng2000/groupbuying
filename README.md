# 團購統計 — 發布到 GitHub Pages

只有 `index.html` 一個檔案，不需要安裝任何東西。

## 用 iPhone 發布（Safari 就能完成）

1. 先把 `index.html` 下載到「檔案」App。
2. Safari 開 `github.com`，登入（沒帳號就先註冊，免費）。
3. 右上角 `+` → **New repository**
   - Repository name：`tuan`（自己取，會出現在網址裡）
   - 選 **Public**（免費方案只有公開的 repo 能開 Pages）
   - 按 **Create repository**
4. 進到剛建好的 repo → **Add file** → **Upload files**
   → **choose your files** → 瀏覽 → 從「檔案」App 選 `index.html`
   → 下方按 **Commit changes**
5. 上方 **Settings** → 左側 **Pages**
   - Source：**Deploy from a branch**
   - Branch：**main** ＋ **/ (root)** → **Save**
6. 等 1～2 分鐘重新整理，頁面上會出現網址：
   `https://你的帳號.github.io/tuan/`
7. Safari 開那個網址 → 分享 → **加入主畫面**，之後就像 App 一樣點開就用。

## 之後要改東西

repo 裡點 `index.html` → 右上鉛筆圖示 → 改完 Commit，
或再 Upload files 上傳新的同名檔案覆蓋，網站一兩分鐘後自動更新。

## 資料存在哪裡

- 訂單和品項會**自動存在你開這個網頁的那台裝置的瀏覽器裡**，關掉再開還在。
- 換手機、換瀏覽器、清除瀏覽資料 → 資料不會跟著走。
- 所以收單告一段落，用右上角「匯出／備份」→「複製備份碼」貼到備忘錄留一份。
  換裝置時把備份碼貼回去按「還原備份」就接得上。

## 注意

GitHub Pages 的網址是公開的，任何人只要知道網址就能打開（不過每個人看到的都是自己
裝置上的資料，你的訂單不會被別人看到，因為資料沒有上傳到網路）。
