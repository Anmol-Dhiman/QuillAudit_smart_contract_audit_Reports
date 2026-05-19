# From Vulnerable to Secure: QuillAudits’ Impact on NFTs2Me

## Overview
QuillAudits conducts a rigorous audit of NFTs2Me, identifying and rectifying 10 critical vulnerabilities to enhance the platform's security and efficiency.

NFTs2Me offers an easy interface for creating NFT artwork, defining metadata, & uploading to IPFS.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- NFT Collection Security Review
- Signature Verification Analysis
- Minting & Ownership Validation

## Technologies Involved
- Solidity
- zkSync
- Ethereum
- NFT Infrastructure
- ERC721A
- Smart Contracts

## Key Findings
1. Denial-of-Service (DoS) Vulnerability
2. Insecure Token Transfers
3. Missing Signature Expiry
4. Insecure Signature Verification

## Security Improvements
1. Imposed a defined upper limit on the size of the revenue address array in the N2MFactory contract
2. Implemented the safeTransfer function for token withdrawals in the N2MERC721A contract instead of the transfer function
3. Added an expiry timestamp to the signature verification process in the delegatedCreation function of the N2MFactory contract
4. Included the contract address in the signature verification hash in the delegatedCreation function of the N2MFactory contract and implemented a unique nonce check for each signature

## Audit Outcome
The NFTs2Me’s smart contracts security audit identified and addressed critical vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the NFTs2Me Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/nfts2me-security-audit
