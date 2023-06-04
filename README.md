# Deploying Uniswap's Universal Router for NFT and ERC20 swapping on PolygonZkevm

Please read the [Contributions](https://github.com/Uniswap/universal-router#contributions) section before submitting a Pull Request.

To see the commit of the smart contracts that was used in the latest deployment, see branch `deployed-commit`. To see the addresses of this latest deployment on each network, see folder `deploy-addresses`.

## High-Level Overview

The Universal Router is a ERC20 and NFT swap router that allows users greater flexibility when performing trades across multiple token types.

Our flexible command style allows us to provide users with:

- Splitting and interleaving of Uniswap trades
- Purchases of NFTs across 8 marketplaces
- Partial fills of trades
- Wrapping and Unwrapping of ETH
- Time-bound, signature controlled token approvals using [Permit2](https://github.com/Uniswap/permit2)
