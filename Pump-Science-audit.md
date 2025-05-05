## About Pump Science

Pump Science Bonding Curve Protocol is a Solana protocol implementing an advanced bonding curve mechanism for fundraising and sustainable project funding. This protocol enables compound submitters to launch their own token ($DRUG) with dynamic fee structures and automated liquidity management. [github](https://github.com/code-423n4/2025-01-pump-science)

## Contest Period

The Pump Science audit took place from January 15 to January 23, 2025, running for a duration of 8 days. [code4rena](https://code4rena.com/audits/2025-01-pump-science)

## My Findings:
| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| M&#x2011;02 | **Solo** - Bonding Curve Invariant Check Incorrectly Validates SOL Balance Due to Rent Inclusion [report ->](https://code4rena.com/reports/2025-01-pump-science#m-02-bonding-curve-invariant-check-incorrectly-validates-sol-balance-due-to-rent-inclusion) | Medium | **Pump Science** - DeFi protocol implementing tokenized longevity research with bonding curve mechanisms | Rust | Solana |
| M-03 | Abrupt fee transition from 8.76% to 1% at slot 250 due to incorrect linear decrease formula [report ->](https://code4rena.com/reports/2025-01-pump-science#m-03-abrupt-fee-transition-from-876-to-1-at-slot-250-due-to-incorrect-linear-decrease-formula) | Medium | **Pump Science** | Rust | Solana |
