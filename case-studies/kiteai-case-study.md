# Securing a $33M VC-Backed Project: How QuillAudits Strengthened Kite AI’s Core Systems

## Overview
QuillAudits conducted a comprehensive security audit for Kite AI, a web-based platform built around a modular points and XP system designed to drive user engagement and interaction.

The engagement focused on strengthening authentication flows, airdrop logic, wallet verification, frontend security, and infrastructure protections.

## Scope
- Authentication & Authorization Testing
- API Security Testing
- Wallet Signature Verification
- Frontend Security Assessment
- Infrastructure Security Review
- Threat Modelling & Vulnerability Analysis

## Technologies Involved
- Solidity
- Ethereum
- EVM
- Web3 Authentication
- Smart Contracts
- API Infrastructure

## Key Findings
- Keys exposed in client bundle
- No authentication on critical endpoints
- Missing wallet signature verification
- OAuth state parameter not validated
- Quiz creation denial of service vulnerabilities
- Clickjacking risks on claim pages

## Security Improvements
- Keys secured server-side and rotated
- Strong authentication and validation enforced
- Signature-based ownership verification added
- Proper validation and user binding enforced
- Frame protection implemented
- Backend validation and access controls strengthened

## Audit Outcome
By addressing these issues, Kite AI eliminated multiple real-world attack vectors that could have led to unauthorized claims, account compromise, and fund loss.

The fixes strengthened security across authentication, wallet interactions, and claim logic while significantly reducing the platform’s overall risk surface.

## Full Case Study
Read the complete case study here:

https://www.quillaudits.com/case-studies/quillaudits-secured-kite-ai-core-systems
