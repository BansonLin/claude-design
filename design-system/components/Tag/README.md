# Tag

小型狀態標籤：`tag-int`（內部狀態，`brass` 虛線框）、`tag-hist`（歷史版，`rule-strong` 實線框）、`pub-badge`（對外版）、`gt-code`（決策關卡代碼）。

- 標籤寫狀態，不寫裝飾：「暫停對外」「歷史版」「對外版」「G3」。
- `tag-int` 只出現在內部完整版（外層加 `data-sensitive`），對外版會整個隱藏。
- 字級 0.75rem、字距 .08em、圓角 `r-tag`；`pub-badge` 用 `r-pill`。
- 「註」這類前置標籤用 `brass-ink` 實心底、`paper` 字。
- 使用端提供：一到四個字的狀態文字。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
