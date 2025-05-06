
## About Lambo.win
Lambo.win is a protocol that introduces the concept of virtual liquidity to meet the liquidity needs of projects. The protocol establishes deep liquidity pools to satisfy the buying and selling activities of users, creating a win-win situation where liquidity providers earn fees while retail investors and developers resolve their liquidity issues. The core concept involves virtual tokens which are conditional ERC20 tokens that ensure issued virtual liquidity doesn't enter the market, with each holder address requiring a specific balance formula.

GitHub: [https://github.com/code-423n4/2024-12-lambowin](https://github.com/code-423n4/2024-12-lambowin)

## Contest Period
The Lambo.win audit on Code4rena took place from December 2 to December 9, 2024, with a total prize pool of $22,500 in USDC. The audit was judged by Koolex and the final report was assembled by Code4rena.

Audit page: [https://code4rena.com/audits/2024-12-lambowin](https://code4rena.com/audits/2024-12-lambowin)

## My Findings:

| ID | Issue | Severity | Protocol | Language | Blockchain |
|---|---|---|---|---|---|
| H&#x2011;01 | Minting zero tokens when underlyingToken is not Ether in cashIn() [report ->](https://code4rena.com/reports/2024-12-lambowin#h-01-loss-of-user-funds-in-virtualtokens-cashin-function-due-to-incorrect-amount-minting) | High | **Lambo.win** - Tokenized virtual assets platform with rebalancing mechanisms | Solidity | Ethereum |
| H-02 | LamboFactory can be permanently DoS-ed due to createPair call reversal [report ->](https://code4rena.com/reports/2024-12-lambowin#h-02-lambofactory-can-be-permanently-dos-ed-due-to-createpair-call-reversal) | High | **Lambo.win** | Solidity | Ethereum |
| H-04 | Anyone can call `LamboRebalanceOnUniwap.sol::rebalance()` function with any arbitrary value, leading to rebalancing goal i.e. (1:1 peg) unsuccessful [report ->](https://code4rena.com/reports/2024-12-lambowin#h-04-anyone-can-call-lamborebalanceonuniwapsolrebalance-function-with-any-arbitrary-value-leading-to-rebalancing-goal-ie-11-peg-unsuccessful) | High | **Lambo.win** | Solidity | Ethereum |
| M&#x2011;01 | Since the cost of launching a new pool is minimal, an attacker can maliciously consume VirtualTokens [report ->](https://code4rena.com/reports/2024-12-lambowin#m-01-since-the-cost-of-launching-a-new-pool-is-minimal-an-attacker-can-maliciously-consume-virtualtokens) | Medium | **Lambo.win** | Solidity | Ethereum |
| M-03 | `sellQuote` and `buyQuote` are missing deadline check in `LamboVEthRouter` [report ->](https://code4rena.com/reports/2024-12-lambowin#m-03-sellquote-and-buyquote-are-missing-deadline-check-in-lambovethrouter) | Medium | **Lambo.win** | Solidity | Ethereum |
| M-04 | Accumulated ETH in the LamboVEthRouter will be irretrievable [report ->](https://code4rena.com/reports/2024-12-lambowin#m-04-accumulated-eth-in-the-lambovethrouter-will-be-irretrievable) | Medium | **Lambo.win** | Solidity | Ethereum |
| M-07 | **Solo** - Rebalance profit requirement prevents maintaining VETH/WETH peg [report ->](https://code4rena.com/reports/2024-12-lambowin#m-07-rebalance-profit-requirement-prevents-maintaining-vethweth-peg-) | Medium | **Lambo.win** | Solidity | Ethereum |
| M-08 | Users can prevent protocol from rebalancing for his gain and cause loss of funds for protocol and its users [report ->](https://code4rena.com/reports/2024-12-lambowin#m-08-users-can-prevent-protocol-from-rebalancing-for-his-gain-and-cause-loss-of-funds-for-protocol-and-its-users) | Medium | **Lambo.win** | Solidity | Ethereum |
| M-09 | Rebalance will be completely dossed if OKX commision rate goes beyond the fee limits [report ->](https://code4rena.com/reports/2024-12-lambowin#m-09-rebalance-will-be-completely-dossed-if-okx-commision-rate-goes-beyond-the-fee-limits) | Medium | **Lambo.win** | Solidity | Ethereum |


