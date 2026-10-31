# 📚 Omega JAMB Master

## Description
JAMB UTME solver - answers 2025 syllabus, past questions, explains solutions. 90% accuracy for Nigerian students.

## Price
$0.03 per question via Paystack

## Category
education, jamb, nigeria, exam

## How to use
POST /v1/skills/jamb-master
{
  "skill": "jamb-master",
  "input": "What is photosynthesis?",
  "subject": "Biology",
  "api_key": "YOUR_KEY"
}

## Output Format (MUST return JSON)

AI MUST always return answer in this JSON format:

{
  "answer": "Option B - Mitochondria is powerhouse...",
  "confidence": "High",
  "explanation": "2-3 sentences why this answer is correct, reference syllabus",
  "subject": "Biology"
}

Example:
{
  "answer": "C - x = 5",
  "confidence": "High",
  "explanation": "Using quadratic formula b²-4ac, solving gives x=5. This aligns with JAMB 2022 past question.",
  "subject": "Mathematics"
}

## Owner
Omega Hybrid Synergy - omegahybridsynergy@gmail.com
