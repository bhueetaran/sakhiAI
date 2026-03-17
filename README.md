# 🌸 SakhiAI 

> *Every woman deserves a friend who knows health.*

**SakhiAI** is an AI-powered health companion for Indian women — designed for rural, semi-urban, and urban users alike. It helps women identify symptoms, detect red flags, and get guidance in their own language — before it's too late.

---

## 🚨 The Problem

- **70%** of Indian women face gynecological problems
- Women in rural India often don't know their symptoms are serious
- Illiteracy, language barriers, and social stigma prevent timely care
- Maternal health crises often go undetected until it's an emergency
- Cervical & breast cancer screenings are almost non-existent in rural areas

**Most women don't go to a doctor because nobody ever told them something was wrong.**

---

## 💡 What SakhiAI Does

SakhiAI is not a replacement for a doctor. It's the **friend who tells you — you need to see one.**

```
Choose your language (Hindi / Tamil / Bengali / English)
        ↓
Answer a quick pregnancy check
        ↓
Tap the body area where you feel discomfort
        ↓
Select your symptoms (color-coded by severity)
        ↓
Get an instant health report with:
  🔴 Red flag alerts
  🤰 Pregnancy-specific warnings
  💡 Actionable recommendations
  🔬 Preventive screening reminders
  🏥 Guidance to nearest ASHA worker / PHC
```

---

## ✨ Features

| Feature | Description |
|--------|-------------|
| 🌐 Multilingual | Hindi, Tamil, Bengali, English |
| 🫀 Body Diagram | Visual symptom selector — no medical words needed |
| 🔴 Red Flag Detector | AI flags symptoms needing urgent care |
| 🤰 Maternal Alerts | Special warnings for pregnant women |
| 🔬 Screening Reminders | Cervical cancer, breast cancer, anemia checks |
| 📋 Health Report | Shareable report to show to doctor/ASHA worker |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation

```bash
# Clone the repo
git clone https://github.com/bhueetaran/sakhiAI.git
cd sakhiAI

# Install dependencies
pip install -r requirements.txt

# Run SakhiAI
python sakhi_prototype1.py
```

---

## 🛠️ Tech Stack
### ✅ Current (Prototype)
- **Python 3** — core logic and processing  
- **Gradio** — interactive web-based UI  
- **Rule-Based AI Engine** — symptom → risk mapping  
- **Multilingual UI System** — language-specific rendering  
- **Custom Symptom Dataset** — structured symptom + severity mapping  

### 🚀 Future Tech Stack (Planned)
- **NLP Models (IndicBERT / LLMs)** — natural language understanding  
- **Speech-to-Text (Web Speech API / Whisper)** — voice input support  
- **React Native** — mobile application development  
- **Geolocation APIs** — nearest PHC / ASHA worker guidance  
- **Offline-first Architecture** — for low-connectivity regions  
- **Cloud Backend (Firebase / FastAPI)** — scalability and data handling  

> ⚠️ Note: The current version is a working prototype. The future stack outlines planned enhancements for scalability and accessibility.

---

## 🗺️ Roadmap

- [x] Multilingual support (4 languages)
- [x] Body diagram symptom selector
- [x] Red flag detection engine
- [x] Pregnancy-specific alerts
- [x] Preventive screening reminders
- [ ] Voice input (Web Speech API)
- [ ] Offline mode
- [ ] Mobile app (React Native)
- [ ] Integration with ASHA worker network
- [ ] 10+ Indian language support

---

## 📁 Project Structure

```
sakhi-ai/
├── sakhi_prototype1.py          # Main application
├── requirements.txt     # Dependencies
├── LICENSE              # MIT License
├── README.md            
└── solution.md     # Technical approach & architecture
```

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

---

## Built with ❤️ because every woman deserves to be heard🌸

