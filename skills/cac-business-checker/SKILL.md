# 🏢 Omega CAC Business Checker

## Description
Verify Nigerian CAC business registration, RC number, status, director. Detect fake companies for POS, vendors, investors.

## Price
$0.10 per verification via Paystack (premium skill!)

## Category
business, CAC, nigeria, verification, KYC

## How to use
POST /v1/skills/cac-business-checker
{
  "skill": "cac-business-checker",
  "input": "Omega Hybrid Synergy",
  "api_key": "YOUR_KEY"
}

## Output Format (MUST return JSON)

AI MUST always return answer in this JSON format:

{
  "business_name": "Omega Hybrid Synergy",
  "is_registered": true,
  "rc_number": "RC 1234567",
  "status": "Active",
  "business_type": "Business Name",
  "verification_note": "Genuine - Check cac.gov.ng for full details",
  "risk_level": "Low"
}

Example for fake:
{
  "business_name": "Fake Ltd",
  "is_registered": false,
  "rc_number": "Not found",
  "status": "Not Registered",
  "business_type": "Unknown",
  "verification_note": "No record on CAC - Possible scam, request CAC certificate",
  "risk_level": "High"
}

## Owner
Omega Hybrid Synergy - omegahybridsynergy@gmail.com
