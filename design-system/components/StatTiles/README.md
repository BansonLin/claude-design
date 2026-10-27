# StatTiles

案例區的成果格：大數字＋單位、名稱、一行說明，整格可點、右上角箭頭。

- 共用邊格線（1px `navy-rule`），欄數由 `--cols` 指定（預設 4，1024px 以下 2 欄）。
- 數字用 `numeral`，單位用 small（0.9375rem、`navy-ink-2`）；箭頭 `brass-light`，hover 時格子底色換 `navy-deep`、箭頭右移 3px。
- 每格只講一個可數的交付物（「14 份策略簡報」），說明寫它包含什麼。
- 使用端提供：數字、單位、名稱、說明、連結。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
