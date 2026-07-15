<div align="center">

# 🛡️ SecureLens AI

### Privacy-First On-Device AI Security Assistant

Detect phishing, scam messages, malicious URLs and suspicious content **entirely inside your browser**.

No cloud AI. No data leaves your device.

---

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite)
![Transformers.js](https://img.shields.io/badge/Transformers.js-HuggingFace-yellow)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-Web-blue)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

# Demo

🎥 **Watch the Demo**

https://youtu.be/hbaZc8dMOoE

---

# Screenshots

## Home

![Home](screenshots/home.png)

## Detection

![Detection](screenshots/detection.png)

---

# Problem

Millions of users receive phishing emails, fake job offers, scam SMS, malicious QR codes, and fraudulent payment links.

Most AI tools send sensitive data to cloud servers.

This creates privacy concerns.

---

# Solution

SecureLens AI performs AI-powered security analysis directly inside the browser.

The core AI model runs locally using ONNX Runtime Web.

No user text is sent to cloud AI services.

---

# Features

- Detect phishing messages
- Detect scam SMS
- Detect malicious URLs
- Explain why content is suspicious
- Risk score
- Plain-language recommendations
- Browser-based AI
- Privacy-first
- Open source

---

# Architecture

```text
User Input
      │
      ▼
React UI
      │
      ▼
Transformers.js
      │
      ▼
ONNX Runtime Web
      │
      ▼
Local AI Model
      │
      ▼
Risk Engine
      │
      ▼
Results
```

---

# Tech Stack

- React
- Vite
- JavaScript
- Transformers.js
- ONNX Runtime Web
- Tailwind CSS

---

# Installation

```bash
git clone https://github.com/Astuti5/SecureLens-AI.git

cd SecureLens-AI

npm install

npm run dev
```

---

# Folder Structure

```text
src
 ├── components
 ├── lib
 ├── data
 ├── App.jsx
 └── main.jsx
```

---

# On-Device AI

The AI model runs completely inside the browser.

No cloud inference is used for the primary security analysis.

---

# Roadmap

- Screenshot analysis
- QR code detection
- Browser extension
- APK analysis
- Offline multilingual support

---

# License

MIT License

---

# Author

**Astuti Kumari**

GitHub

https://github.com/Astuti5
