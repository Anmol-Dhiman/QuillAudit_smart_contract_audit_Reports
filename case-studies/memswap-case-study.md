# Memeswap's Vault & DoS Issues Resolved: How QuillAudits Made It Happen

## Overview
QuillAudits executed an in-depth audit of Memeswap, identifying and rectifying 19 critical vulnerabilities, significantly bolstering the platform’s security and performance.

Memeswap offers a user-friendly interface for trading meme tokens, allowing users to swap, add, and remove liquidity effortlessly.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- Vault & Liquidity Security Review
- Slippage & Queue Logic Validation
- Access Control Analysis

## Technologies Involved
- Solidity
- Scroll
- Base
- Blast
- Berachain
- DEX Infrastructure

## Key Findings
1. Malicious Contract Exploit Resulting in Protocol Shutdown
2. Potential Denial of Service Vulnerability in MemeswapVault
3. Potential Slippage Risk Due to Zero Minimum Amounts in Liquidate Function
4. Contract Initialization Vulnerability in MemeswapTokenFactory

## Security Improvements
1. QuillAudits introduced checks within the trigger modifier to verify that Ether transfers proceed only to contracts that do not revert
2. QuillAudits implemented safeguards to prevent underflow and overflow conditions during enqueue and dequeue operations
3. QuillAudits enforced non-zero minimum amounts in the liquidate function
4. QuillAudits added a check to prevent multiple initializations

## Audit Outcome
The MemeSwap’s smart contracts security audit identified and addressed critical vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the MemeSwap Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/memeswap-security-audit
