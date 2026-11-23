# 手部衛生 LLM Wiki

> 給第一次陪病家屬的手部衛生知識庫，並以此製作教學 HTML 簡報。

## 主題簡介
（請用自己的話寫 2–3 句：為什麼選這個主題、這個 Wiki 想幫誰理解什麼。）

## 結構
| 路徑 | 說明 |
|---|---|
| `raw/` | 原始資料（不修改），清單見 `raw/sources.md` |
| `wiki/index.md` | 所有 Wiki 頁面目錄（每次 ingest 後更新） |
| `wiki/log.md` | Ingest／檢查／修正紀錄 |
| `wiki/sources/` | S1–S5 每篇資料的摘要頁 |
| `wiki/concepts/` | 概念頁（手部衛生、洗手5時機…） |
| `rules.md` | 給 AI 的 Wiki 維護規則（相當於 CLAUDE.md） |
| `mapping.md` | 簡報頁 ↔ Wiki 頁 ↔ 原始來源 對應表 |
| `slides/index.html` | 教學 HTML 簡報 |

## 工具
- Gemini（討論與生成）
- NotebookLM（以原始資料逐句檢查）
- GitHub Pages（發布）

## 流程（loop / graph）
（流程圖貼在這裡，並說明：哪些步驟重複、哪裡檢查與重新生成、為什麼這樣設計。）

## 反思
- 最常出錯的節點：
- 把檢查往前移到：
- 對 workflow 的修改與原因：
