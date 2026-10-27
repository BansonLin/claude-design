# AngleTags

角度標籤：一排不可點的膠囊，列出一件工作涵蓋的面向（例如核實的 7 個角度）。

- 0.84375rem、1px `navy-rule` 框、`r-pill`、內距 .25rem .75rem，間距 .45rem；只有文字，不加圖示。
- 它是清單，不是按鈕：用 `<ul class="angles"><li>`，沒有 hover 與選取狀態，免得被誤認成 Chip。
- 上方用 `mini-h` 寫數量（「7 個主要角度」）。
- 只用在深藍案例區（外層 `.sec-case`）。
- 使用端提供：數量標題與 3–8 個短詞。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
