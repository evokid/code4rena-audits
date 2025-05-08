## About NOYA
NOYA is an asset management protocol with accounting and withdrawal queue systems. The protocol provides infrastructure for asset management with sophisticated accounting mechanisms to track user balances and a structured withdrawal system to ensure orderly processing of user withdrawals.

**GitHub**: https://github.com/code-423n4/2024-04-noya  
**Documentation**: https://docs.noya.io  
**Website**: https://noya.io  

<br>

## Contest Period
The NOYA audit on Code4rena took place from April 18, 2024 to May 1, 2024. The audit focused on the protocol's core accounting mechanisms and withdrawal systems.

**Code4rena**: https://code4rena.com/audits/2024-04-noya  

<br>


## NOYA - My Findings
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;04 | `executeWithdraw` may be blocked if any of the users are blacklisted from the `baseToken` [report ->](https://code4rena.com/reports/2024-04-noya#h-04-executewithdraw-may-be-blocked-if-any-of-the-users-are-blacklisted-from-the-basetoken) | High | **NOYA** - Asset management protocol with accounting and withdrawal queue systems | Solidity | Ethereum |
| H-10 | `AccountingManager::resetMiddle` will not behave as expected [report ->](https://code4rena.com/reports/2024-04-noya#h-10-accountingmanagerresetmiddle-will-not-behave-as-expected) | High | **NOYA** | Solidity | Ethereum |
| M&#x2011;13 | Missing calls to `_updateTokenInRegistry` leads to incorrect state of tokens in registry [report ->](https://code4rena.com/reports/2024-04-noya#m-13-missing-calls-to-_updatetokeninregistry-leads-to-incorrect-state-of-tokens-in-registry) | Medium | **NOYA** | Solidity | Ethereum |
| M-19 | Attacker can increase the length of `withdrawQueue` by withdrawing 0 amount of tokens frequently [report ->](https://code4rena.com/reports/2024-04-noya#m-19-attacker-can-increase-the-length-of-withdrawqueue-by-withdrawing-0-amount-of-tokens-frequently) | Medium | **NOYA** | Solidity | Ethereum |
| M-26 | The `TVLHelper.sol#getTVL` function is DOSed by the `under collateralized connector`, and as a result, many parts of the protocol may be DOS [report ->](https://code4rena.com/reports/2024-04-noya#m-26-the-tvlhelpersolgettvl-function-is-dosed-by-the-under-collateralized-connector-and-as-a-result-many-parts-of-the-protocol-may-be-dos) | Medium | **NOYA** | Solidity | Ethereum |
| M-27 | Withdrawals in AccountManager are prone to DOS attacks [report ->](https://code4rena.com/reports/2024-04-noya#m-27-withdrawals-in-accountmanager-are-prone-to-dos-attacks) | Medium | **NOYA** | Solidity | Ethereum |

