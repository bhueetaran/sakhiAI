# SakhiAI — Technical Solution Document

## Problem Statement
70% of Indian women face gynecological problems, yet most go undetected due to illiteracy, language barriers, social stigma, and lack of awareness. Women — especially in rural India — don't know their symptoms are serious until it's too late.

## Proposed Solution
SakhiAI is a voice-first, multilingual AI health companion that helps women identify symptoms, detects red flags, and connects them to care — in their own language, without needing to read or write.

## Target Users
- Rural and semi-urban Indian women (15–50 years)
- Pregnant women with no prenatal guidance
- Young women unaware of reproductive health
- Low-literacy users who cannot navigate traditional health apps

## Key Features
1. **Multilingual support** — Hindi, Tamil, Bengali, English (10+ planned)
2. **Visual body diagram** — tap to report symptoms, no typing needed
3. **Red flag AI engine** — maps symptoms to urgency levels instantly
4. **Maternal alert system** — special pregnancy-specific danger detection
5. **Preventive screening reminders** — cervical cancer, breast cancer, anemia

## Technical Approach

### Current Stack (Prototype)
- Python 3 + Colorama — CLI interface
- Rule-based expert system — symptom → risk mapping
- Multilingual string engine — 4 languages

### Production Stack (Roadmap)
- React Native — cross-platform mobile app
- FastAPI (Python) — backend API
- Hugging Face IndicBERT / MuRIL — multilingual NLP
- Web Speech API — voice input in Indian languages
- OpenStreetMap — offline clinic/ASHA worker locator
- SQLite (offline) — symptom history tracking

### System Architecture
```
User Input (voice/tap)
        ↓
Language Detection Module
        ↓
Symptom Collection Engine (body diagram)
        ↓
Red Flag AI Engine (rule-based + ML)
        ↓
Maternal Risk Classifier
        ↓
Report Generator
        ↓
Care Navigation (ASHA / PHC locator)
```

## Impact & Scalability
- Deployable via ASHA worker network across 600,000+ villages
- Works offline — critical for rural areas with poor connectivity
- Open source — any NGO or government body can deploy and extend
- Potential to reduce maternal mortality and late-stage cancer diagnoses
- Scalable to 10+ Indian languages with community contributions
