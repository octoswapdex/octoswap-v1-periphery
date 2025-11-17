# OctoSwap Classic-V1 Periphery Contracts (Remix Env)

## Contract Details
- **Contract Name**: `OctoswapRouter`
- **Solidity Version**: `^0.6.6`
- **Compiler Settings**:
  - **Optimization**: `Enabled` (Runs: `999999`)
  - **EVM Version**: `Istanbul`

- **Deployed Address (Monad Mainnet)**: `0x60fd5Aa15Debd5ffdEfB5129FD9FD8A34d80d608`
- 
# OctoSwap Classic-V1 Periphery Changes (Uniswap V2 Periphery)

Comparison between `octoswap-v1-periphery` and original `uniswap/v2-periphery`.

## Contract Changes

### OctoswapRouter.sol (UniswapV2Router02.sol)
- **Line 12**: Contract name `UniswapV2Router02` → `OctoswapRouter`

### libraries/UniswapV2Library.sol
- **Line 24**: Init code hash `0x96e8ac4277198ff8b6f785478aa9a39f403cb768dd02cbee326c3e7da348845f` → `0x1305842295bb388975eec146e164811bee4ac15606baa6205d5749e933f26762`

## Unchanged Components

- **Base contracts**: All base contracts identical (100% match)
- **Interfaces**: All interface files identical (100% match)
- **Libraries**: All library files except UniswapV2Library.sol identical (100% match)

## Dependencies

All dependencies byte-for-byte identical to Uniswap V2 Periphery:
- `@uniswap/lib`: 4.0.1-alpha
- `@uniswap/v2-core`: 1.0.0

---

## Summary

All changes are purely branding-related (contract name only). All functional code, including routing logic, liquidity management, swap calculations, library functions, Solidity versions, and compiler optimization settings remain 100% identical to the original Uniswap V2 Periphery contracts. The init code hash change reflects the renamed core pair contract.

