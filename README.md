# Phishing Detection for Financial Sector

## Overview
This project develops an online machine learning model for detecting phishing attacks specifically targeting the financial sector. The model uses URL-based features with custom financial indicators to detect zero-day phishing attacks in real-time.

## Dataset
- **Size:** 572,119 samples
- **Features:** 27 (including 14 custom financial features)
- **Sources:** 
  - PhiUSIIL (UCI) - 235,370 samples
  - StealthPhisher (IEEE) - 336,749 samples

### Custom Financial Features
- Bank keyword detection (Chase, PayPal, HSBC, etc.)
- Urgency term detection (urgent, suspended, verify)
- URL entropy (randomness score)
- Suspicious TLD detection (.xyz, .top, etc.)
- And 10 more financial-specific indicators

## 🚧 Project Status

**Current Phase:** Data cleaning and feature engineering complete. Model training in progress.

| Phase | Status |
|-------|--------|
| Dataset Collection | ✅ Complete |
| Data Cleaning | ✅ Complete |
| Feature Engineering | ✅ Complete |
| Model Training | 🔄 In Progress |
| Online Learning | ⬜ Pending |
| Zero-Day Detection | ⬜ Pending |
| Software Tool | ⬜ Pending |
| Paper Writing | 🔄 In Progress |
