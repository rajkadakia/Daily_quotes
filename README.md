# 🔁 Auto-Updating Quotes Repository

This repository automatically updates its `README.md` file every 4 days with 3 new quotes — either motivational or technology-related — using a GitHub Actions workflow.

## 🚀 How It Works

- Every 4 days, a GitHub Actions workflow is triggered.
- A quote category (`motivational` or `tech`) is randomly selected.
- 3 quotes are fetched from online APIs:
  - **Motivational**: [ZenQuotes.io](https://zenquotes.io)
  - **Tech/General**: [Quotable API](https://api.quotable.io)
> __

> __

- Each quote is inserted into this file just above the marker `<!--QUOTE_END-->`.
- Each quote insertion is committed separately to simulate 3 contributions.

## 🔧 Workflow Details

- **Schedule**: Runs every 4 days using cron.
- **Commits**: Makes 3 separate commits per run (if changes are made).
- **Languages Used**: Shell, YAML
- **APIs**:
  - `https://zenquotes.io/api/random`
  - `https://api.quotable.io/random?tags=technology,famous-quotes`

## 📄 Auto-Inserted Quotes

Quotes are added below this section every 4 days:

<!--QUOTE_START-->
> __

> __

<!--QUOTE_END-->

---

> 💡 _This setup is useful for keeping your GitHub profile active with meaningful updates — not spammy commits._
