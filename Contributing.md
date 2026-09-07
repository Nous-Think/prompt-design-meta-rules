# Contributing / 貢獻指南

Thank you for your interest! Here's how to contribute.
感謝你的關注！以下是貢獻方式。

## Ways to Contribute / 貢獻方式

1. **Report issues** — Found an error, inconsistency, or have a suggestion? [Open an issue](../../issues/new).
2. **Submit test results** — Ran the prompts on a different model? Share your findings (see *Test Reports* below).
3. **Translation & adaptation** — Help improve or adapt content across languages.

1. **回報問題**——發現錯誤、不一致或有建議？[開一個 issue](../../issues/new)。
2. **提交測試結果**——在其他模型上跑過提示詞？分享你的發現（見下方「測試報告」）。
3. **翻譯與適配**——協助改善或適配各語言版本。

## Repository Layout / 目錄結構

| Path | Content |
|---|---|
| `zh-TW/` | Source language. Meta Rules, the two memoranda and all AB test cases are authored here first. |
| `en-US/` | English adaptation of everything under `zh-TW/`. |
| `zh-TW/AB測試實例/<model>/` · `en-US/AB-Test-Cases/<Model>/` | AB test cases grouped by model (e.g. `Opus 5`, `Fable 5.1`, `GPT 6`). |

zh-TW 為源語言，en-US 為適配版（adaptation），不是逐字翻譯。

## Guidelines / 規範

### Content Changes / 內容變更

- Each language version is an **adaptation**, not a strict translation. If you modify one version, state in the PR or commit message whether the counterpart needs updating.
- Meta Rules carry a version tag (`[Ver x.y.z]`) near the top of both language files; keep the two in step.

- 修改任一語言版本時，請在 PR 或 commit 訊息中註明對應語言版本是否需同步。
- 元規則檔首的版本標記（`[Ver x.y.z]`）須兩語言一致。

### Test Reports / 測試報告

Follow the structure of an existing case in the same model folder. A text-based case is one Markdown file:

```
# 測試N：<title>                        ← one H1 title = the filename without .md
> 模型：<model>｜思考等級：<level>｜元規則：中文版（Ver x.y.z）｜測試日期：YYYY-MM-DD｜執行時間：<mm:ss>
# AB測試題                              ← the prompt exactly as given to the model
# 裸跑回應（<model>）                    ← baseline response, verbatim, folded:
<details><summary>展開回應原文</summary>

…response…

</details>
# 元規則回應（<model>）                  ← Meta Rules response, same folding
# 本次AB測試品質審計      ← audit (optional — some tests are deliberately left un-audited)
```

- Metadata line (second line of the file): model, thinking level, which Meta Rules edition was loaded (zh-TW or en-US) and its `[Ver x.y.z]`, test date, run time, and optionally a short reasoning summary. Omit any field you do not actually know rather than guessing.
- Responses are **evidence**: paste them verbatim, mistakes included. Commentary belongs only in the audit or note sections.
- English cases open with a note stating that the material was originally produced in Chinese (see any file under `en-US/AB-Test-Cases/`).
- Cases whose output is an artifact (e.g. HTML/SVG) use a folder: one description `.md` plus one file per `<model>（<level>）<condition>.html`.

測試報告請對齊同一模型資料夾內既有檔案的結構。第二行為中繼資料：模型、思考等級、載入的元規則語言版本與 `[Ver x.y.z]`、測試日期、執行時間、可選的思考摘要，不知道的欄位省略而非推估。回應原文是**證據**：原樣貼上，錯誤也保留；評論只放在審計或註記段。產物型測試（如 HTML／SVG）以資料夾呈現：一份說明 md，加上每個「模型（等級）條件」一個檔案。

### Encoding / 編碼

All files are UTF-8 **without** BOM. The repository ships an `.editorconfig` so most editors apply this automatically, and a `.gitattributes` that normalizes line endings. If Chinese text renders as garbage on GitHub, the file was saved in a legacy code page (Big5/ANSI) — re-save it as UTF-8.

所有檔案為 UTF-8（無 BOM）。repo 內附 `.editorconfig` 與 `.gitattributes`；若中文在 GitHub 上顯示為亂碼，代表檔案被以 Big5／ANSI 儲存，請重新以 UTF-8 儲存。

### Commit Messages / Commit 訊息

One intent per commit, stated plainly:

- `Add AB test: Fable 5.1 SVG drawing (zh-TW)`
- `Translate Opus 5 Test-4 to en-US`
- `Rename SVG test artifacts to <model>（<level>）<condition>`
- `Fix encoding: convert SVG test description to UTF-8`

一個 commit 一個意圖，訊息直述做了什麼。

## Questions? / 有問題？

Open an issue or start a discussion. We welcome questions in both English and 中文.
