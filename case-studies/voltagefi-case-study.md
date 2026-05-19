# How QuillAudits Revamped Voltage Finance's Reward Mechanism

## Overview
QuillAudits conducted an in-depth security audit of Voltage Finance, identifying and rectifying critical vulnerabilities to enhance the protocol's security and reliability.

The Voltage Finance Protocol is a decentralized finance (DeFi) platform designed to offer an array of yield farming, swapping, and staking opportunities for its users.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- Reward Distribution Logic Review
- Liquidity & Flash Loan Security
- Yield Farming Security Analysis

## Technologies Involved
- Solidity
- Fuse Network
- DeFi
- DEX
- Yield Farming
- Smart Contracts

## Key Findings
1. Reward Value Overwriting Leads to Incorrect Reward Distribution During Harvest
2. Incorrect Transfer of Double Reward to User
3. Improper handling of flash loan functionalities increased susceptibility to price manipulation attacks in certain liquidity pools

## Security Improvements
1. The reward calculation logic was fixed, ensuring that Volt and Fuse tokens are independently calculated and distributed without any overwriting, allowing users to receive the intended reward amounts
2. The double reward transfer logic was corrected, ensuring that users receive the exact Fuse token rewards as per the intended protocol design
3. Introduced verification checks to mitigate flash loan exploits, ensuring stable and fair pricing mechanisms

## Audit Outcome
The Voltage Finance V3 Protocol’s smart contracts security audit identified and addressed critical vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the Voltage Finance V3 Protocol Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/voltage-finance-security-audit
