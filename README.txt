Forest Converter V1.0
=====================

Forest Studio 的乾淨繁簡轉換工具。

功能
- 簡體 → 繁體（台灣繁體標準）
- 繁體 → 簡體
- 貼上 / 清空 / 一鍵複製
- 交換內容及轉換方向
- 保留段落、標點與換行
- Ctrl / Command + Enter 快速轉換
- Responsive：電腦雙欄、手機上下排列
- PWA：部署至 HTTPS 後可加入手機主畫面
- 文字在瀏覽器內轉換，不會送往 Forest Studio 伺服器

轉換核心
- opencc-js 1.4.2
- 首次開啟需要網路載入 OpenCC，PWA Service Worker 會嘗試快取供後續使用。

部署至 GitHub Pages
1. 建立一個新的 GitHub repository。
2. 把本資料夾內全部檔案上傳到 repository root。
3. Repository Settings → Pages。
4. Source 選 Deploy from a branch。
5. Branch 選 main / root，儲存。
6. GitHub Pages 網址生效後即可使用。

V1.0 · designed by Forest Studio
