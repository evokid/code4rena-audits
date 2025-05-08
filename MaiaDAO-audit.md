## About Maia DAO Ecosystem

Maia DAO Ecosystem is a cross-chain DeFi protocol focused on efficient liquidity renting and management across multiple blockchains. The V2 ecosystem consists of four main protocols: Hermes, Maia, Talos, and Ulysses, designed to significantly increase capital efficiency through virtualized liquidity where assets from different chains are recognized as distinct tokens.

**GitHub**: https://github.com/Maia-DAO/maia-ecosystem-monorepo/tree/main  
**Website**: https://www.maiadao.io
<br/><br/>

## Contest Period

The Maia DAO Ecosystem audit on Code4rena took place from May 30, 2023 to July 5, 2023, with a total award pool of $300,500 USDC. The audit identified 79 unique vulnerabilities (35 HIGH and 44 MEDIUM severity), with particular focus on issues related to cross-chain bridging functions like retrySettlement and retrieveDeposit.

**Code4rena**: https://code4rena.com/audits/2023-05-maia-dao-ecosystem  
**Audit Report**: https://code4rena.com/reports/2023-05-maia
<br/><br/>


## Maia DAO Ecosystem <span style="font-size: 14px;"> - 6 July 2023</span> 
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;05 | Multiple issues with `retrySettlement()` and `retrieveDeposit()` will cause loss of users' bridging deposits [report ->](https://code4rena.com/reports/2023-05-maia#h-05-multiple-issues-with-decimal-scaling-will-cause-incorrect-accounting-of-htokens-and-underlying-tokens) | High | **Maia DAO Ecosystem** - Cross-chain DeFi protocol with bridging and settlement functions | Solidity | Multi-chain |
| H-14 | User underpay for the remote call execution gas on root chain [report ->](https://code4rena.com/reports/2023-05-maia#h-14-user-may-underpay-for-the-remote-call-executiongas-on-the-root-chain) | High | **Maia DAO Ecosystem** | Solidity | Multi-chain |
| M&#x2011;10 | The user is enforced to overpay for the fallback gas when `retryDeposit` [report ->](https://code4rena.com/reports/2023-05-maia#m-10-the-user-is-enforced-to-overpay-for-the-fallback-gas-when-calling-retrydeposit) | Medium | **Maia DAO Ecosystem** | Solidity | Multi-chain |
