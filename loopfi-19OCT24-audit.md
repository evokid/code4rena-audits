
## About LoopFi
LoopFi is a DeFi lending protocol with CDP vaults and leveraged staking mechanisms. The platform's core concept revolves around leveraging ETH-based yields, utilizing receipt tokens, and staking mechanisms to align incentives between various actors in the ecosystem. The CDPVault contract manages the core logic of the borrowing and lending functionalities, allowing users to deposit collateral, borrow against it, and handle repayments.

**GitHub**: https://github.com/code-423n4/2024-07-loopfi  
**Documentation**: https://docs.loopfi.xyz  
**Website**: https://loopfi.xyz

<br/>

## Contest Period
The LoopFi audit on Code4rena took place between July 25, 2024 and August 15, 2024. The audit focused on the platform's smart contracts, including the CDPVault and PoolV3 contracts that enable the protocol's lending and borrowing functionality.

**Code4rena**: https://code4rena.com/audits/2024-07-loopfi  


<br>


## LoopFi - My Findings
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;11 | It is nearly impossble for Liquidators to use `liquidatePosition()` to fully pay off a non bad-debt position [report ->](https://code4rena.com/reports/2024-07-loopfi#h-11-it-is-nearly-impossble-for-liquidators-to-use-liquidateposition-to-fully-pay-off-a-non-bad-debt-position) | High | **LoopFi** DeFi lending protocol with CDP vaults and leveraged staking mechanisms | Solidity | Ethereum |
| H-07 | **Solo** - Malicious Borrower Cycle Exploits to Inflate Interest Rates [report ->](https://code4rena.com/reports/2024-07-loopfi#h-07-malicious-borrower-cycle-exploits-to-inflate-interest-rates) | High | **LoopFi** | Solidity | Ethereum |
| H-06 | Malicious borrower can evade full liquidation in `CDPVault::liquidatePosition` by repaying small amounts of debt [report ->](https://code4rena.com/reports/2024-07-loopfi#h-06-malicious-borrower-can-evade-full-liquidation-in-cdpvaultliquidateposition-by-repaying-small-amounts-of-debt-) | High | **LoopFi** | Solidity | Ethereum |
| M&#x2011;01 | **Solo** - Bringing a position from unsafe to safe by liquidation paritally [report ->](https://code4rena.com/reports/2024-07-loopfi#m-01-bringing-a-position-from-unsafe-to-safe-by-liquidation-partially) | Medium | **LoopFi** | Solidity | Ethereum |
| M-28 | `BalancerOracle::update()` can return stale price [report ->](https://code4rena.com/reports/2024-07-loopfi#m-28-balanceroracleupdate-can-return-a-stale-price) | Medium | **LoopFi** | Solidity | Ethereum |

