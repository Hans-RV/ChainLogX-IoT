# 📡 ChainLogX-IoT

**ChainLogX-IoT** is a decentralized, tamper-proof IoT data logging system that combines **ESP32-based sensing**, **cloud storage**, **blockchain immutability**, and **AI-powered anomaly analysis** using **Groq API**.

It ensures **data integrity**, **real-time monitoring**, and **intelligent feedback** whenever abnormal sensor behavior is detected.

---

## 🔍 Overview

ChainLogX-IoT uses a hybrid architecture:

- **ESP32** collects real-time sensor data
- **Cloud (Firebase)** stores and visualizes data
- **Blockchain (Polygon)** stores immutable SHA-256 hashes
- **Groq AI** analyzes sudden sensor changes and provides insights

Any modification to cloud data is immediately detected via **hash mismatch with on-chain records**.

---

## 🧠 Key Features

- ✅ Tamper-proof IoT data logging
- 🔐 Blockchain-based hash verification
- ⚡ Real-time sensor monitoring
- 🚨 Sudden-change anomaly detection
- 🤖 AI-powered feedback using Groq API
- 📊 Interactive dashboard with alerts
- 🌐 Scalable cloud architecture

---

## 🛠 Tech Stack

### Hardware
- ESP32
- IoT Sensors (Temperature, Humidity, Pressure, etc.)

### Software
- **Firmware:** Arduino C++
- **Cloud:** Firebase (Realtime DB / Firestore)
- **Blockchain:** Solidity Smart Contract
- **Network:** Polygon Testnet
- **Web3 Integration:** Web3.py
- **AI Engine:** Groq API
- **Backend:** Python / Cloud Functions
- **Dashboard:** React / Web App

---

## 🔄 System Workflow

1. ESP32 reads sensor values
2. Sensor data is uploaded to Firebase
3. SHA-256 hash of data is generated
4. Hash is recorded on blockchain
5. Backend monitors data for sudden changes
6. On anomaly detection:
   - Groq API called
   - AI feedback generated
7. Dashboard displays:
   - Sensor values
   - Blockchain verification status
   - AI insights & alerts

---

## 🚨 AI-Powered Sudden Change Detection

### Detection Methods
- Threshold-based deviation
- Rate-of-change analysis
- Rolling average deviation

### AI Feedback Includes
- Possible cause of anomaly
- Risk level (Low / Medium / High)
- Recommended action
