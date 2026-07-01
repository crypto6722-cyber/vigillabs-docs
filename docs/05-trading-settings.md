---
sidebar_position: 5
title: Trading Settings
---

# Trading Settings

The **Trading** page is where you tell VigiLabs how to size and place your trades. These settings apply to every new position VigiLabs opens, until you change them.

## Buy amount

Set how much VigiLabs spends on each signal. Buy amounts are set per chain in the chain's native token:

- **Solana** — an amount in SOL per trade (for example, 0.5 SOL)
- **EVM chains** — an amount in ETH/BNB per trade (for example, 0.05)

Choose an amount you're comfortable committing to a single meme coin position. Because a bad signal can go to zero, size conservatively.

## Slippage

Slippage is the maximum price movement you'll tolerate between the moment VigiLabs sees a price and the moment the trade executes. Higher slippage means your trades are more likely to fill on fast-moving or volatile tokens, but you may get a worse price. Lower slippage protects your price, but trades may fail in fast markets.

## Gas priority

Gas priority controls how much you pay to have your transaction processed quickly. Higher priority can help your trade land faster during busy periods, at a higher cost. You can typically choose between low, medium, and high.

## Enabling and disabling chains

You can turn trading on or off for each chain independently. A chain will only trade if:

- It's enabled on the Trading page, and
- You have a funded wallet set up for it.

If a wallet is missing for a chain, VigiLabs will let you know rather than trying to trade without one.

## Stop All Trading

The **Stop All Trading** switch is your master control. When you stop all trading, VigiLabs will not buy or sell on any chain — if a followed caller posts a token, nothing executes. Use this whenever you want to change your settings safely, or simply pause the service.

When you're ready again, use **Resume All** to turn trading back on.

## Saving

After changing any settings, save them. Your saved settings apply to every new position from that point forward. Positions already open continue to follow the take-profit and stop-loss rules that were in place when they were opened.

