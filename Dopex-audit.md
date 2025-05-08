## About Dopex
Dopex is a maximum liquidity and minimal exposure options protocol that provides decentralized options trading services. The platform aims to provide fair option pricing, maximum liquidity, and capital efficiency for writers, along with rebates for option writers via rDPX. The backbone of the Dopex ecosystem is the Single Staking Options Vault (SSOV), which accepts deposits of a token and earns yield on them via writing options.

**Website**: https://www.dopex.io  
**Documentation**: https://docs.dopex.io  
**GitHub**: https://github.com/code-423n4/2023-08-dopex
<br/>


## Contest Period
The Dopex audit on Code4rena took place from August 21, 2023 to September 6, 2023, with a prize pool of $125,000 USDC. The audit analyzed the Dopex smart contract system written in Solidity and yielded 26 unique vulnerabilities, including 9 high-severity and 17 medium-severity issues. The main focus of the audit was on rDPX V2, which introduces a new synthetic coin dpxETH pegged to ETH, designed to earn boosted yields on ETH and serve as collateral for future Dopex Options Products.

**Code4rena**: https://code4rena.com/audits/2023-08-dopex  
**Audit Report**: https://code4rena.com/reports/2023-08-dopex
<br/><br/>



## Dopex - My Findings
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;03 | The settle feature will be broken if attacker arbitrarily transfer collateral tokens to the PerpetualAtlanticVaultLP [report ->](https://code4rena.com/reports/2023-08-dopex#h-03-the-settle-feature-will-be-broken-if-attacker-arbitrarily-transfer-collateral-tokens-to-the-perpetualatlanticvaultlp) | High | **Dopex** | Solidity | Arbitrum |
| H-07 | Incorrect precision assumed from RdpxPriceOracle creates multiple issues related to value inflation/deflation [report ->](https://code4rena.com/reports/2023-08-dopex#h-07-incorrect-precision-assumed-from-rdpxpriceoracle-creates-multiple-issues-related-to-value-inflationdeflation) | High | **Dopex** - Options trading platform with perpetual vaults and rebates | Solidity | Arbitrum |
| H-05 | Users can get immediate profit when deposit and redeem in `PerpetualAtlanticVaultLP` [report ->](https://code4rena.com/reports/2023-08-dopex#h-05-users-can-get-immediate-profit-when-deposit-and-redeem-in-perpetualatlanticvaultlp) | High | **Dopex** | Solidity | Arbitrum |
| M&#x2011;02 | The vault allows "free" swaps from WETH to RDPX [report ->](https://code4rena.com/reports/2023-08-dopex#m-02-the-vault-allows-free-swaps-from-weth-to-rdpx) | Medium | **Dopex** | Solidity | Arbitrum |
| M-14 | No slippage protection for bonders [report ->](https://code4rena.com/reports/2023-08-dopex#m-14-no-slippage-protection-for-bonders) | Medium | **Dopex** | Solidity | Arbitrum |
| M-13 | Can not withdraw RDPX if WETH withdrawn is zero [report ->](https://code4rena.com/reports/2023-08-dopex#m-13-cannot-withdraw-rdpx-if-weth-withdrawn-is-zero) | Medium | **Dopex** | Solidity | Arbitrum |
| M-15 | `sync` function in `RdpxV2Core.sol` should be called in multiple scenarios to account for the balance changes that occurs [report ->](https://code4rena.com/reports/2023-08-dopex#m-15-sync-function-in-rdpxv2coresol-should-be-called-in-multiple-scenarios-to-account-for-the-balance-changes-that-occurs) | Medium | **Dopex** | Solidity | Arbitrum |

