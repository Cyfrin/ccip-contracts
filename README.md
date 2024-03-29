# ccip-contracts

A minimal repo that is a copy of the npm package [@chainlink/contracts-ccip](https://www.npmjs.com/package/@chainlink/contracts-ccip/v/1.2.1).

Everyday at 3AM, the latest version of the package is updated here, this way, you can use the Chainlink CCIP contracts with foundry without having to use npm/yarn. This also makes other third party packages like Brownie and Ape easier to work with. 

## Usage

### Foundry

1. Run this in your projects root directory.

```bash
forge install cyfrin/ccip-contracts@1.4.0 --no-commit
```

2. Then, update your `foundry.toml` to include the following in the `remappings`.

```
remappings = [
  '@chainlink/contracts-ccip/=lib/ccip-contracts/contracts-ccip/',
]
```

