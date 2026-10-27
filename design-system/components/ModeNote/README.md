# ModeNote

內部完整版的提醒條，加上敏感資料標記 `.sx`／`.sx-long`：說明哪些內容在對外模式會被隱藏或替換。

- 提醒條用 1px `rule-strong` 虛線框、0.75rem、`ink-2`，開頭粗體「內部檔」。
- 短詞用 `.sx`（`sens` 淡黃銅底）；整句用 `.sx-long`（`brass` 點狀底線），避免整段上色看起來像被選取。
- 只在內部完整版出現：外層加 `data-sensitive`，`html.is-public` 時整個隱藏；對外檔另外產出，不靠瀏覽器隱藏來保密。
- 使用端提供：提醒文字，以及要標記的詞句。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
