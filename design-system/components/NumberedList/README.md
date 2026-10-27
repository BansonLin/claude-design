# NumberedList

編號清單（`.elist`）：宋體 `brass-ink` 序號在左，右邊「標題＋一句說明」，條目間 1px `rule` 分隔。

- 用在「請業主準備什麼」「我們會帶來什麼」這類要逐項核對的清單；兩份清單並排成兩欄。
- 標題 1.0625rem 宋體，說明 0.9375rem `ink-2`；序號由 CSS counter 產生，使用端不用寫數字。
- 開始流程用 StepGrid 版本（`.esteps`）：四格、`paper` 底、上方 0.75rem 的 `brass-ink` 序號。
- 使用端提供：清單標題、每項標題與說明。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
