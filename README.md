# Create 2 Deployer

## Deployed Locations

Rinkeby: [0x4275F0C060Ebe50272f1e483d0E144F83c31d910](https://rinkeby.etherscan.io/address/0x45A1A1a7d02436e0D83a15E177a551F4e8B3a33c)
Goerli: [0x4275F0C060Ebe50272f1e483d0E144F83c31d910](https://goerli.etherscan.io/address/0x45A1A1a7d02436e0D83a15E177a551F4e8B3a33c)

## Installation

```bash
yarn add -D create2-deployer
```

## Usage

```ts
import {Deployer} from 'create2-deployer';

const signer = await ethers.getSigner(address);
const deployer = new Deployer(signer);
```
