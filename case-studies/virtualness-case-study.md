# Inside the Fix: QuillAudits' Strategy for Securing Virtualness Protocol

## Overview
QuillAudits conducts a rigorous audit of Virtualness Protocol, identifying and rectifying 40 critical vulnerabilities to enhance the platform's security and efficiency.

Virtualness provides a mobile-first platform that empowers creators & brands to create, mint, & showcase digital collectibles like art, videos, music, & tokens.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- NFT Marketplace Security Review
- Lazy Minting Validation
- Token Transfer & Role Management Analysis

## Technologies Involved
- Solidity
- Polygon
- ERC721
- ERC1155
- NFT Marketplace Infrastructure
- Smart Contracts

## Key Findings
1. Reuse of MintData for Different Orders
2. Royalty Fee Transfer Issue during Lazy Minting
3. Seller Order Manipulation Before Signing
4. Lack of SafeERC Usage for Critical Operations
5. Address Role Removal Considerations

## Security Improvements
1. Enhanced validation ensured sell.order.trader and sell.order.collection.tokenId matched mintData.creators[0].account and mintData.tokenId
2. Adjusted the operation sequence to ensure royalty information is set before calling transferFunds()
3. Implemented backend checks to calculate platform fees directly within smart contracts
4. Resolved the issue by replacing direct token transfer operations with SafeERC functions like safeTransferFrom()
5. Addressed this by implementing a verification step in the lazy minting process to ensure that the signer's role is still valid at the time of minting execution

## Audit Outcome
The Virtualness Protocol’s smart contracts security audit identified and addressed critical vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the Virtualness Protocol Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/virtualness-protocol-security-audit
