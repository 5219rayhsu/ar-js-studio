# AR.js Studio 專案

AR.js Studio 專案的工作資料夾，用於保存 3D 模型與後續匯出的 AR 網頁。

## 資料夾

- `assets/models/`：3D 模型素材。

## 現有素材

- `assets/models/iphone_duo_3d_model_-_by_pikkme_studio.glb`
- 原始檔名標示作者為 Pikkme Studio；保留原檔名，授權資訊待補。

## AR.js Studio 匯出

- `index.html`、`assets/asset.glb`、`assets/marker.patt`：Studio 匯出的網頁與素材。
- `exports/ar.zip`：Studio 原始下載套件。
- `assets/marker.png`：Studio 預設辨識圖，供列印或在另一個螢幕顯示。

發布後，以手機瀏覽器開啟網站、允許相機，並將鏡頭對準辨識圖。執行時需要網路以載入外部 JavaScript。

網站：https://5219rayhsu.github.io/ar-js-studio/

GitHub Pages 從 `main` 分支根目錄發布，儲存庫與網站均為公開。
