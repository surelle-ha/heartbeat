# Heartbeat 🌱

This repository uses GitHub Actions to commit to itself on a schedule.

## How it works
- A scheduled GitHub Action updates `heartbeat.txt`
- The change is committed back to the repository
- This creates GitHub contributions for the repository owner

## Forking
Once you fork this repository:
1. Go to **Actions**
2. Click **Enable workflows**
3. (Optional for private repos)
   Enable **Profile → Include private contributions**

That’s it — the bot will work automatically.

## Schedule
Runs once per day (UTC).

You can modify the cron schedule in:
`.github/workflows/auto-commit.yml`
