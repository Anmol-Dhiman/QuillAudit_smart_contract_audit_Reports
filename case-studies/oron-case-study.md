# Learn How QuillAudits Enhanced Oron Wallet Security by Fixing IDOR & Data Exposure Issues

## Overview
QuillAudits conducted an extensive security audit of Oron Wallet, uncovering and rectifying 10 critical vulnerabilities to bolster the wallet's security & reliability.

Oron Wallet offers a decentralized Web3 platform for managing various cryptocurrencies, providing features like sending, receiving, buying, selling, and staking digital assets.

## Scope
- Wallet Security Audit
- Vulnerability Assessment
- Penetration Testing
- Access Control Validation
- Sensitive Data Protection Review
- SSL & Communication Security Analysis

## Technologies Involved
- Android
- Multichain
- Web3 Wallet Infrastructure
- Dapp Integrations
- Mobile Security
- Cryptocurrency Wallets

## Key Findings
1. Insecure Direct Object References (IDOR)
2. IDOR Leading to Secret Key Leakage
3. Missing Rate Limiting
4. Sensitive Data Exposure in Memory Dumps
5. Improper Storage of Sensitive Data
6. Lack of SSL Pinning

## Security Improvements
1. Implemented proper access control mechanisms to validate user authorization before granting access to resources
2. Enhanced access controls to protect sensitive parameters like wallet_address
3. Introduced rate limiting by setting thresholds on the number of requests a user or device can send within a specific timeframe
4. Implemented encryption for sensitive data stored in memory and ensured it is securely erased after use
5. Migrated sensitive data storage from Android Shared Preferences to a more secure storage mechanism
6. Integrated SSL Pinning to ensure that the application only trusts specific, pre-defined server certificates

## Audit Outcome
The Oron Web3 Android Wallet security audit identified and addressed High Medium and Low severity vulnerabilities and other Best Practices, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the Oron Wallet Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/oron-wallet-security-audit
