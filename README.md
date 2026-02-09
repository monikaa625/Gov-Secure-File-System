# Gov-Secure-File-System
Real-time file integrity monitoring system using Blockchain and AES Encryption for secure document storage
# 🛡️ Government-Grade Secure File System

## 📌 Project Overview
A real-time cybersecurity tool designed to ensure **Data Integrity** and **Confidentiality** for sensitive government documents. It combines **AES-256 Encryption** with a custom **Blockchain** to create a tamper-proof audit trail.

## 🚀 Key Features
* **Real-Time Monitoring:** Automatically detects file creation or modification using `watchdog`.
* **AES Encryption:** Instantly locks files using the `cryptography` library (Confidentiality).
* **Blockchain Ledger:** Logs every file change in an immutable chain (Integrity).
* **Tamper Detection:** Forensic audit tool that alerts if a file's hash does not match the blockchain record.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `watchdog`, `cryptography`, `hashlib`, `json`

## ⚙️ How to Run
1.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2.  Run the sentinel script:
    ```bash
    python main.py
    ```
3.  The system will create a `secure_docs` folder. Any file dropped there is automatically secured.

## 📸 Proof of Concept
(Upload your screenshot of the terminal output here)
