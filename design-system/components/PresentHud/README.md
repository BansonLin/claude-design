# PresentHud

簡報模式的控制列：開啟後取代導覽列上的「簡報模式」按鈕，放上一頁、頁數、下一頁、目前段落標題與「結束簡報」。

- 只在 `html.is-present` 時出現；同時根字級放大到 112.5%，每個 `[data-slide]` 撐滿一個畫面。
- 按鈕為 `r-pill` 膠囊、1px `rule-strong` 框；「結束簡報」用墨色實心反白，是列上唯一的實心按鈕。
- 頁數用 tabular-nums，並加 `aria-live="polite"` 讓報讀器唸出換頁。
- 段落標題只在 1600px 以上顯示，超過 11rem 以省略號截斷；640px 以下隱藏分段切換與品牌字。
- 鍵盤 ←／→ 或 PageUp／PageDown 換頁，Esc 結束。
- 使用端提供：頁面上各段的 `data-slide` 與 `data-title`。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
