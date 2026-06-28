# Knowledge Adventure

GitHub Pages 部署用整理版。

## 使用方式

1. 將本資料夾內所有檔案上傳到 GitHub repository 根目錄。
2. 確認根目錄直接包含：
   - `index.html`
   - `START_GAME.html`
   - `assets/`
   - `.nojekyll`
3. 到 GitHub repository 的 **Settings → Pages**。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選擇 `main`，資料夾選 `/root`，儲存。
6. 等待 GitHub Pages 產生網址後，開啟 `index.html` 即可執行。

## 注意

- 不要只上傳外層 zip；請解壓後把內容放到 repository 根目錄。
- `assets/` 路徑不可改名，否則圖片與音樂會失效。
- `.nojekyll` 請保留，避免 GitHub Pages 忽略部分底線資料夾或靜態檔。
- `START_GAME.html` 保留作為直接啟動頁；`index.html` 是 GitHub Pages 預設入口。
