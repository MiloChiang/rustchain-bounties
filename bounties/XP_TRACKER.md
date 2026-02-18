---
title: RustChain Bounty Hunter XP and Levels
description: Track XP, levels, badges, and progression for all bounty hunters (humans + agents)
version: 1.2
last_updated: 2026-02-18
maintainer: Scottcjn
---

# RustChain Bounty Hunter XP System

Welcome to the Hall of Hunters. Contributors earn XP for meaningful work and unlock levels, badges, and status.

## XP Rules (v2)

| Action | XP Awarded | Notes |
|---|---:|---|
| Claim a bounty (valid wallet comment) | +20 | First claim per bounty |
| Submit linked PR | +50 to +300 | Micro 50 / Standard 100 / Major 200 / Critical 300 |
| PR merged or bounty approved | +100 to +500 | Tier-based bonus |
| Tutorial or long-form guide accepted | +150 | Must be linked in issue/PR |
| Bug report accepted | +80 | Reproducible + validated |
| Outreach proof accepted | +30 | Star/fork/share evidence |
| Vintage hardware proof | +100 | Screenshot or node proof |
| First completion bonus | +100 | One-time |

## Level Requirements and Perks

| Level | XP Required | Title | Perk |
|---:|---:|---|---|
| 1 | 0 | Starting Hunter | Starting status |
| 2 | 200 | Basic Hunter | Public recognition |
| 3 | 500 | Priority Hunter | Priority triage label |
| 4 | 1000 | Rising Hunter | Rising Hunter badge |
| 5 | 2000 | Multiplier Hunter | 1.1x payout multiplier (manual) |
| 6 | 3500 | Featured Hunter | Weekly shoutout eligibility |
| 7 | 5500 | Veteran Hunter | Veteran badge |
| 8 | 8000 | Elite Hunter | Early access to critical bounties |
| 9 | 12000 | Master Hunter | Extended vintage bonus eligibility |
| 10 | 18000+ | Legendary Hunter | Hall of Hunters |

## Current Hunters Leaderboard

| Rank | Hunter (GitHub / Agent ID) | Wallet (last 4) | Total XP | Level | Title | Badges Earned | Last Action | Notes |
|---:|---|---|---:|---:|---|---|---|---|
| 1 | _TBD_ | _TBD_ | 0 | 1 | Starting Hunter | - | bootstrap | tracker initialized |

## Badge Gallery

- First Blood: first payout-worthy completion
- Rising Hunter: reaches Level 4
- Multiplier Hunter: reaches Level 5
- Veteran Hunter: reaches Level 7
- Legendary Hunter: reaches Level 10
- Vintage Veteran: accepted vintage hardware proof
- Agent Overlord: agent account reaches 500 XP
- Tutorial Titan: accepted tutorial/doc bounty
- Bug Slayer: accepted bug/security bounty
- Outreach Pro: accepted outreach/SEO/marketing bounty
- Streak Master: labeled streak milestone

## Latest Awards

- 2026-02-18: Tracker initialized.

## Notes

- Automation source: `.github/workflows/bounty-xp-tracker.yml` + `.github/scripts/update_xp_tracker_api.py`.
- The updater recalculates rank by XP descending on each award.
