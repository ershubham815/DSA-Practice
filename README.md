# DSA Practice Repository

This repository is configured to keep a daily contribution streak for **6 months**.

## What is automated

- A GitHub Actions workflow runs every day at **00:15 UTC**.
- It appends one row to `progress/daily-log.md` for the current day.
- It auto-commits and pushes that change.
- It stops after **2026-10-19**.

## Recommended daily routine

1. Solve one or more DSA problems.
2. Replace the auto-generated `TBD` values in `progress/daily-log.md` with:
   - Topic (e.g., Arrays, Binary Search, Trees)
   - Problems solved
   - Short notes or learnings
3. Commit and push your real update for the day.

## Trigger manually

You can run the workflow manually from **Actions → Daily DSA Commit → Run workflow**.
