# 💸 FINFLOW — GST Register & Finance Manager

A smart, all-in-one GST-compliant finance management web app built during the **Wave Hackathon** by a team of CSE students from KLS VDIT College.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Built with Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-red)
![Hackathon](https://img.shields.io/badge/Wave-Hackathon-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Language](https://img.shields.io/badge/Language-English%20%7C%20Kannada-purple)

---

## 📌 About the Project

**FINFLOW** is a GST Sales & Purchase Register application designed to help small businesses manage their finances and GST compliance — all in one place.

- OCR-based invoice scanning  
- Auto-generates GSTR-1 & GSTR-3B reports  
- Clean, interactive dashboard  

Built as part of the **Wave Hackathon** by students from  
*KLS Vishwanathrao Deshpande Institute of Technology (VDIT), Haliyal*

---

## ✨ Features

### 🧾 Invoice Management
- OCR Invoice Scanning — Upload PDF/image invoices and auto-read details  
- Smart Invoice Detection — Auto classify Sales vs Purchase  
- Invoice Validation — Detect fake GSTIN, illegal GST usage  
- Manual Entry — Add invoices manually  

### 📊 Registers & Dashboard
- Purchase Register — Track Input Tax Credit (ITC)  
- Sales Register — Track Output Tax  
- Live Dashboard — GST breakdown, profit, net tax  

### 📑 GST Reports
- GSTR-1 — B2B, B2C, HSN summary  
- GSTR-3B — Monthly GST summary  
- GSTR-2A / 2B — ITC reconciliation  

### 🔐 Security & Users
- Multi-user Authentication  
- Per-user JSON Storage  
- Password Change Support  

### 🌐 Bilingual Support
- English  
- Kannada (ಕನ್ನಡ)

---

## 🛠 Tech Stack

| Technology | Usage |
|----------|------|
| Python | Core backend logic, OCR parsing, GST calculations |
| Streamlit | Frontend UI & dashboard |
| Pytesseract | OCR text extraction |
| Pandas | Data processing |
| PyMuPDF / pdf2image | PDF handling |
| JSON | Data storage |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Tesseract OCR installed

### Installation

1. Clone the repository
```bash
git clone https://github.com/Rajendra7250/FINFLOW-FINAL.git
cd FINFLOW-FINAL
