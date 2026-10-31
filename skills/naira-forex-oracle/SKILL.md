# 💱 Omega Naira Forex Oracle

## Description
Live Naira USD/EUR/GBP black market & CBN rates, prediction, best P2P platform. Updates hourly for Nigerian traders.

## Price
$0.04 per call via Paystack / Flutterwave

## Category
finance, forex, naira, nigeria, trading

## How to use
POST /v1/skills/naira-forex-oracle
{
  "skill": "naira-forex-oracle",
  "input": "USD to NGN today",
  "api_key": "YOUR_KEY"
}

## Output Format (MUST return JSON)

AI MUST always return answer in this JSON format:

{
  "base_currency": "USD",
  "official_rate": 1530.5,
  "black_market_rate": 1645.0,
  "best_platform": "Binance P2P - 1642 NGN",
  "prediction": "Naira may weaken 2% this week due to CBN policy",
  "confidence": "High"
}

Example:
{
  "base_currency": "USD",
  "official_rate": 1530.5,
  "black_market_rate": 1645.0,
  "best_platform": "Bybit P2P - 1648 NGN",
  "prediction": "Stable - CBN injected dollars today",
  "confidence": "Medium"
}

## Owner
Omega Hybrid Synergy - omegahybridsynergy@gmail.com
