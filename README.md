# 🚀 Auto Push

![Auto Push Workflow](https://github.com/PrAtHaM-0707/Auto-Commit/actions/workflows/auto-commit.yml/badge.svg)

A lightweight and automated tool to keep your GitHub contribution graph active and green. Auto Push uses GitHub Actions to make scheduled, automated commits to your repository without requiring any manual effort.

---

## 🌟 Features

- **Fully Automated:** Runs in the background using GitHub Actions.
- **Customizable Schedule:** Change the commit frequency by modifying the cron schedule.
- **Technical Commit Messages:** Randomly selects from a curated list of professional, tech-focused commit messages.
- **Zero Maintenance:** Set it up once and forget it.

---

## 🛠️ Setup Guide

To get started with Auto Push on your own account, follow these simple steps:

1. **Host the Code:** Clone or use this repository as a template for your own GitHub account.
2. **Enable Actions:** Ensure that **GitHub Actions** are enabled in your repository settings (Settings -> Actions -> General -> Allow all actions).
3. **Done:** The bot will automatically start committing based on the defined schedule!
4. **Test it (Optional):** Go to the **Actions** tab in your repository, click on **Auto Commit**, and hit the **Run workflow** button to test it instantly!

---

## ⚙️ Configuration

You can easily change how often the bot runs by modifying the schedule interval.

Navigate to `.github/workflows/auto-commit.yml` and adjust the `cron` schedule:

```yaml
on:
  workflow_dispatch:
  schedule:
    - cron: '*/5 * * * *' # Change to every 4 hours later: "0 */4 * * *"
```

---

## 📝 Disclaimer

This tool is created for educational and fun purposes. Keep in mind that artificially inflating your GitHub contribution graph might not accurately reflect your actual coding activity. Use responsibly!
