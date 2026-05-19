# QuillAudits Secures Reactive Bridge: Stopping Fee Abuse, DOS and Unrecoverable Losses

## Overview
QuillAudits secures Reactive Bridge by preventing fee abuse, DoS attacks, and unrecoverable losses through smart contract audit.

Reactive Bridge is a cross-chain token bridging solution that connects the Ethereum network to the Reactive Network. It enables seamless and secure transfers of tokens, specifically converting native ETH on Reactive Network into WREACT tokens on Ethereum and vice versa.

## Scope
- Smart Contract Audit
- Cross-Chain Message Validation
- Functional Testing
- Logic & State Validation
- Fee Mechanism Review
- Security Testing & Remediation

## Technologies Involved
- Solidity
- Ethereum
- EVM
- Cross-Chain Bridge Infrastructure
- Smart Contracts

## Key Findings
- Improper Event Subscriptions left failed transactions on the destination chain unprocessed and undetectable by the Reactive Bridge, leading to no recovery.
- Faulty Rejection Logic risked Denial-of-Service (DOS) conditions during cross-chain message rejections due to inconsistent state changes.
- Fee Parameters allowed manipulation of transfer costs and increased the cost to users due to the lack of upper bounds.
- No Refund Path for Bridge-to-Bridge Failures can result in irreversible fund loss.

## Security Improvements
- Improved Event Subscription
- Fixed Rejection Handling
- Fixed bounds on Fee Parameters
- Fixed Refund Mechanism

## Audit Outcome
The Reactive Bridge Smart Contracts security audit identified and addressed several vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the Reactive Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://quillaudits.com/case-studies/reactive-bridge-security-audit
