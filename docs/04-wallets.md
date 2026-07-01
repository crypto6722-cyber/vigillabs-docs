---
sidebar_position: 4
title: Wallets
---

# Wallets

VigiLabs trades from wallets tied to your account. This page covers the supported chains, how to create or import a wallet, how to view your keys, and how to withdraw.

## Supported chains

VigiLabs supports wallets on:

- **Solana** — SOL and SPL tokens
- **Ethereum, Base, and BNB Chain** — EVM tokens (these three share one EVM wallet)
- **TON** — TON and Jettons
- **HyperEVM** — HYPE and HyperEVM tokens

You only need to set up wallets for the chains you actually want to trade.

## Generate or import

For each chain, you have two options:

- **Generate a new wallet.** VigiLabs creates a fresh wallet for you inside the app. Its recovery key is encrypted and stored so the service can execute trades on your behalf (see [Security & Custody](./security-and-custody)).
- **Import your own.** Bring an existing wallet by importing its key — for example from Phantom, MetaMask, Jupiter, or Uniswap.

Either way, VigiLabs needs to be able to sign transactions automatically — that's what makes hands-off execution possible.

## Backing up your recovery key

:::danger This is the most important step
When you generate a wallet, VigiLabs will require you to back up its recovery key **before** it reveals your deposit address. Store this key somewhere safe and private. Anyone with your recovery key can control your funds, and if you lose it and lose access to your account, your funds cannot be recovered.
:::

You can view your private key at any time from the Wallets page. When you request it, VigiLabs shows it for a short window and then hides it again for safety.

## Funding your wallet

Once a wallet is set up and backed up, VigiLabs shows you its deposit address. Send crypto to that address on the correct chain to fund your trading. Double-check you're sending on the right network — sending assets on the wrong chain can result in permanent loss.

## Withdrawing

You can withdraw your funds at any time from the Wallets page. Access to view and withdraw your balances is never blocked — even if your subscription lapses, you can always get your funds out. Only automated trading and group management depend on an active subscription.

## Pausing

If you want to stop trading without withdrawing, use the **Stop All Trading** switch on the Trading page. Your funds stay where they are; VigiLabs simply stops buying and selling until you resume.

