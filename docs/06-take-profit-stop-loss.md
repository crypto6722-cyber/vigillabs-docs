---
sidebar_position: 6
title: Take Profit & Stop Loss
---

# Take Profit & Stop Loss

VigiLabs can close positions for you automatically using take-profit (TP) and stop-loss (SL) rules. This means you don't have to watch every position — the service sells at your targets or cuts losses at your limit.

## Take-profit levels

A take-profit level tells VigiLabs to sell part of a position when it reaches a certain gain. You can set multiple levels, each with:

- A **trigger** — the gain at which the level fires (for example, +50%, +100%, +200%).
- A **split** — how much of the position to sell at that level.

Your splits across all levels must total 100%. VigiLabs sells the specified portion at each level as the price passes it, letting you take profit in stages while leaving some of the position to run.

For example, a common setup sells in four stages: a portion at +50%, another at +100%, another at +200%, and the remainder at a higher target. You're free to add as many levels as you want and set the triggers and splits however you like.

If you turn auto take-profit off, VigiLabs holds the position until you sell it manually.

## Stop-loss

A stop-loss tells VigiLabs to sell the entire position if the price falls to a set level below your entry — for example, sell everything if the token drops 30% below entry. This is your main automated protection against a position going against you.

If you turn stop-loss off, VigiLabs will not automatically cut a losing position; it will hold until you sell manually.

## Quick presets

If you'd rather not configure everything by hand, VigiLabs offers presets that fill in a full set of levels in one click. Typical presets include:

- **Conservative** — a few levels with earlier exits
- **Balanced** — a standard spread of levels
- **Aggressive** — levels aimed at larger targets
- **Moonbag** — more levels designed to hold a portion for big runners

You can start from a preset and then adjust individual levels to taste.

## Manual control always works

You can always close a position yourself, regardless of your TP/SL settings. Selling and closing are never blocked.

## An honest note on automatic exits

:::warning Exits are not guaranteed
Automatic exits depend on liquidity and market conditions at the moment they fire. In fast-moving or thinly-traded tokens, a take-profit or stop-loss can fill at a worse price than your target, or fail to fill at all. A stop-loss is not a guarantee against loss — it's a tool that works best in reasonably liquid markets. Size your positions with this in mind.
:::

