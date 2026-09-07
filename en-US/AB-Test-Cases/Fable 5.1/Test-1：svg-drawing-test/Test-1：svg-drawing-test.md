# Test-1：svg-drawing-test

> The prompt and this description were originally written in Chinese. The HTML artifacts are the original model outputs with only their visible text translated into English (title, on-screen labels, accessibility text, page description); structure, styles and scripts are untouched. Chinese originals: [zh-TW folder](../../../../zh-TW/AB測試實例/Fable%205.1/測試1：SVG繪圖測試/).

> Model: Fable 5.1 | Thinking level: High, Extra | Meta Rules: zh-TW edition (Ver 2.0.0) | Test date: 2026-09-07

# AB Test Prompt

Create an HTML page whose content is a 2D SVG animation of a pelican riding a bicycle.

# Artifacts

| Condition | Thinking level | Run time | Open | Source |
|---|---|---|---|---|
| Baseline | High | — | [Open](https://nous-think.github.io/LLM-Cognitive-Architecture-By-Prompt/en-US/AB-Test-Cases/Fable%205.1/Test-1：svg-drawing-test/Fable%205.1%20%28High%29%20Baseline.html) | [Source](./Fable%205.1%20%28High%29%20Baseline.html) |
| Meta Rules | High | — | [Open](https://nous-think.github.io/LLM-Cognitive-Architecture-By-Prompt/en-US/AB-Test-Cases/Fable%205.1/Test-1：svg-drawing-test/Fable%205.1%20%28High%29%20Meta%20Rules.html) | [Source](./Fable%205.1%20%28High%29%20Meta%20Rules.html) |
| Baseline | Extra | — | [Open](https://nous-think.github.io/LLM-Cognitive-Architecture-By-Prompt/en-US/AB-Test-Cases/Fable%205.1/Test-1：svg-drawing-test/Fable%205.1%20%28Extra%29%20Baseline.html) | [Source](./Fable%205.1%20%28Extra%29%20Baseline.html) |
| Meta Rules | Extra | — | [Open](https://nous-think.github.io/LLM-Cognitive-Architecture-By-Prompt/en-US/AB-Test-Cases/Fable%205.1/Test-1：svg-drawing-test/Fable%205.1%20%28Extra%29%20Meta%20Rules.html) | [Source](./Fable%205.1%20%28Extra%29%20Meta%20Rules.html) |

Run time: when a response uses several tools, Claude's interface shows the number of tool calls instead of the elapsed time, so no run time is available for this set.

# Notes

- This test is deliberately not audited. The merits of an SVG animation are a matter of taste; even where the two outputs differ, an audit could read as steering the verdict. Watch them and judge by your own preference.
- How to view: "Open" plays the animation directly in the browser (GitHub Pages). GitHub links always open in the same tab, so Ctrl+click (⌘+click on Mac) or middle-click to open a new tab. "Source" is the GitHub file view; you can also download the html and open it locally.
- Edit trace: after submission the html files were changed in two ways only — the `<title>` was prefixed with "model (level) condition" so browser tabs can be told apart (the original title is kept after the colon), and for this English edition the visible text was translated. The rendered animation is unchanged; every change can be checked in the commit history.
