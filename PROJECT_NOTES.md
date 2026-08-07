# 專案紀錄

## 專案概覽

這是一個以單一 `index.html` 建立的靜態網站雛形，使用 Bootstrap 5 製作基本版面元件。

## 檔案結構

```text
website/
├── index.html            # 網頁主檔
├── PROJECT_NOTES.md      # 本紀錄檔
└── images/               # 圖片素材
    ├── 01.jpg
    ├── 02.jpg
    ├── 03.jpg
    ├── 04.jpg
    ├── 05.jpg
    └── 06.jpg
```

## 現有頁面內容

- Bootstrap 導覽列（Navbar）
  - 品牌文字：`Navbar`
  - 選單項目：Home、Features、Pricing、Dropdown link
- Bootstrap 輪播元件（Carousel）
  - 使用圖片：`images/01.jpg`、`images/02.jpg`、`images/03.jpg`
  - 提供上一張／下一張控制按鈕
- 主要標題：`Hello, world!`

## 技術與相依項

- HTML5
- Bootstrap 5.0.2
  - CSS 與 JavaScript Bundle 皆由 jsDelivr CDN 載入
  - JavaScript Bundle 內含 Popper，支援導覽列下拉選單與輪播元件
- 無本機 CSS、JavaScript、套件管理設定或建置流程

## 資產使用狀態

目前共有 6 張 JPG 圖片；頁面輪播僅使用前 3 張，`04.jpg`、`05.jpg`、`06.jpg` 尚未被頁面引用。

## 注意事項

- 網頁語言目前為英文（`lang="en"`），標題與導覽文字仍為預設示範內容。
- `<title>` 與頁面主標題皆為 `Hello, world!`，建議替換為網站實際名稱。
- 圖片的 `alt` 屬性皆為 `...`，建議改為能描述圖片內容的替代文字，以提升無障礙性與 SEO。
- 原始檔中的部分中文註解顯示為亂碼，推測是編碼不一致；建議統一以 UTF-8 儲存檔案。

## 啟動方式

此專案沒有編譯步驟。以瀏覽器直接開啟 `index.html`，或透過任一靜態檔案伺服器提供此資料夾，即可檢視頁面。

## Github推送地址
USER NAME:kui870315-ai
專案名稱:zentangle_space-260807
HTTPS:https://github.com/kui870315-ai/zentangle_space-260807.git
SSH:git@github.com:kui870315-ai/zentangle_space-260807.git