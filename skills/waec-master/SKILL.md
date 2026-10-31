# 📖 Omega WAEC Master

## Description
WAEC/WASSCE solver - 2024 syllabus, past questions, practicals, theory. 90% accuracy for Nigerian secondary students.

## Price
$0.03 per question via Paystack

## Category
education, waec, wassce, nigeria, exam

## How to use
POST /v1/skills/waec-master
{
  "skill": "waec-master",
  "input": "Explain photosynthesis equation",
  "subject": "Biology",
  "api_key": "YOUR_KEY"
}

## Output Format (MUST return JSON)

AI MUST always return answer in this JSON format:

{
  "answer": "6CO2 + 6H2O -> C6H12O6 + 6O2 - Photosynthesis converts light energy...",
  "confidence": "High",
  "explanation": "Full WAEC marking scheme style answer, include practical observation if needed",
  "subject": "Biology",
  "exam_type": "WAEC Theory"
}

Example:
{
  "answer": "A - The process is evaporation",
  "confidence": "High",
  "explanation": "WAEC 2023 Objective Q15 - Evaporation occurs at all temperatures, boiling only at boiling point. Syllabus reference: SS2 Physics.",
  "subject": "Physics",
  "exam_type": "WAEC Objective"
}

## Owner
Omega Hybrid Synergy - omegahybridsynergy@gmail.com
