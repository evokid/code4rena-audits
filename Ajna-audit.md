
## About Ajna Protocol

Ajna Protocol is a noncustodial, peer-to-pool, permissionless lending and borrowing system that operates without governance or external price feeds. The protocol enables users to create lending markets for both ERC20 and ERC721 tokens, offering a truly decentralized system for borrowing against almost any asset without requiring permission or oracles.

**GitHub**: https://github.com/ajna-finance  
**Website**: https://www.ajna.finance

## Contest Period

The Ajna Protocol audit on Code4rena took place from May 3-11, 2023, with a total award pool of $60,500 USDC. The audit focused on the protocol's core lending functionality and its innovative grant coordination fund, identifying several high and medium severity issues related to liquidity management and reward distribution.

**Code4rena**: https://code4rena.com/contests/2023-05-ajna-protocol

<br>


## Ajna Protocol - My Findings:
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;08 | Claiming accumulated rewards while the contract is underfunded can lead to a loss of rewards [report ->](https://code4rena.com/reports/2023-05-ajna#h-08-claiming-accumulated-rewards-while-the-contract-is-underfunded-can-lead-to-a-loss-of-rewards) | High | **Ajna Protocol** - DeFi lending protocol with reward distribution mechanism | Solidity | Ethereum |
