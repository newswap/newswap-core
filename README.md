# Uniswap V2
To see contracts diffs:
```
$ git diff 4dd59067c76dea4a0e8e4bfdda41877a6b16dedc 2782659d84366544c245998d3fcc991dfa5179ad 
```
- UniswapV2Pair init code hash - `3e150cc7a7a4cb1c7b61edd8b86f1bcab502aca9cab4d0f1d1e98793923a5cf6`

[![Actions Status](https://github.com/Uniswap/uniswap-v2-core/workflows/CI/badge.svg)](https://github.com/Uniswap/uniswap-v2-core/actions)
[![Version](https://img.shields.io/npm/v/@uniswap/v2-core)](https://www.npmjs.com/package/@uniswap/v2-core)

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

# Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`
