# Test-1：svg-drawing-test

> The prompt and this description were originally written in Chinese. The HTML artifacts are the original model outputs with only their visible text translated into English (title, on-screen labels, accessibility text, page description); structure, styles and scripts are untouched. Chinese originals: [zh-TW folder](../../../../zh-TW/AB測試實例/GPT%206/測試1：SVG繪圖測試/).

> Model: GPT 6 | Thinking level: High | Meta Rules: en-US edition (Ver 2.0.0) | Test date: 2026-09-07

# AB Test Prompt

Create an HTML page whose content is a 2D SVG animation of a pelican riding a bicycle.

# Artifacts

| Condition | Thinking level | Run time | Open | Source |
|---|---|---|---|---|
| Baseline | High | 4 min 18 s | [Open](https://nous-think.github.io/LLM-Cognitive-Architecture-By-Prompt/en-US/AB-Test-Cases/GPT%206/Test-1：svg-drawing-test/GPT%206%20%28High%29%20Baseline.html) | [Source](./GPT%206%20%28High%29%20Baseline.html) |
| Meta Rules | High | 5 min 52 s | [Open](https://nous-think.github.io/LLM-Cognitive-Architecture-By-Prompt/en-US/AB-Test-Cases/GPT%206/Test-1：svg-drawing-test/GPT%206%20%28High%29%20Meta%20Rules.html) | [Source](./GPT%206%20%28High%29%20Meta%20Rules.html) |

Run times are the thinking times shown by the GPT interface.

# Notes

- This test is deliberately not audited. The merits of an SVG animation are a matter of taste; even where the two outputs differ, an audit could read as steering the verdict. Watch them and judge by your own preference.
- How to view: "Open" plays the animation directly in the browser (GitHub Pages). GitHub links always open in the same tab, so Ctrl+click (⌘+click on Mac) or middle-click to open a new tab. "Source" is the GitHub file view; you can also download the html and open it locally.
- Max level: the two original artifacts turned out to be near-identical (388 of 407 lines shared) and cannot be treated as independent generations; they have been withdrawn and will be re-run.
- Edit trace: after submission the html files were changed in two ways only — the `<title>` was prefixed with "model (level) condition" so browser tabs can be told apart (the original title is kept after the colon), and for this English edition the visible text was translated. The rendered animation is unchanged; every change can be checked in the commit history.
