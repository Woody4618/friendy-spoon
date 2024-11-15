This program is deployed and verified at: 4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs

Verify command:

```bash
solana-verify verify-from-repo https://github.com/solana-developers/verified-program-root/ --program-id 4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs
```

Notice how here we do not need a `--mount-path` because the program is directly in the root of the repository.
For an example where the program is in a subdirectory, see the https://github.com/solana-developers/verified-program example.
For an example of an anchor program see: https://github.com/solana-developers/solana-game-preset

Find the program in the Solana Explorer here:
https://explorer.solana.com/address/4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs?cluster=mainnet
https://solscan.io/account/4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs#programVerification
https://solana.fm/address/4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs?cluster=mainnet-alpha

Find the verify docs here:
https://solana.com/developers/guides/advanced/verified-builds

And the code here:
https://github.com/Ellipsis-Labs/solana-verifiable-build
