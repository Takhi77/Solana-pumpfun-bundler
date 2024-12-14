# Solana Pumpfun Bundler using JITO & LOOKUPTABLE

## Contact
telegram: @Takhi77

You can contact me here if you have any problems with this repo then we can decide comfortable contact way.

## Sample

https://pump.fun/7JTQG7Bp6fsbnSmfT6NqRoTmoMj6aX9NZXdnsnHgJtuz
with updated version
https://solscan.io/token/4KndEPnfUbBWMqt98MASDdRL7DNLzyRG2E5epTps3Hz5
https://pump.fun/4KndEPnfUbBWMqt98MASDdRL7DNLzyRG2E5epTps3Hz5

## Overview

Jito is supporting the bundle service that you can confirm 4 transactions (This is maximum from my experience) at once.

I am doing with 24 wallets, but there is possibility to increase the number of wallets.
So, each swap instruction of Pumpfun has less accounts than Raydium, so we can use Lookuptable more effectively than Raydium.

It provides methods for creating, buying from 24 wallets, and selling tokens when you want.

This is the steps of My bundler.

## 1. Creating wallets to buy tokens from the pool you creating.

## 2. Creating Lookuptable

## 3. Extending Lookuptable and simulations of each transactions to bundle

## 4. Bundle createPool with the token of metadata transaction and 3 transactions buying from 28 wallets.

## 5. Sell tokens at once from 24 wallets using bundle when you want

## 6. Gathering Sol from 24 wallets you bundle buy and sell

# Updated Version

Previous version has serious problem.
But nobody recorgnized it but after delivery of the product, when the clients are testing with big amount of solana, it meets error (exactly SLIPPAGE error)
So, in updated version, I solved that problem.
And seperate the dev wallet and funding wallet.
And randomize the amount of distributing to bundler wallets, by doing that we can decorate the chart well.
