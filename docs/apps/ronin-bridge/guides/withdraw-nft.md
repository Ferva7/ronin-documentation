---
description: Transfer NFTs from Ronin to Ethereum using Ronin Bridge.
slug: /apps/ronin-bridge/withdraw-nft
title: Withdraw an NFT
toc_max_heading_level: 2
---

## Overview

This guide describes how to use Ronin Bridge to send an NFT (non-fungible token) from your Ronin Wallet to an address on Ethereum.

## Prerequisites

If you access Ronin Bridge through the Ronin Wallet mobile app, then you can only connect Ethereum wallets imported into your Ronin Wallet beforehand. 

To import your Ethereum wallets, see [Importing Your MetaMask Wallet to Ronin Wallet](https://support.roninchain.com/hc/en-us/articles/14862812718107-Importing-Your-MetaMask-Wallet-to-Ronin-Wallet).

## Step 1. Add the sender and recipient addresses

1. Open [Ronin Bridge](https://app.roninchain.com/bridge) and select the **NFTs** tab.
   ![nft-withdrawal-0](../assets/nft-deposit-0.png)
2. Switch to the withdrawal feature by selecting the button between the **From** and **To** fields.
   ![nft-withdrawal-1](../assets/nft-withdrawal-1.png)
3. In the **From** field, connect your Ronin Wallet using the browser extension or mobile app.
   ![nft-withdrawal-2](../assets/nft-withdrawal-2.png)
4. In the **To** field, enter the Ethereum address that you want to transfer the NFT to. Double-check the recipient address to avoid sending your NFT to the wrong destination.
   :::note[Ronin Wallet app]
   If you access Ronin Bridge through the Ronin Wallet mobile app, then you can enter any Ethereum address as a recipient, but only your imported Ethereum wallet can pay the gas fees for the transaction.
   :::
   ![nft-withdrawal-3](../assets/nft-withdrawal-3.png)

## Step 2. Select the NFT to withdraw

1. Choose the collection containing the NFTs you want to withdraw.
   ![nft-withdrawal-4](../assets/nft-withdrawal-4.png)
2. In the collection, select the specific NFT.
   ![nft-withdrawal-5](../assets/nft-withdrawal-5.png)

## Step 3. Approve the NFT

To withdraw an NFT, you need to grant Ronin Bridge permission to transfer it, which is also referred to as *approval*. You have two ways to do it: approve a single token or approve all tokens.

### Approve a single token

Approving a single token means that every time you transfer an NFT, you will need to approve each token individually. So when you transfer another token in the future, you will need to approve it again.

1. With the NFT selected, click **Approve NFT**.
   ![nft-withdrawal-6](../assets/nft-withdrawal-6.png)
2. Select **Single token**.
   ![nft-withdrawal-7](../assets/nft-withdrawal-7.png)

### Approve all tokens

Approving all tokens means that you only need to grant approval once, and your future NFT transfers will not require any approval.

1. Select the NFT you want to transfer, then click **Approve NFT**.
   ![nft-withdrawal-6](../assets/nft-withdrawal-6.png)
2. Select **All tokens**.
   ![nft-withdrawal-8](../assets/nft-withdrawal-8.png)

You can revoke token approval by using the [Token Revoke](https://ronin.axiedao.org/revoke/) tool.

## Step 4. Confirm your withdrawal

1. Review the transaction details, including the gas fees associated with the withdrawal. Make sure you have enough ETH in your Ethereum wallet to cover the fees. If everything looks correct, select **Submit withdrawal**.
   ![nft-withdrawal-9](../assets/nft-withdrawal-9.png)
2. When prompted, sign the transaction in your Ronin Wallet.
3. Select **Connect Wallet** and connect your Ethereum wallet.
   ![nft-withdrawal-10](../assets/nft-withdrawal-10.png)
4. Wait for the transaction to be confirmed by the network. Be patient, however, as transactions can take some time to complete, depending on network congestion and gas fees.
   ![nft-withdrawal-11](../assets/nft-withdrawal-11.png)
5. When the NFT is ready to be withdrawn, select **Withdraw** to transfer it to your Ethereum address.
   ![nft-withdrawal-12](../assets/nft-withdrawal-12.png)
6. When prompted, sign the transaction in your connected Ethereum wallet to receive the transfer.

## Step 5. Receive the NFT in your Ethereum wallet

When the withdrawal is complete, you'll see a "Withdrawal completed" window.
![nft-withdrawal-13](../assets/nft-withdrawal-13.png)
You can now check your connected wallet to verify that the NFT has arrived successfully.
