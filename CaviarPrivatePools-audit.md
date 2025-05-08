## About Caviar Private Pools

Caviar Private Pools is an NFT trading platform that allows users to create customizable liquidity pools for NFT trading. These private pools enable concentrated liquidity, custom fee rates, NFT weightings, and royalty fee support. The platform lets traders buy, sell, and exchange NFTs within these pools, with features for stolen NFT filtering and flashloan capabilities.

**GitHub**: https://github.com/outdoteth/caviar-private-pools  
**Website**: https://docs.caviar.sh

## Contest Period

The Caviar Private Pools audit on Code4rena took place from April 7-13, 2023. The audit identified a total of 20 unique vulnerabilities, including 3 HIGH and 17 MEDIUM severity issues. A critical finding (M-09) revealed that malicious royalty recipients could steal excess ETH from buy orders when users trade through the EthRouter contract.

**Code4rena**: https://code4rena.com/reports/2023-04-caviar



<br/>

## Caviar Private Pools - My Findings:
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| M&#x2011;09 | Malicious royalty recipient can steal excess eth from buy orders [report ->](https://code4rena.com/reports/2023-04-caviar#m-09-malicious-royalty-recipient-can-steal-excess-eth-from-buy-orders) | Medium | **Caviar Private Pools** - NFT trading platform with private pools and royalty mechanisms | Solidity | Ethereum |
