# Chip

篩選用的膠囊按鈕（`.chip`），以 `aria-pressed` 表示選取，選取時改為墨色實心反白。

- 一列篩選前面放 `.flabel`（類別／階段），用 `.frow` 包起來；手機版改為橫向捲動、不換行。
- 計數放在 `.c-n`（0.75rem、tabular-nums），未選取時半透明。
- 外框是 `rule-strong`（對 paper 只有 1.91:1），所以選取狀態一定要靠實心反白表達，不能只換框線色。
- 深藍區塊內自動改用 `navy-rule` 外框、`navy-ink` 反白。
- 使用端提供：`<button type="button" class="chip" aria-pressed>`、文字、選用的計數。

靜態呈現：標記與 class 取自來源頁面，樣式來自 `components/bundle.css`。
