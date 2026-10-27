# SourceChip

把一句陳述連到它的出處：`.src-chip`（行內出處）與 `.ref-chip`（卡片底部的「本案交付物」）。

- 每個數字或主張後面都要能接一個出處 chip，這是「事實可追溯」在介面上的樣子。
- 行內出處前面放 `.src-label`「出處」；卡片底部用 `.refs` 區塊，上緣是 `rule-strong` 虛線，小標「本案交付物」。
- 圓角 `r`，外框 `rule`／`rule-strong`；hover 外框換成 `brass`。
- 使用端提供：出處名稱（含版本，例如「市場分析 v0.3」）與連結。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
