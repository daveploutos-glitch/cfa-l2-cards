# CFA L2 溫習平台

CFA Level II 全部十個科目（＋補底 Level I 基礎）的溫習網頁：記憶卡（間隔重複）、自由練習、筆記、學習計劃、每日記錄。

線上使用: https://daveploutos-glitch.github.io/cfa-l2-cards/

- `index.html` 由 `srs.py export` 產生（卡片、學習計劃、每日記錄、筆記索引、KaTeX 已內嵌）；卡片圖片在 `img/`（webp）。
- `plan.json`：學習計劃（2026-09-27 至 2027-05-22，每日一項）；`log.json`：每日記錄（由 progress.md 產生）；`notes/`：老師筆記 PDF（最新累積版 + 每日快照）及 `index.json`。
- 學習進度及用戶自己的每日記錄儲存在瀏覽器 localStorage；用戶上載的筆記存在瀏覽器 IndexedDB，只在該裝置。網址固定不變，更新網站不會遺失進度。
