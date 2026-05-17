# 🌾 Farmer's Voice Assistant

## Giving a voice to 500 million farmers who can't read.

[![Gemma 4 Hackathon](https://img.shields.io/badge/Gemma%204%20Good-Hackathon-green)](https://www.kaggle.com)
[![Languages](https://img.shields.io/badge/Languages-3-orange)](https://github.com)

---

## 📌 What is this?

A **voice-only** web app for non-literate farmers. Speak a question in Hindi, English, or Swahili – get a spoken answer about weather, pests, fertilizer, or crop prices.

**The Problem:** 500M farmers can't read text-based apps → 40% lower yields  
**The Solution:** No reading, no typing – just speaking and listening

---

## ✨ Features

| Feature | Status |
|---------|--------|
| 🎤 Voice Input | ✅ |
| 🔊 Voice Output | ✅ |
| ☀️ Weather | ✅ |
| 🐛 Pest Solutions | ✅ |
| 🌱 Fertilizer Advice | ✅ |
| 💰 Market Prices | ✅ |
| 🔁 Repeat | ✅ |
| 🐌 Slow Mode | ✅ |
| 🌍 3 Languages | ✅ |

**Supported:** English, Hindi, Swahili

---

## 🏗️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5/CSS3 | UI & styling |
| JavaScript | Logic |
| Web Speech API | Voice input/output |
| Local JSON DB | Knowledge base |

**No dependencies. No backend. Works offline.**

---

## 📥 How to Run

### 1. Download
```bash
git clone https://github.com/yourusername/farmer-voice-assistant.git
cd farmer-voice-assistant
```

### 2. Start local server
```bash
python -m http.server 8000
```

### 3. Open browser
```text
http://localhost:8000
```

### 4. Allow microphone → Click mic → Speak

---

## 🎮 How to Use

| You Say | Assistant Responds |
|---------|-------------------|
| "What is the weather?" | Today's forecast |
| "Small black insects" | Pest solution |
| "Fertilizer for rice" | Dosage advice |
| "Price of wheat" | Market rate |

Quick buttons: Weather, Pests, Fertilizer, Prices, Repeat, Slow Mode, Language, Help

**Shortcut:** Press Spacebar for microphone

---

## 🌐 Languages

| Language | Code | Regions |
|----------|------|---------|
| English | en-US | Global |
| Hindi | hi-IN | North/Central India |
| Swahili | sw-KE | East Africa |

---

## 📁 Project Structure

```text
farmer-voice-assistant/
├── index.html     # Main app (single file)
├── README.md      # This file
└── LICENSE        # Apache 2.0
```

---

## 🔧 How It Works

```text
User speaks → Web Speech API → Keyword matching → Local database → Speech output
```

Intelligent keyword matching finds best answer from 50+ farming entries.

---

## 📊 Impact

| Metric | Value |
|--------|-------|
| Target users | 500M farmers |
| Yield increase | +40% (World Bank) |
| Income increase | +$400/year |
| Deployment cost | $0(web)/$15 (offline) |

---

## 📄 License

Apache 2.0 – free for commercial use

---

## 🙏 Built For

Gemma 4 Good Hackathon – Digital Equity & Inclusivity Track

---

## ⭐ Quick Start

```bash
git clone https://github.com/yourusername/farmer-voice-assistant.git
cd farmer-voice-assistant
python -m http.server 8000

# Open http://localhost:8000
```

Built with 💚 for farmers who can't read

Giving a voice to 500 million farmers.