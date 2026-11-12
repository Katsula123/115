# 操作日誌（Log）

> 本頁為**時間導向**的只增不減（append-only）紀錄，追蹤知識庫每次 `init`、`ingest`、`query`、`lint` 與 `research` 操作。
> 可使用 `grep "^## \[" log.md | tail -5` 快速檢視近期紀錄。

## [2026-11-12] init | 初始化 LLM 研究知識庫
- 新增：`AGENTS.md`、`README.md`、`.gitignore`、`index.md`、`log.md`、`overview.md` 及 `template-*.md` 模板組。
- 摘要：依據 Karpathy LLM Wiki 模式與繁體中文研究規範完成知識庫初始化。

## [2026-11-12] ingest | The Best of NIPPON47！47都道府縣「溫泉」特輯
- 保存原始資料：`raw-2026-11-12-gltjp-nippon47-hot-spring.md`（來源：https://www.gltjp.com/zh-hant/nippon47/hot-spring/）
- 新增：`article-gltjp-nippon47-hot-spring.md`、`concept-japan-onsen-classifications.md`、`comparison-japan-47-prefectures-onsen.md`
- 更新：`index.md`、`log.md`
- 摘要：完成首篇網頁測試攝取，並依使用者需求調整為單層大資料夾扁平結構。
