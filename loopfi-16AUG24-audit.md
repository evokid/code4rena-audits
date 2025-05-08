
## About LoopFi
LoopFi is a money market utilizing smart collateral with automated leverage to maximize capital efficiency and returns of Restaking products. The platform's core concept revolves around leveraging ETH-based yields, utilizing receipt tokens, and staking mechanisms to align incentives between various actors in the ecosystem. The CDPVault contract manages the core logic of the borrowing and lending functionalities, allowing users to deposit collateral, borrow against it, and handle repayments.

[GitHub](https://github.com/code-423n4/2024-07-loopfi)
[Documentation](https://docs.loopfi.xyz/)
[Website](https://www.loopfi.xyz/)

## Contest Period
The LoopFi audit on Code4rena took place between July 25 and August 15, 2024. The audit focused on the platform's smart contracts, including the CDPVault and PoolV3 contracts that enable the protocol's lending and borrowing functionality.

[Code4rena Audit Page](https://code4rena.com/audits/2024-07-loopfi)



## LoopFi - My findings 
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;05 | Rewards might be lost due to the error that _updateRewardIndex() might advance lastBalance without advancing index for a token [report ->](https://code4rena.com/reports/2024-10-loopfi#h-01-rewards-might-be-lost-due-to-the-error-that-_updaterewardindex-might-advance-lastbalance-without-advancing-index-for-a-token) | High | **LoopFi** - DeFi lending protocol with CDP vaults and leveraged staking mechanisms | Solidity | Ethereum |
