
## About MANTRA DEX
MANTRA DEX is a decentralized exchange (DEX) protocol that allows for permissionless pool and farm creation. The protocol is built around singleton contracts, which makes it easier to manage and integrate with other protocols. It's a fork of White Whale V2, which was originally licensed under the MIT License. The DEX architecture includes several key components: Pool Manager for creating pools and handling swaps, Farm Manager for creating and distributing rewards on pools, Fee Collector for protocol fees, and Epoch Manager as the system clock for distributing farm rewards. [github](https://github.com/code-423n4/2024-11-mantra-dex) [documentation](https://docs.mantrachain.io/mantra-smart-contracts/mantra_dex)

## Contest Period
The MANTRA DEX audit on Code4rena ran from November 29, 2024 to January 13, 2025, with a total prize pool of $60,000 in USDC. This was a competitive audit where security researchers (known as wardens) competed to find vulnerabilities in the protocol. [code4rena](https://code4rena.com/audits/2024-11-mantra-dex)

## My Findings:
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H-01 | **Solo** - Pool creation can be manipulated to drain protocol fees [report ->](#audit_link) | High | **MANTRA DEX** - Decentralized exchange with advanced liquidity and trading features | Rust | MANTRA |
| M-04 | Epoch Manager allows reward distribution manipulation through improper validation [report ->](#audit_link) | Medium | **MANTRA DEX** | Rust | MANTRA |

