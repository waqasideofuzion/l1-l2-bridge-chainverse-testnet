# l1-l2-bridge-chainverse-testnet

Anyone can try to token bridge between Oasys Testnet and SandVerse.

## Quick Start

Clone the repository and install dependencies.

```shell
git clone https://github.com/waqasideofuzion/l1-l2-bridge-chainverse-testnet

cd l1-l2-bridge-tutorial

npm install
```

Set the private key of the your test account in the `.env` file.
> You can get a test token from [Faucet](https://faucet.testnet.oasys.games/).

```shell
PRIVATE_KEY=0x...
```

Try `OAS` (aka ETH) bridge for bridge OAS from L1 to L2

```shell
npm run bridge
OR
npx hardhat run scripts/bridge-OAS.ts
```

Try `oFT` bridge.

```shell
npx hardhat run scripts/bridge-oFT.ts
```

Try `oNFT` bridge.

```shell
npx hardhat run scripts/bridge-oNFT.ts
```
