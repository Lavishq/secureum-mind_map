
# 108 - [Remove stale comments](./Remove%20stale%20comments.md)

Remove stale comments Remove inline comments that suggest the two uint256 values `DAOfiV1Pair.reserveBase` and `DAOfiV1Pair.reserveQuote` are stored in the same storage slot. This is likely a carryover from the `UniswapV2Pair` contract, in which `reserve0`, `reserve1`, and `blockTimestampLast` are packed into a single storage slot.


1. Recommendation: Remove stale comments
2. [ConsenSys's Audit of DAOfi](https://consensys.net/diligence/audits/2021/02/daofi/#remove-stale-comments)


___
## Slide Screenshot
![108.png](../../images/8.%20Audit%20Findings%20201/108.png)
___
## Slide Text
- 
___
## References
- Youtube Reference
___
## Tags