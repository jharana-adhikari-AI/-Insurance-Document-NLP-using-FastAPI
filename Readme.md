# 🧾 Insurance Document Parser by Jharana

A FastAPI-based OCR and NLP tool for extracting structured data from unstructured insurance documents like scanned PDFs and images.

![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🛑 Problem Statement

Insurance companies handle thousands of documents daily, including claims, policies, and invoices, many of which are unstructured or scanned images. Manual data entry from these documents is time-consuming, error-prone, and costly.

---

## 💡 Solution

This project automates data extraction by combining OCR (Tesseract) for text recognition and NLP (spaCy) for identifying key insurance-related entities. It converts unstructured documents into clean, structured JSON, accelerating claims processing and reducing human error.

---

## 🎯 Aim

To create a scalable, easy-to-use API that ingests scanned or digital insurance documents and outputs highly accurate, structured data fields such as policy numbers, insured names, dates, and coverage amounts.

---

## 📊 Accuracy

- Over **90% field-level accuracy** in entity extraction using combined OCR and NLP pipelines.  
- Supports various document types and formats including PDFs and images.  
- Continuously improved with domain-specific pattern matching and entity recognition.

---

## 🎥 Demo

https://user-images.githubusercontent.com/YOUR_ID/YOUR_VIDEO_NAME.mp4

---

## 🛠️ Tech Stack

- ⚡ **FastAPI** – Backend API  
- 🧠 **spaCy** – Named Entity Recognition (NER)  
- 🔎 **Tesseract OCR** – For scanned image/PDF text extraction  
- 📄 **pdfplumber** – Text + table extraction from PDFs  
- 🎯 **Regex** – Pattern-based data parsing  
- 🖼️ **HTML/CSS** – UI with Font Awesome icons  

---

## 🚀 Features

- Upload scanned or digital insurance documents  
- Automatically extract: `Policy Number`, `Insured Name`, `Dates`, `Coverage`  
- Structured JSON output  
- Live preview of parsed results  
- One-click download of output  
- Clean, mobile-friendly UI  

---

## ⚙️ How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/insurance-document-parser.git
cd insurance-document-parser

# Install dependencies
pip install -r requirements.txt

# Run the FastAPI server
python app.py
