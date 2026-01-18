# 📡 ChainLogX-IoT
A decentralized, tamper-proof IoT data logging system powered by **ESP32**, Cloud Storage, and Blockchain.

---

## 🔍 Overview
**ChainLog IoT** securely captures and verifies sensor data using a hybrid architecture:
- **ESP32** for real-time IoT sensing and data transmission  
- **Cloud Database** for scalable storage and monitoring  
- **Blockchain** for immutable hash verification (tamper-proof logs)  

Any modification in cloud data is immediately identified by comparing it with the original on-chain hash.

---

## 🛠 Tech Stack
- **Hardware:** ESP32, IoT Sensors  
- **Programming:** C++ (Arduino)  
- **Cloud:** Firebase 
- **Blockchain:** Solidity Smart Contract (Polygon Testnet)
- **Web3 Integration:** Web3.py

---

## 🔄 Workflow
1. ESP32 reads sensor values  
2. Sensor data is uploaded to Cloud Storage  
3. A SHA-256 hash of the data is generated  
4. Hash is recorded on Blockchain via smart contract  
5. Any data change = hash mismatch → tampering detected  

---

## 🎯 Use Cases
- Industrial machine data monitoring  
- Supply chain temperature verification  
- Agriculture & environmental logging  
- Research-grade data integrity systems
