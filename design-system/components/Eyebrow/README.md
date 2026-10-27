# Eyebrow

區塊最上方的眉標：兩位數編號加英文大寫標籤，例如「01 CHALLENGES」。

- 字型 `eyebrow`（0.8125rem、500、字距 .2em、大寫），色彩 `brass-ink`；深藍區塊內改用 `brass-light`。
- 編號放在 `.no`，改用宋體 600、字距 .06em。首屏可以只放標籤、不放編號。
- 區塊內的次一層小標用 `.mini-h`（0.75rem、字距 .18em、ink-3），後面可接一段補充說明 span。
- 使用端提供：編號、英文標籤（或中文小標）。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
