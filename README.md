# AutoCure.AI: Self-Healing Data Pipeline

This repository stores AI-generated SQL scripts designed to fix data pipeline issues.

## Structure

- `fixes/`: auto-generated SQL fixes by AI agent
- `docs/`: documentation and design notes
- `scripts/`: helper scripts for automation or validation
- `tests/`: test SQL scripts for data validation

## Workflow

1. AI agent generates SQL fix and commits to `fixes/`
2. PRs created for review and merge
3. Optional tests or automation run post-merge