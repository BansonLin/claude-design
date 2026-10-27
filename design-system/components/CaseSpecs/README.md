# CaseSpecs

案例區的規格表：每列「項目／內容／事實等級」，放在 `navy` 底上。

- 三欄格線 4.5rem / 1fr / auto；列之間 1px `navy-rule`。
- 項目用 0.8125rem `navy-ink-2`、字距 .1em；內容 1rem `navy-ink`；等級用 FactLevel。
- 業主名稱這類對外不宜揭露的資訊，內部版加 `.sx` 標示、對外版替換成概稱（「宜蘭在地業主」）。
- 使用端提供：規格列與每列的事實等級。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
