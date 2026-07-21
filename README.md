# 🎬 ClipFarmer

Viral YouTube Shorts research agent for a **ranking channel** (ranking clips / Top-X / tier-list Shorts).

## What it does
On each run, ClipFarmer:
1. Searches the live web (recency-filtered, last ~7 days) for trending Shorts in the ranking niche.
2. Analyzes competitor ranking/compilation channels and their latest viral shorts.
3. Scans the week's cultural moments (sports, movies, gaming, memes) that ranking formats can ride.
4. Delivers the **Top 3 contents to edit today**, with hooks, titles, and editing notes.

## Reports
Dated reports live in [`reports/`](reports/), one per research run:

- [2026-07-21 — Ranking channel](reports/2026-07-21-clipfarmer-ranking.md)
- [2026-07-20 — Ranking channel](reports/2026-07-20-clipfarmer-ranking.md)
- [2026-07-16 — Ranking channel](reports/2026-07-16-clipfarmer-ranking.md)

## Freshness rule
Every cited trend/short must come from a source published within the last ~2 weeks (preferably 7 days). No stale content.
