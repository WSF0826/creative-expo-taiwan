# creative-expo-taiwan

## 專案用途簡介

本專案是「2026 文博會親子行程導覽」靜態網頁，主要提供南港展覽館 1 館的親子行程、展區地圖、設施資訊，以及適合 3 歲與 7 歲兒童的參觀動線。網頁以 `index.html` 為入口，搭配圖片素材與 Tailwind CSS CDN 呈現版面。

## 主要檔案結構

```text
.
├── README.md        # 專案說明文件
├── index.html       # 靜態網頁入口
├── map-full.jpg     # 頁面使用的地圖圖片素材
├── 左上區塊_3.jpg   # 頁面圖片素材
├── 左下區塊_3.jpg   # 頁面圖片素材
├── 中上區塊_3.jpg   # 頁面圖片素材
├── 中下區塊_3.jpg   # 頁面圖片素材
├── 右上區塊_3.jpg   # 頁面圖片素材
├── 右下區塊_3.jpg   # 頁面圖片素材
└── .nojekyll        # GitHub Pages 設定檔
```

## 直接使用瀏覽器開啟

由於本專案是靜態網頁，可以直接用瀏覽器開啟 `index.html`：

1. 在檔案總管或 Finder 中找到專案資料夾。
2. 雙擊 `index.html`。
3. 頁面會在預設瀏覽器中開啟。

也可以在終端機中執行：

```bash
open index.html
```

> 若不是 macOS，請改用作業系統提供的檔案開啟方式。

## 使用本機伺服器開啟

若要透過本機 HTTP 伺服器瀏覽，請在專案根目錄執行：

```bash
python3 -m http.server 8000
```

啟動後，在瀏覽器開啟：

```text
http://localhost:8000
```

停止伺服器時，可在終端機按下 `Ctrl + C`。

## Build、Lint 與自動化測試

目前專案沒有 build、lint 或自動化測試流程；修改內容後請直接在瀏覽器中檢查頁面顯示是否正常。

## 相依資源

頁面目前依賴 Tailwind CSS CDN，因此瀏覽器需要能連線到 CDN，才能載入 Tailwind CSS 樣式。
