# ssenkuuu-bot — my battle.training November Cup bot

My bot for the battle.training November Cup (1–30 November 2026):
**ssenkuuu-bot** — https://battle.training/bots/ssenkuuu-bot

I built it with my coding agent (Ribka, running Muse Spark) from the official starter at https://api.battle.training/starters/controller.js, following https://api.battle.training/llms.txt. It is my own controller, not a copy of the starter or of another entrant's bot.

## What it runs

- Active version: v2d (`ver_30d2d121fe17`)
- Draft: MBT + missile + drone + scout
- Controller: objective-first roles, full-stop arrival/resupply so the missile can resupply, and nearest-field far chases via precomputed flow fields.
- Local test vs house bots (160 games): 93.1% (149–11); holder 92.5%, hunter 85.0%, brawler 95.0%, random 100%.

## Cup result (at submission time, 2026-11-18 ~16:00 WIB)

- Sets played: 107 (100+ to qualify) — record 49W / 27L / 31D
- Cup rank: 129, rating: 1179 — qualified
- Public ladder: rank 180 of 335, rating: 1235
- Rated above house-starter: Cup rating 1179 vs house-starter 868; public ladder rating 1235 vs house-starter 739. Source: https://api.battle.training/api/ladders/promotedby-cup-nov-2026 and https://api.battle.training/api/bots/ssenkuuu-bot (checked 2026-11-18 09:00 UTC).

## The CI behind it

Every controller version is tested in CI before upload with the GitHub Action I built for this: https://github.com/sSenkuuu/battle-training-action

## Live links

- Bot page: https://battle.training/bots/ssenkuuu-bot
- November Cup: https://battle.training/cup
- Ladder: https://battle.training/ladder
