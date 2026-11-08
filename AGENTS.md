# AGENTS

- 單檔 `index.html`（CSS、SVG 繪圖、JS 全內嵌），畫布 1600×900 以 `--s` 縮放。每頁一個 `.slide[data-key]`，對應 JS 中 `def(key,{max,labels,apply,...})` 控制器與 `N[key]` 講稿／提示。
- 新增 SVG 漸層 id 必須全檔唯一；共用漸層放在 body 開首的隱藏 `<svg>`。
- 只定義 `from` 的 keyframes 若元素本身 opacity:0，必須補 `to`（曾令實驗簿空白）。
- 發布：GitHub `porscheyeung/miracles`，main 根目錄 Pages。保留 `v1.html` 原檔。
- 內容遵守 README「內容原則」；不使用占星或其他宗教用語。
