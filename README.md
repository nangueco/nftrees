# Nangu NFTrees

## Setup

1. Setup Solana toolchain
2. Clone Metaplex https://github.com/metaplex-foundation/metaplex/
3. Setup dev wallet and fund the wallet

## Create new Candy Machine

ts-node PATH_TO_METAPLEX_REPO/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts upload -e devnet -k ~/.config/solana/devnet.json -cp config.json -c example ./assets

## Mint one NFT

ts-node PATH_TO_METAPLEX_REPO/metaplex/js/packages/cli/src/candy-machine-v2-cli.ts mint_one_token -e devnet -k ~/.config/solana/devnet.json -cp config.json -c example
