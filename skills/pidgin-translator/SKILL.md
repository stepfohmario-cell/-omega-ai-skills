# 🗣️ Omega Pidgin Translator

## Description
Nigerian Pidgin ↔ English ↔ Yoruba/Igbo/Hausa translator. Real street Pidgin, not textbook. For chatbots, content, diaspora.

## Price
$0.01 per translation via Paystack (high volume!)

## Category
translation, pidgin, nigeria, language, AI

## How to use
POST /v1/skills/pidgin-translator
{
  "skill": "pidgin-translator",
  "input": "How are you doing today?",
  "target": "pidgin",
  "api_key": "YOUR_KEY"
}

## Output Format (MUST return JSON)

AI MUST always return answer in this JSON format:

{
  "original": "How are you doing today?",
  "translated": "How you dey today? You well?",
  "language": "pidgin",
  "confidence": "High",
  "alternative": "Wetin dey sup today?"
}

Example:
{
  "original": "I no get money",
  "translated": "I don't have money",
  "language": "english",
  "confidence": "High",
  "alternative": "I'm broke"
}

## Owner
Omega Hybrid Synergy - omegahybridsynergy@gmail.com
