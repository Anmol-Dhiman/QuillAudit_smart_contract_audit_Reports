# Raga Finance Case Study: Fixing Fees & Withdrawal Logic

## Overview
Discover how QuillAudits helped Raga Finance fix flawed fee structures and withdrawal logic in this detailed smart contract case study.

Raga Finance is a yield aggregation platform that operates through a system of vaults and strategies.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- Vault & Strategy Logic Review
- Yield Aggregation Security
- Emergency Control Validation

## Technologies Involved
- Solidity
- ERC4626
- Berachain
- Yield Aggregation
- Smart Contracts
- DeFi Vault Infrastructure

## Key Findings
1. Fee Mismanagement in Deposits
2. Permanent Loss of User Funds Post-EmergencyWithdraw
3. Treasury Fee Loss During withdrawAll()
4. Inflated Vault Asset Values
5. No Access Control on setVault()
6. Broken Panic Logic
7. Faulty Swap Logic in Strategy
8. Mint Function DoS via Dust Attack

## Security Improvements
1. Fee Accounting Logic Refined
2. Safe Emergency Withdrawals
3. Preserved Treasury Fees During WithdrawAll()
4. Accurate totalAssets Representation
5. Access Controls Enforced on setVault()
6. Functional Panic Mechanism
7. Correct Swap Calculations
8. Mint Function Resilience

## Audit Outcome
The Raga Finance Smart Contracts security audit identified and addressed several vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the Raga Finance Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/quillaudits-secures-raga-finance
