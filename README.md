<h1 align="center">S Dinesh</h1>

<p align="center">
  🧠 97.2% Accurate Oral Cancer Detection (DenseNet201 + CBAM)<br/>
  📡 Real-time RFID System (&lt;800ms, ESP32 → Google Sheets)<br/>
  ⚙️ Built FinTech + E-commerce end-to-end systems
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=DINESH2841&color=0e75b6&style=flat" alt="Profile Views" />
  <a href="https://linkedin.com/in/sevinnidinesh"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin" /></a>
  <a href="https://dineshsevinni.me/"><img src="https://img.shields.io/badge/Portfolio-Visit-252525?style=flat&logo=google-chrome" /></a>
  <a href="https://github.com/DINESH2841/Oral-Cancer-Densenet"><img src="https://img.shields.io/badge/Accuracy-97.2%25-brightgreen?style=flat" /></a>
  <a href="https://github.com/DINESH2841/Oral-Cancer-Densenet"><img src="https://img.shields.io/badge/AUC-0.997-brightgreen?style=flat" /></a>
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/DINESH2841/Oral-Cancer-Densenet/main/results/confusion_matrix.png" width="420" alt="Oral Cancer Model - Confusion Matrix" />
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/DINESH2841/Oral-Cancer-Densenet/main/results/roc_curve.png" width="420" alt="ROC Curve - AUC 0.997" />
</p>

<p align="center"><i>Real outputs from the Oral Cancer Detection model — not demo screenshots</i></p>

---

## 🏆 Projects

### 🥇 [Oral Cancer Detection — DenseNet201 + CBAM Attention](https://github.com/DINESH2841/Oral-Cancer-Densenet)

**What I built:**
- DenseNet201 backbone with CBAM (Spatial + Channel Attention)
- Trained on 13,202 images (balanced Cancer / Non-Cancer)
- Benchmarked against EfficientNetB0 and MobileNetV3

**Results:**
- Accuracy: **97.2%** | Recall: **98.0%** | AUC: **0.997**
- False Negative rate: **1.83%** (121 missed out of 6,601 cancer samples)
- Outperformed EfficientNetB0 by **2.4%** on recall

```bash
python predict.py --image test.jpg
# CANCER DETECTED (Confidence: 98.7%)
```

---

### 🥈 [RFID Attendance System — ESP32 + Google Sheets](https://github.com/DINESH2841/RFID-Based-ESP-Integrated-with-Google-Sheets)

**What I built:**
- ESP32 + RC522 RFID reader over SPI protocol
- HTTP POST to Google Apps Script webhook to Google Sheets
- Web dashboard with live filtering, CSV export, admin controls

**Results:**
- Cloud sync latency: **<800ms** card tap to Sheets
- Offline buffering via EEPROM — no data loss on WiFi drop
- Supports **50+ registered cards** via SPIFFS JSON config

---

### 🥉 [Bank Statement Analyzer](https://github.com/DINESH2841/bank_analyzer_app)

**What I built:**
- Multi-bank parser with 20+ transaction categories
- Monthly Average Balance engine with daily gap-filling
- Fraud flag detection + visual dashboard

---

### ⚙️ [Ras Currys — E-Commerce Platform](https://github.com/DINESH2841/rascurrys-showcase)

**What I built:**
- Next.js + Node.js + MongoDB + Redis full-stack delivery app
- WhatsApp order automation + HDFC payment gateway
- Zone-based delivery pricing + fraud detection on orders

---

## 🎯 What I'm Currently Building

- 💼 **[Job Tracker](https://github.com/DINESH2841/Job_Tracker)** — Application pipeline tracker with status stages and analytics
- 🏦 **[Bank Statement Analyzer](https://github.com/DINESH2841/bank_analyzer_app)** — FinTech data engine: fraud flags, MAB, category classification
- 🍛 **[Ras Currys](https://github.com/DINESH2841/rascurrys-showcase)** — WhatsApp orders, HDFC payments, zone-based delivery

---

## 🛠 Tech Stack

| Domain | Technologies |
|--------|-------------|
| **ML / AI** | Python, TensorFlow, Keras, OpenCV, DenseNet201, CBAM |
| **IoT** | ESP32, RC522 RFID, Arduino IDE, SPI |
| **Backend** | Node.js, Express, Redis, MongoDB, PostgreSQL |
| **Frontend** | Next.js, React, TypeScript, Tailwind CSS |
| **Cloud** | Vercel, Render, Google Sheets API |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dinesh2841&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=dinesh2841&layout=compact&theme=tokyonight&hide_border=true" height="150" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=DINESH2841&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center"><i>"Don't just write code. Build systems."</i></p>

---
