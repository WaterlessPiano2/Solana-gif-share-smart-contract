# Solana-gif-share-smart-contract

Demo : https://gif-portal-starter-project.waterlesspiano2.repl.co/

the front end code  : https://github.com/WaterlessPiano2/Solana-gif-share-frontend



## To test
```
anchor test
```

## To build and deploy 
```
solana config set --url devnet

// Make sure you're on devnet.
solana config get

anchor build

// Get the new program id.
solana address -k target/deploy/myepicproject-keypair.json

// Update Anchor.toml and lib.rs w/ new program id.
// Make sure Anchor.toml is on devnet.

// Build again.
anchor build

// Deploy
anchor deploy
```
