
## About DittoETH
DittoETH is a decentralized stable asset protocol with an order book design that aims to provide low fees and extra yield. The protocol allows users to create, manage, and speculate on pegged tokens that can represent various financial instruments by using overcollateralized liquid staked ETH to create stablecoins. It takes in overcollateralized liquid staked ETH (rETH, stETH) to create stablecoins using a gas-optimized orderbook, starting with a USD stablecoin called dUSD.

On the orderbook, bidders and shorters bring ETH, while askers can sell their dUSD. Bidders get the dUSD, and shorters get the bidders' collateral and a ShortRecord to manage their debt position (similar to a CDP). Shorters play the vital role of minting pegged assets for the protocol, which happens when shorters' trades are matched on the orderbook with a corresponding long trader.

**GitHub**: https://github.com/code-423n4/2024-03-dittoeth  
**Documentation**: https://dittoeth.com  
**Website**: https://dittoeth.com

## Contest Period
The DittoETH audit on Code4rena took place from March 15, 2024 to April 5, 2024, with a prize pool of $60,800 in USDC. The audit focused on various aspects of the protocol, including the new redemption feature, which was an entirely new concept introduced to the protocol.

**Code4rena**: https://code4rena.com/audits/2024-03-dittoeth


<br/>

## DittoETH = My Findings 
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| M&#x2011;07 | Using cached price to create a proposal reduce the efficacity of redemptions for asset peg [report ->](https://code4rena.com/reports/2024-03-dittoeth#m-07-using-cached-price-to-create-a-proposal-reduce-the-efficacity-of-redemptions-for-asset-peg) | Medium | **DittoETH** - ETH-backed stablecoin with price proposals and redemption mechanism | Solidity | Ethereum |
