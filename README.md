# mento-sdk-examples

A set of runnable example code snippets for using the [Mento Protocol SDK](https://www.npmjs.com/package/@mento-protocol/mento-sdk).

## Installation and usage

```sh
# clone the repo
git clone https://github.com/mento-protocol/mento-sdk-examples.git

# cd into the directory
cd mento-sdk-examples

# install all dependencies
yarn

# run the example snippets
yarn ts-node src/discovery.ts
yarn ts-node src/quotes.ts
yarn ts-node src/swap.ts (requires private key setup)
```

## Private Key Setup
Replace the variable `"YOUR_PRIVATE_KEY_HERE"` in [src/swap.ts](https://github.com/mento-protocol/mento-sdk-examples/blob/main/src/swap.ts) with your private key for your chosen Celo network.
