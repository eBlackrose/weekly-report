# Dev Pulse

This repository is generated and updated by [github-weekly-reporter](https://github.com/deariary/github-weekly-reporter).

Every week, GitHub Actions collects my activity (commits, PRs, reviews), an LLM writes a narrative summary, and the result is published as a report page and an animated news-ticker card for my profile.

## Live Reports

https://eblackrose.github.io/weekly-report/

## Profile Card

<a href="https://github.com/eBlackrose/weekly-report">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://eblackrose.github.io/weekly-report/card-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://eblackrose.github.io/weekly-report/card.svg" />
    <img alt="Weekly Report" src="https://eblackrose.github.io/weekly-report/card.svg" height="48" />
  </picture>
</a>

## How It Works

1. **Daily**: a scheduled workflow collects my GitHub events at midnight (America/Los_Angeles).
2. **Weekly**: every Monday the full report is generated with an AI narrative and deployed to GitHub Pages.
3. Run **Weekly Report** manually from the Actions tab at any time.

## Secrets

| Secret | Purpose |
|---|---|
| `GH_PAT` | GitHub token used to read activity and push to `gh-pages` |
| `GROQ_API_KEY` | LLM key for the AI narrative and ticker headlines |

---

Supported by [deariary](https://deariary.com)
