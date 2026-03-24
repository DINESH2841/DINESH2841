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

## ⚡ Quick Snapshot

- 🧠 **ML Model:** 97.2% accuracy on 13k+ images (DenseNet201 + CBAM Attention)
- 📡 **IoT System:** Real-time RFID to Google Sheets (<800ms, ESP32 + SPI)
- 💳 **FinTech:** Multi-bank statement parser with fraud detection & MAB engine
- 🛒 **E-commerce:** Full-stack delivery platform (WhatsApp orders + HDFC payments)

---

## 🏆 Projects

### 🥇 [Oral Cancer Detection — DenseNet201 + CBAM Attention](https://github.com/DINESH2841/Oral-Cancer-Densenet)

<p align="center">
  <img src="https://raw.githubusercontent.com/DINESH2841/Oral-Cancer-Densenet/main/results/confusion_matrix.png" width="420" alt="Confusion Matrix" />
  <img src="https://raw.githubusercontent.com/DINESH2841/Oral-Cancer-Densenet/main/results/roc_curve.png" width="420" alt="ROC Curve AUC 0.997" />
</p>

**What I built:**
- DenseNet201 backbone with CBAM (Spatial + Channel Attention)
- Trained on 13,202 images (balanced Cancer / Non-Cancer)
- Benchmarked against EfficientNetB0 and MobileNetV3

**Results:**
- Accuracy: **97.2%** | Recall: **98.0%** | AUC: **0.997**
- False Negative rate: **1.83%** (121 missed out of 6,601 cancer samples)
- Outperformed EfficientNetB0 by **2.4%** on recall

**Why it matters:** Missing cancer (false negatives) can be life-threatening. The model was explicitly optimized for high recall (98%) — not just accuracy.

```bash
python predict.py --image test.jpg
```

---

### 🥈 [RFID Attendance System — ESP32 + Google Sheets](https://github.com/DINESH2841/RFID-Based-ESP-Integrated-with-Google-Sheets)

<p align="center">
  <img src="https://raw.githubusercontent.com/DINESH2841/RFID-Based-ESP-Integrated-with-Google-Sheets/main/images/setup.jpg" width="420" alt="Hardware Setup" />
  <img src="https://raw.githubusercontent.com/DINESH2841/RFID-Based-ESP-Integrated-with-Google-Sheets/main/images/output.png" width="420" alt="Google Sheets Live Output" />
</p>

**What I built:**
- ESP32 + RC522 RFID reader over SPI protocol
- HTTP POST to Google Apps Script webhook to Google Sheets
- Web dashboard with live filtering, CSV export, admin controls

**Results:**
- Cloud sync latency: **<800ms** from card tap to Google Sheets
- Offline buffering via EEPROM — **zero data loss** on WiFi drop
- Supports **50+ registered cards** via SPIFFS JSON config

---

### 🥉 [Bank Statement Analyzer](https://github.com/DINESH2841/bank_analyzer_app)

**What I built:**
- Multi-bank statement parser with **20+ transaction categories**
- Monthly Average Balance engine with daily gap-filling logic
- Fraud flag detection + visual analytics dashboard

**Results:**
- Processes **10,000+ transactions** per statement upload
- Detects bank charges, EMIs, and anomalous debits automatically
- MAB calculated with gap-filling across irregular statement windows

---

### ⚙️ [Ras Currys — E-Commerce Platform](https://github.com/DINESH2841/rascurrys-showcase)

**What I built:**
- Next.js + Node.js + MongoDB + Redis full-stack delivery app
- WhatsApp order automation + HDFC payment gateway integration
- Zone-based delivery pricing + order-level fraud detection

**Results:**
- Handles concurrent orders with fraud scoring on every transaction
- Sub-second product API response with Redis caching
- Automated WhatsApp order confirmations with real-time status updates

---

## 🎯 What I'm Currently Building

- 💼 **[Job Tracker](https://github.com/DINESH2841/Job_Tracker)** — Application pipeline with status stages and analytics
- 🏦 **[Bank Statement Analyzer](https://github.com/DINESH2841/bank_analyzer_app)** — FinTech data engine: fraud flags, MAB, 20+ categories
- 🍛 **[Ras Currys](https://github.com/DINESH2841/rascurrys-showcase)** — WhatsApp orders, HDFC payments, zone-based delivery

---

## 🛠 Tech Stack

| Domain | Technologies |
|--------|-------------|
| **ML / AI** | Python, TensorFlow, Keras, OpenCV, DenseNet201, CBAM |
| **IoT** | ESP32, RC522 RFID, Arduino IDE, SPI Protocol |
| **Backend** | Node.js, Express, Redis, MongoDB, PostgreSQL |
| **Frontend** | Next.js, React, TypeScript, Tailwind CSS |
| **Cloud** | Vercel, Render, Google Sheets API |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dinesh2841&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="140" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=dinesh2841&layout=compact&theme=tokyonight&hide_border=true" height="140" />
</p>

---

<p align="center"><i>"Don't just write code. Build systems."</i></p>
