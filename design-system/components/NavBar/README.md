# NavBar

固定在頂端的導覽列：左邊品牌字標，中間段落連結，右邊工具（完整／對外切換、簡報模式、目錄）。

- 高度 `nav-h`（3.75rem），底色 `paper` 90% 加背景模糊，下緣 1px `rule`。
- 品牌用字不用圖：`.brand-name` 宋體 600、字距 .08em，後接 `.brand-sub`（ink-3、字距 .16em），手機版隱藏副標。
- 目前段落用 `aria-current="true"`，以 2px `brass` 底線標示。
- 內部檔用 `.seg` 分段切換「完整／對外」；對外檔改放 `.pub-badge`「對外版」。
- 1024px 以下連結收進「目錄」選單，展開時用 `shadow-menu`。
- 使用端提供：品牌名、副標、段落錨點、工具按鈕。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
