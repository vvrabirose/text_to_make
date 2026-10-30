# Vivi studio

自然綠色系的一頁式接案作品集，使用原生 HTML、CSS 與 JavaScript，無須安裝套件或建置。

## 本機預覽

在專案目錄執行：

```sh
python3 -m http.server 8000 --bind 0.0.0.0
```

開啟本機的 8000 埠檢視。網站包含手機版、鍵盤焦點、減少動態效果偏好，以及 Email、Telegram 與作品外連。

## 內容與圖片

- `index.html`：品牌、服務、作品與聯絡內容。
- `style.css`：響應式版型。
- `assets/forest.png`：AI 生成的自然情境圖片，非客戶作品。
- 作品卡片及首頁六層視窗使用品牌擁有者提供的真實截圖，包含 WordPress 首頁、1shop 首頁、入場動畫及歡迎彈窗。

第一版供檢視，尚未發布。上線前需由品牌擁有者確認介紹、服務範圍及作品呈現。

首頁六層作品視窗以遠近透視與輕柔浮動效果呈現，支援減少動態效果偏好。截圖原檔保留於 assets，不依賴遠端網站載入。

WordPress 標誌來源：WordPress 官方 Dashicons 儲存庫 https://github.com/WordPress/dashicons/blob/master/sources/svg/wordpress.svg 。1shop 官方標誌仍待取得；未以重繪標誌代替。

## GitHub Pages

此網站可直接使用 GitHub Pages 靜態託管，無須建置。儲存庫 Settings → Pages → Build and deployment 選擇 Deploy from a branch，分支選 main，資料夾選 / (root)。正式網址需以 Pages 實際發布結果為準。
