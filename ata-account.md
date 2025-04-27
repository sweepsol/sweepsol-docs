# ATA Account

## Understanding ATA Accounts on Solana

### What is an ATA account?

An Associated Token Account (ATA) is a special account on Solana that stores a specific token type (excluding SOL). For each different token you own (USDC, BONK, etc.), a separate ATA is automatically created.

### The hidden cost of ATAs

Each ATA is created with a small amount of SOL (about 0.002 SOL) that remains locked as long as the account exists. If you've interacted with many tokens over time, this can represent a significant sum unnecessarily immobilized.

### Why recover this SOL?

Many users end up with dozens of empty ATAs (without tokens) that are still active. These "ghost" accounts contain SOL that can be recovered when the account no longer holds any tokens.

### Important note

SweepSOL only closes token accounts with a balance of 0 tokens. If an account still holds any amount of tokens, it won't be closed. This ensures you never lose any of your assets during the process.

### Advanced feature: Token burning

For token accounts with balances greater than 0, we offer a secondary feature that allows you to burn these tokens and then close their associated ATA accounts. This is particularly useful for unwanted tokens or dust amounts that are taking up space in your wallet and locking SOL.

### SweepSOL to the rescue

Our service automatically analyzes your wallet, identifies empty ATAs, and allows you to close them with a single click to recover your SOL. This keeps your wallet organized while reclaiming funds that would otherwise be lost.
