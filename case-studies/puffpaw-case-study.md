# This Vape-to-Earn Project Had a Hidden Flaw… We Found It First

## Overview
Our thorough audit identified critical vulnerabilities in reward logic and data integrity, delivering targeted fixes to ensure accurate tracking, fair incentives, and secure protocol execution.

Puffpaw operates as a cross-chain token infrastructure built on LayerZero’s Omnichain Fungible Token (OFT) standard, designed to enable seamless token interoperability across multiple blockchain networks.

## Scope
- Smart Contract Audit
- Functional Testing
- Manual Code Review
- Automated Security Testing
- Threat Modelling
- Cross-Chain Infrastructure Review

## Technologies Involved
- Solidity
- Ethereum
- LayerZero
- OFT Standard
- DePIN
- Smart Contracts

## Key Findings
1. Lack of Input Validation
2. Floating Pragma
3. Ownership Transfer Security

## Security Improvements
1. Input Validation (Critical Addresses) - Added explicit zero-address validation for all critical constructor parameters, ensuring safe deployment and preventing misconfiguration
2. Compiler Version Consistency - Fixed the Solidity compiler version to ensure consistent, predictable builds across environments
3. Ownership Transfer Security - Implemented Ownable2Step to enforce a secure two-step ownership transfer process, reducing the risk of accidental misconfiguration

## Audit Outcome
The PuffPaw smart contracts security audit identified and addressed critical vulnerabilities, protecting user funds and ensuring platform stability.

By conducting audits and addressing identified issues, the PuffPaw Team has taken a significant step towards securing its platform and safeguarding user trust.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/quillaudits-secured-puffpaw-core-systems
