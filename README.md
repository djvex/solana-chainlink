# I think this is a remake of pappas999's tutorial (here)[https://github.com/smartcontractkit/solana-starter-kit]

# Get current Solana configuration settings with `solana config get`
```
(base) jason@Jasons-MacBook-Pro solana-chainlink % solana config get
Config File: /Users/jason/.config/solana/cli/config.yml
RPC URL: https://api.devnet.solana.com 
WebSocket URL: wss://api.devnet.solana.com/ (computed)
Keypair Path: /Users/jason/.config/solana/id.json 
Commitment: confirmed
```

# WIP: How to deploy
1. Something about generating a key pair or something like that
2. Air drop some fake SOL

```bash
solana airdrop 2 $(solana-keygen pubkey ./id.json) --url https://api.devnet.solana.com && solana airdrop 2 $(solana-keygen pubkey ./id.json) --url https://api.devnet.solana.com
```


# WIP: How to connect to Chainlink data feed
1. Some anchor command?
