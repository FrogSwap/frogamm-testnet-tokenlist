---
description: 'Build on FrogSwap and need help? let us know.'
---

## ✨ Building on FrogSwap and KekChain 🐸

## **FrogSwap Contracts:**

**Frog Token Address**: `0x4f05F2927080A47a88c5cBb958A7A492F09b1340`

**Router Address**: `0x36d4Fec597d673a37f26a7346EF3793cfAb95D9f`

**Factory Address**: `0xb12B84d457e31267D1f68F6EaaB9dE1861a09A5A`

**wKEK Address**: `0xA888a7A2dc73efdb5705106a216f068e939A2693`

## How to get your token LOGO on FrogSwap:

### 1. Image for the Token Logo <a id="1-image-for-the-token-logo"></a>

> * **File Extension**: `png` . Uppercase `PNG` is considered invalid
> * **File Name**：`logo.png`
> * **Size**: `256px by 256px`
> * **Background**: Transparent is a must

### 2. Token Information File <a id="2-token-information-file"></a>

> * Fork the repository and add the token information (example below) to testnet.tokenlist.json
> * Create a folder under assets/{blockchainName}/{tokenAddress}
> * Add the token icon (logo.png) under the folder created in the previous step
> * Add the token information in the testnet.tokenlist.json file, in the format shown below

The sample below shows what information has to be included on the `testnet.tokenlist.json` file.  
Please make sure that the details are accurate and follows the formatting.  
The contract address should follow the checksum address format \(see next requirement\).

```
{
      "name": "FrogSwap Token",
      "symbol": "FROG",
      "address": "0x4f05F2927080A47a88c5cBb958A7A492F09b1340",
      "chainId": 420666,
      "decimals": 18,
      "logoURI": "https://raw.githubusercontent.com/FrogSwap/frogamm-testnet-tokenlist/main/assets/kekchain/0x4f05F2927080A47a88c5cBb958A7A492F09b1340/logo.png"
},

```
