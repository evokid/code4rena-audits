## About Munchables
Munchables is a token locking and price approval protocol with mechanism design. It focuses on providing tools for token locking and managing price approvals within its ecosystem, implementing various mechanisms to ensure token stability and user engagement.

**GitHub**: https://github.com/code-423n4/2024-05-munchables  
**Documentation**: https://docs.munchables.xyz  
**Website**: https://munchables.xyz

<br/>

## Contest Period
The Munchables audit on Code4rena took place from May 28, 2024 to early June 2024. The audit examined the protocol's smart contracts with a focus on the token locking mechanics and price approval systems.

**Code4rena**: https://code4rena.com/audits/2024-05-munchables  

<br/>

## Munchables - My Findings
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;01 | Malicious User can call `lockOnBehalf` repeatedly extend a users `unlockTime`, removing their ability to withdraw previously locked tokens [report ->](https://code4rena.com/reports/2024-05-munchables#h-01-malicious-user-can-call-lockonbehalf-repeatedly-extend-a-users-unlocktime-removing-their-ability-to-withdraw-previously-locked-tokens) | High | **Munchables** - Token locking and price approval protocol with mechanism design | Solidity | Ethereum |
| M&#x2011;01 | Missing disapproval check in `LockManager.sol::approveUSDPrice` allows simultaneous approval and disapproval of a price proposal [report ->](https://code4rena.com/reports/2024-05-munchables#m-01-missing-disapproval-check-in-lockmanagersolapproveusdprice-allows-simultaneous-approval-and-disapproval-of-a-price-proposal) | Medium | **Munchables** | Solidity | Ethereum |
