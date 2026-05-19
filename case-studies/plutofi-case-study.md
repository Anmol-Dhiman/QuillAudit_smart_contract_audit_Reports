# How Did QuillAudits Secure Pluto Fi’s Liquidations, Price Feeds & Reward Accuracy?

## Overview
Pluto Fi is a DeFi protocol on Solana enabling leveraged yield strategies and passive lending, optimizing returns while ensuring capital protection through safety features.

Pluto Fi, a decentralized finance (DeFi) protocol on the Solana blockchain, maximizes user earnings through leveraged yield strategies and passive lending.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- Price Oracle Validation
- Liquidation Logic Review
- Vault & Reward Calculation Analysis

## Technologies Involved
- Solana
- Rust
- DeFi Lending
- Yield Strategies
- Smart Contracts
- Pyth Oracle

## Key Findings
1. Pyth Price Feed Vulnerability
2. Liquidation Risk Post-Freeze
3. Liquidation Fee Bypass
4. Inaccurate Fractional Arithmetic
5. Unvalidated Leverage Vault in Earn Vault Index Setting

## Security Improvements
1. Implemented validation to incorporate confidence intervals into price calculations, rejecting prices with excessive uncertainty to prevent manipulation
2. Introduced a cooldown period post-unfreeze, allowing borrowers to rebalance their positions before liquidations resume
3. Enforced strict transaction sequencing, ensuring liquidation fees are deducted before closing instructions
4. Implemented explicit rounding mechanisms for correct flooring and ceiling logic
5. Introduced strict validation to verify that only registered Leverage vaults can be assigned

## Audit Outcome
The Pluto Smart Contract security audit identified and addressed critical vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the Pluto Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/how-did-quillaudits-secure-pluto-fi
