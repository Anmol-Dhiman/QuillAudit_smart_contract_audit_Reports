# Discover how QuillAudits Secured Buk Protocol by Addressing Re-Entrancy & Transaction Logic

## Overview
QuillAudits conducts a rigorous audit of Buk Protocol, identifying and rectifying 8 critical vulnerabilities to enhance the platform's security and efficiency.

Buk Protocol offers a modular infrastructure for dApps and marketplaces, enabling the tokenization and on-chain trading of dynamic assets.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- NFT & Booking Logic Validation
- Marketplace Security Review
- Transaction Logic Analysis

## Technologies Involved
- Solidity
- Polygon
- NFTs
- Marketplace Infrastructure
- RWA
- Smart Contracts

## Key Findings
1. Unrestricted Booking and Potential NFT Misuse
2. Inconsistent NFT Ownership Handling
3. Inconsistent Transaction Logic

## Security Improvements
1. Implemented validation checks in bookRooms(), enhanced mintBukNFT() to validate before minting
2. Revised checkout() to verify bukNFT ownership
3. Aligned emergencyCancellation() and cancelRooms() to direct cancellation charges to the correct addresses

## Audit Outcome
The Buk Protocol's smart contract security audit identified and resolved critical vulnerabilities, safeguarding user funds and ensuring platform stability.

By conducting thorough audits and addressing the issues found, the Buk Protocol team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/buk-protocol-security-audit
