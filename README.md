# 🪙 Token Mint — MVcoin

## Overview
This repository contains the script used to mint a custom SPL token on the Solana Devnet using Solana CLI.

## Token Details
- Token Name: MVcoin
- Mint Address: 676jN7TSaeHQBdmyDMy5Hh6y316wmEKd9ASx4g31fAR6
- Total Minted: 10000
- Mint Tx Hash:  4LFE8wVXdXjJuXiTPmgDDPiN9WhRD8sey2y8RrKUk71NpKRPTCaf1qnXgnQqXBzC2boENSLBpTnWr3sfwFmdUvAC
  
✅ Screenshot of terminal output showing successful minting

![WhatsApp Image 2025-11-01 at 22 56 23_067d3f4b](https://github.com/user-attachments/assets/d6b04d79-d763-429e-8cdb-3109caa70663)

You can verify the mint on Solscan using this link 👇<br>
[https://solscan.io/token/Fa3JUK2dokFJZgjDyXa5dSpRhrBb8veoNnpbw9zvqgzr?cluster=devnet](https://explorer.solana.com/address/676jN7TSaeHQBdmyDMy5Hh6y316wmEKd9ASx4g31fAR6?cluster=devnet)

## Commands Used
```bash
solana config set --url https://api.devnet.solana.com
spl-token create-token
spl-token create-account  676jN7TSaeHQBdmyDMy5Hh6y316wmEKd9ASx4g31fAR6
spl-token mint 676jN7TSaeHQBdmyDMy5Hh6y316wmEKd9ASx4g31fAR6 10000 BYgPEYSbM8TEvqq5fhsCPM4XgHyULaqJ1EvJszVMPYpx
spl-token accounts

