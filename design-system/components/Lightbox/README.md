# Lightbox

全螢幕看圖：上方張數與工具，中間大圖與左右翻頁，下方標題、示意聲明與分組。

- 底色 `lb-bg`（兩個主題相同），文字 #EEE；按鈕 1px 半透明白框、圓角 `r`，hover 時底色變亮。
- 大圖 `contain`、圓角 `r-tag`、`shadow-lightbox`，這是全站兩處陰影之一。
- 鍵盤：←／→ 翻頁、Esc 關閉，關閉後焦點回到原本點的那張圖；手機可左右滑動，翻頁鈕移到右下。
- 「開原圖」連到原始檔；說明列一定帶示意聲明。
- 開啟時 `html` 加 `lb-open` 鎖住捲動。實際使用時是 `position: fixed` 的對話框（`role="dialog"`、`aria-modal="true"`）；預覽改成固定高度方塊。
- 使用端提供：目前張數、原圖連結、圖片、標題、聲明、分組。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`；圖片是 CaseImagery 素材群組的上傳檔。
