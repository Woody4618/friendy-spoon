This program is deployed and verified at: 4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs

Verify command:

```bash
solana-verify verify-from-repo https://github.com/Woody4618/friendy-spoon/ --program-id 4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs
```

Notice how here we do not need a `--mount-path` because the program is directly in the root of the repository.
For an example where the program is in a subdirectory, see the https://github.com/Woody4618/crispy-waffle example.

Find the program in the Solana Explorer here:
https://explorer.solana.com/address/4EMDPYMakiVuCUpsTdw26LkVcGwHUYaJLtXTLxCHzPDs?cluster=mainnet

Find the verify docs here:
https://solana.com/developers/guides/advanced/verified-builds

And the code here:
https://github.com/Ellipsis-Labs/solana-verifiable-build
