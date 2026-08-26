# pioneerm-automation

TIA Portal **Openness** 自動化：專案建立、編譯、匯出、產線機台工程。

> 對外公開視圖僅此頁。完整 repo 請以 **member** 進入：[pioneerm-automation](https://github.com/pioneerm-automation?view_as=member)

## 從這裡開始

| 角色 | 讀什麼 |
|------|--------|
| 人類入門 | [`openness-standard`](https://github.com/pioneerm-automation/openness-standard) → `README.md`、`doc/ADD_PROJECT.md` |
| Agent 入口 | `openness-standard/AGENTS.md` |
| 必守規範 | `openness-standard/rules/README.md` |

## 鎖定版本

- **TIA Portal V21**
- Openness PublicAPI 以各機安裝路徑為準，見 `openness-standard/reference/tia_v21.md`

## 多 repo 分工

| repo | 用途 |
|------|------|
| [`.github`](https://github.com/pioneerm-automation/.github) | org profile（本頁） |
| [`openness-standard`](https://github.com/pioneerm-automation/openness-standard) | 規範、範本、onboarding、Cursor rules 範本 |
| `<machine-or-line>` | 單一機台／產線的 TIA 專案 + Openness host（之後「加入專案」） |

對齊 [`pioneerm-edge`](https://github.com/pioneerm-edge) 的排版：**中央法典一個 repo，產品各一個 repo**。本 org **不做 MCU**。
