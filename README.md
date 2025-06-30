# 🧠 Quote Rotation Bot

This repository is powered by a GitHub Action that updates the README every 4 days with either a **motivational** or **technical quote**.

one commit at a time!

---

<!-- START_QUOTES -->


<!-- END_QUOTES -->

---

## 📅 How It Works

- Every 4 days (via cron), this repo pulls a quote using:
  - [ZenQuotes API](https://zenquotes.io) for motivational quotes
  - [Programming Quotes API](https://programming-quotes-api.vercel.app) for tech quotes
- The quote alternates between categories (motivational ↔ tech)
- The latest quote is updated in this README automatically

## ⚙️ Automation Details

Powered by:
- GitHub Actions
- `curl` + `jq`
- Public quote APIs

## 💡 Want to Use This?

Fork this repo, and it’ll work out of the box. Just make sure you:
- Create `quote_type.txt` with `motivational` inside it.
- Keep the comment tags `<!-- START_QUOTES -->` and `<!-- END_QUOTES -->` unchanged in your README.

---


📜 **Quote of the Day**:

> _Enthusiasm makes up for a host of deficiencies. — Barack Obama_
