## About Asymmetry Protocol

Asymmetry Protocol is a staking platform designed to diversify and decentralize liquid staking derivatives. The platform offers safETH, a token that represents a basket of liquid staking derivatives including Lido's wstETH, Rocketpool's rETH, and Frax's frxETH, functioning similar to an ETF for liquid staking tokens and allowing users to gain diversified exposure to Ethereum staking.

**GitHub**: https://github.com/code-423n4/2023-03-asymmetry  
**Website**: https://www.asymmetry.finance

## Contest Period

The Asymmetry Protocol audit on Code4rena took place from March 24-30, 2023, with a total award pool of $49,200 USDC. The audit identified multiple vulnerabilities, including M-10 which described how ETH can become stuck when using the stake function with empty derivatives, a critical issue affecting the protocol's ability to handle certain staking conditions.

**Code4rena**: https://code4rena.com/audits/2023-03-asymmetry-contest



<br/>

## Asymmetry contest - My Findings:
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| M&#x2011;10 | Stuck ether when use function `stake` with empty `derivatives`(`derivativeCount` = 0) [report ->](https://code4rena.com/reports/2023-03-asymmetry#m-10-stuck-ether-when-use-function-stake-with-empty-derivativesderivativecount--0) | Medium | **Asymmetry contest** - Staking platform with derivatives functionality and ETH management | Solidity | Ethereum |
