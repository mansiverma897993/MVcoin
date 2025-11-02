# 🪙 Token Mint — MVcoin

## Overview
This folder documents minting of my SPL token on Solana Devnet.

## Token Details
- Token Name: MVcoin
- Mint Address: 676jN7TSaeHQBdmyDMy5Hh6y316wmEKd9ASx4g31fAR6
- Total Minted: 10000
- Mint Tx Hash:  4LFE8wVXdXjJuXiTPmgDDPiN9WhRD8sey2y8RrKUk71NpKRPTCaf1qnXgnQqXBzC2boENSLBpTnWr3sfwFmdUvAC

## Commands Used
```bash
solana config set --url https://api.devnet.solana.com
spl-token create-token
spl-token create-account  676jN7TSaeHQBdmyDMy5Hh6y316wmEKd9ASx4g31fAR6
spl-token mint 676jN7TSaeHQBdmyDMy5Hh6y316wmEKd9ASx4g31fAR6 10000 BYgPEYSbM8TEvqq5fhsCPM4XgHyULaqJ1EvJszVMPYpx
spl-token accounts

