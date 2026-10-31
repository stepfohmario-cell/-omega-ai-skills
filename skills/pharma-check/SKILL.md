# 💊 Omega Pharma Check

## Description
Nigerian drug verification - check NAFDAC, dosage, interactions, fake drugs. Safety first.

## Price
$0.02 per check via Paystack

## Category
health, pharma, nigeria, NAFDAC

## How to use
POST /v1/skills/pharma-check
{
  "skill": "pharma-check",
  "input": "Paracetamol 500mg dosage",
  "api_key": "YOUR_KEY"
}

## Output Format (MUST return JSON)

AI MUST always return answer in this JSON format:

{
  "drug_name": "Paracetamol 500mg",
  "is_genuine": true,
  "dosage": "1 tablet every 6 hours, max 4 per day",
  "warning": "Avoid alcohol, check liver disease",
  "confidence": "High"
}

Example:
{
  "drug_name": "Augmentin 625mg",
  "is_genuine": true,
  "dosage": "1 tablet twice daily for 5 days after food",
  "warning": "Allergy to penicillin - seek doctor, not for under 12y",
  "confidence": "High"
}

## Owner
Omega Hybrid Synergy - omegahybridsynergy@gmail.com
