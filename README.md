# 海洋能及負碳高速運算平台｜Prototype

此資料夾已整理為可直接放入 Git Repository 的靜態網站版本。

## 檔案結構

```text
.
├─ index.html
├─ assets/
│  └─ images/
│     └─ map.jpg
├─ .nojekyll
└─ README.md
```

## GitHub Pages

1. 將本資料夾內的檔案上傳到 Repository 根目錄。
2. 到 GitHub Repository → **Settings** → **Pages**。
3. Source 選擇 **Deploy from a branch**。
4. Branch 選擇要發布的分支（例如 `main`），資料夾選 `/ (root)`。
5. 儲存後等待 GitHub Pages 部署完成即可。

## 備註

- 首頁已改名為 `index.html`，GitHub Pages 可直接辨識。
- 圖台底圖已整理至 `assets/images/map.jpg`，並同步更新 HTML 相對路徑。
- 本版本未引用 CDN 或其他外部靜態資源，HTML、CSS、JavaScript 皆包含於 `index.html` 內。
