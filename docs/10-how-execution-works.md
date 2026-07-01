---
sidebar_position: 10
title: How Execution Works
---

# How Execution Works

This page explains, in plain terms, what happens between a caller posting a token and VigiLabs opening a position — so you know what to expect.

## From signal to trade

1. **A followed caller posts a token.** VigiLabs is watching the channels you follow. When one of them posts a token, VigiLabs picks it up.
2. **VigiLabs identifies the chain.** It works out which blockchain the token is on and selects your matching wallet.
3. **It checks your rules.** VigiLabs uses your saved buy amount, slippage, and gas settings for that chain.
4. **It executes the buy.** The trade is routed through the best available DEX liquidity for that chain and submitted on-chain.
5. **It sets up your exits.** The new position is managed according to your take-profit and stop-loss rules.

All of this happens quickly — the aim is to act on a signal in a fraction of the time it would take to do it by hand.

## Managing exits

Once a position is open, VigiLabs watches its price and sells according to your take-profit levels and stop-loss. As the price passes each take-profit trigger, the configured portion is sold. If the price falls to your stop-loss level, the position is closed. You can also close a position yourself at any time.

## What VigiLabs does not do

- **It doesn't judge signals.** VigiLabs executes what your followed callers post. It does not decide whether a token is good, safe, or likely to succeed.
- **It doesn't guarantee fills.** In fast or illiquid markets, buys and exits can fill at worse prices than expected, or fail entirely.
- **It doesn't trade what you haven't enabled.** Only enabled chains with funded wallets will trade, and only signals from channels you follow are acted on.

## Duplicate protection

If you already hold an open position for a token, VigiLabs generally won't open a second position for the same token off a repeated signal. This helps avoid stacking into the same trade multiple times when several callers post the same token.

## Your controls

At any moment you can stop everything with **Stop All Trading**, adjust your settings, unfollow a caller, or close a position. VigiLabs executes your decisions — you always hold the wheel.

