# insanity is live — a repository, a team, and a place to publish

**Released:** November 25, 2026

`insanity` starts as an empty repository with the scaffolding this fleet gives
every project, so the first real commit has somewhere to land.

## What exists today

- **A team.** `sane-lead` (claude opus) with `spectr` (codex gpt-6.1-sol) and
  `loco` (codex gpt-6-luna) developing, and `sane-quality` (claude sonnet) on
  the quality gate. The team is defined in `.atm.toml` and can be rebuilt from
  that file alone.
- **A site.** This page, with reports and diagrams sections ready.

## Honest state

There is no product yet. This announcement exists so that when there is one, the
history starts here rather than at a retroactively written page. No reports are
listed until a run produces one.

## How it is built

Only sources are committed; index pages are generated at deploy time by
`scripts/build-site.py`.
