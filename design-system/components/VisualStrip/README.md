# VisualStrip

主視覺比較條：把多個提案稿縮成一排小圖，標出原推薦與定案參考。放在 Journey 卡片內，記錄視覺決策。

- 四欄；圖片保持原稿比例（976:412）、`cover`、圓角 `r-tag`、透明度 .9。
- 原推薦稿（`is-rec`）加 2px `brass-light` 外框、外推 2px、不透明；標籤寫在稿號後：`vtag`「原推薦」用 `brass-light`，`vtag-final`「定案底色參考」用 `navy-ink`。
- 被取代的推薦照實標「原推薦」，不刪除。對外版移除 `is-rec` 與「原推薦」標籤，只留定案參考。
- 只用在深藍案例區（外層 `.sec-case`，通常在 `.journey` 內）。
- 使用端提供：各稿縮圖、稿號、推薦與定案標記。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`；圖片是 CaseImagery 素材群組的上傳檔。
