# QuillAudits Boosted FooDriver Protocol: Fixed Pricing Rates

## Overview
QuillAudits conducted an in-depth security audit of FooDriver, identifying and rectifying critical vulnerabilities to enhance the protocol's security and efficiency.

The FooDriver Protocol is a decentralized application (dApp) designed to revolutionize the delivery industry by utilizing blockchain technology.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- Token Minting Logic Review
- Pricing & Payment Validation
- Upgradeable Contract Security

## Technologies Involved
- Solidity
- Polygon
- Dapp
- Smart Contracts
- ERC20
- Upgradeable Contracts

## Key Findings
1. Incorrect Rate Accounting Resulting in Excessive Token Minting
2. Missing Token Transfer Validation Allowing Unauthorized Minting
3. Inaccurate Token Pricing in FooDriverToken
4. Missing Gap Variables Leading to Potential Storage Collisions in Upgradeable Contracts
5. Improper handling of fee-on-transfer tokens

## Security Improvements
1. Corrected the rate calculation logic, ensuring users receive the accurate number of tokens as intended
2. Implemented proper validation checks on transferFrom, ensuring that tokens are only minted when the transfer is successful
3. Updated the pricing mechanism to ensure accurate and dynamic token rates, preventing any potential underpricing
4. Introduced gap variables to safeguard against storage collisions, ensuring future contract upgrades remain secure
5. Enhanced contract logic to account for fee-on-transfer tokens, ensuring accurate calculations and preventing losses

## Audit Outcome
The FooDriver Protocol’s smart contracts security audit identified and addressed critical vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the FooDriver Protocol Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/foodriver-protocol-security-audit
