# 🃏 BALONEY — Card Game

A Balatro-inspired poker card game playable in any browser. No install, no server, just open and play.

## How to Play

1. Open `index.html` in your browser
2. Select up to **5 cards** from your hand
3. Click **Play Hand** to score points
4. Beat the target score before your hands run out
5. Win rounds to unlock permanent power-ups

## Scoring

**Score = (base chips + card values) × multiplier**

| Hand | Chips | Mult |
|---|---|---|
| Royal Flush | 100 | ×8 |
| Straight Flush | 100 | ×8 |
| Four of a Kind | 60 | ×7 |
| Full House | 40 | ×4 |
| Flush | 35 | ×4 |
| Straight | 30 | ×4 |
| Three of a Kind | 30 | ×3 |
| Two Pair | 20 | ×2 |
| Pair | 10 | ×2 |
| High Card | 5 | ×1 |

> Flush and Straight require exactly 5 cards selected.

## Power-Ups (picked after each round win)

- 🃏 **Jokers** — Permanent passive bonuses (e.g. +4 Mult always, Flushes ×2 Mult)
- 🪐 **Planets** — Permanently upgrade a specific hand type (+15 chips, +1 mult per level, stackable)
- 🏷️ **Vouchers** — Change the rules (extra hand, extra discard, face cards worth more, etc.)

## Features

- 10 defined rounds + endless mode (The Abyss) that keeps getting harder
- 14 unique Jokers
- 10 Planet upgrades (one per hand type)
- 7 Vouchers
- Face cards (J, Q, K) with illustrated portraits
- Green felt card table UI
- Animated card dealing, selection, and scoring

## Files

```
index.html   — the entire game (open this)
README.md    — this file
```
