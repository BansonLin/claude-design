# Button

頁面上的行動按鈕：`btn-primary`（墨色實心）與 `btn-ghost`（墨色外框），高度 3.1rem，圓角 `r`。

- 一個畫面最多一個 `btn-primary`，放在使用者最該做的那一步；第二個動作用 `btn-ghost`。
- 文字先寫動詞、短句：「看服務流程」「看案例」。結尾加 `<span class="arr">→</span>`，hover 時箭頭右移 4px。
- hover：`btn-primary` 底色換成 `brass-ink`；`btn-ghost` 底色換成 `paper-2`。
- 卡片內的小按鈕用 `btn-s`（2.25rem 高、0.8125rem 字）；深藍區塊內用 `btn-s btn-s-light`。
- 使用端提供：`<a>` 或 `<button>`、文字、選用的箭頭 span。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
