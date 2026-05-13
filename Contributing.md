# Contributing / 貢獻指南

Thank you for your interest! Here's how to contribute.
感謝你的關注！以下是貢獻方式。

## Ways to Contribute / 貢獻方式

1. **Report issues** — Found an error, inconsistency, or have a suggestion? [Open an issue](../../issues/new).
2. **Submit test results** — Ran the prompts on a different model? Share your findings.
3. **Translation & adaptation** — Help improve or adapt content across languages.

## Guidelines / 規範

### For Content Changes

- Each language version is an **adaptation**, not a strict translation. If you modify one version, note in your commit message whether the counterpart needs updating.

### For Test Reports

Please include the following metadata at the top of your test report:

```yaml
---
prompt_version: {e.g., meta-rules-v2.1}
prompt_lang: {en / zh-TW}
model: {e.g., claude-sonnet-4-20250514}
test_date: {YYYY-MM-DD}
---
```

### Commit Messages

Use clear, descriptive commit messages:
- `Update zh-TW meta-rules: restructure recursion section`
- `Add test report: meta-rules-v2 on GPT-4o (en)`
- `Fix typo in en/guides/prompt-design.md`

## Questions?

Open an issue or start a discussion. We welcome questions in both English and 中文.
