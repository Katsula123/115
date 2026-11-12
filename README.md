# LLM 研究知識庫（LLM Wiki）

本儲存庫採用 Karpathy 提出的 **LLM Wiki** 模式建立，並採**單層大資料夾結構**（不細分子資料夾），透過檔名前綴區分原始資料（`raw-*`）、Wiki 頁面（`paper-*`、`article-*`、`concept-*`、`model-*`、`comparison-*`）、研究筆記（`note-*`）與簡報（`outline-*`、`slides-*`）。

## 快速開始

1. **用 Obsidian 開啟本資料夾**：將 `llm-wiki/` 設為 Obsidian Vault，即可透過 Graph View、雙向連結與 Dataview 外掛瀏覽。
2. **攝取資料（Ingest）**：將論文或文章貼給 Agent，Agent 會自動以 `raw-` 前綴保存原文，並建立或更新對應的 Wiki 頁面、`index.md` 與 `log.md`。
3. **深度研究與簡報**：提出研究問題後，Agent 會依序產出 `note-*.md`、`outline-*.md` 與清幽日系編輯風的 `slides-*.html`。
