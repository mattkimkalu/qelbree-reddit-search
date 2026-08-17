# qelbree-reddit-search
I want to have the both posts and comments of the posts in the csv files.
# Qelbree Reddit Search Script

Personal, read-only Python script that searches public Reddit posts and comments for the keyword **"qelbree"** over approximately the last 2 years.

## Purpose
This script is for personal research only. It helps collect public discussions about the medication Qelbree (viloxazine).

## Features
- Searches both posts and comments
- Limits results to the last ~2 years
- Automatically skips NSFW content
- Skips private/forbidden subreddits
- Respects Reddit API rate limits
- Prints a summary (counts, date range, and sample results)
- No posting, voting, messaging, or any write actions

## Requirements
- Python 3.8+
- `praw` library

```bash
pip install praw
