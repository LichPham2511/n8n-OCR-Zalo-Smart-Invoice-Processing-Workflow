# n8n-OCR-Zalo Smart Invoice Processing Workflow

## Overview
**n8n Zalo OCR** is a fully automated workflow built on **n8n** to process invoices, shipping labels, and receipts sent via Zalo.It uses **Tesseract.js** for OCR and **Google Gemini** for AI-powered parsing to accurately capture key details and store them directly into **Google Sheets**, ensuring centralized, error-free, and real-time record management.

<img width="1191" height="569" alt="image" src="https://github.com/user-attachments/assets/4e64fd46-819c-4dce-842c-c422977e51b9" />

## Key Features

### Multi-format OCR Support
- E-commerce invoices (Shopee, Lazada, Tiki…)
- Shipping receipts (GHN, GHTK, ViettelPost…)
- Restaurant/store receipts
- Payment vouchers
- Bank transfer confirmations

### AI-Powered Intelligence
- **Google Gemini 2.0 Flash** for intelligent text analysis
- **Tesseract OCR** with Vietnamese + English support
- Automatic recognition & extraction:
  - 📅 Date & Time  
  - 💰 Total Amount  
  - 📦 Order Code  
  - 🚚 Tracking Number  
  - 🏢 Shipping Company  
  - 📝 Product Description  
  - 🔢 Quantity, Size, Weight  

## Technology Stack
| Technology | Purpose |
|------------|---------|
| [n8n](https://n8n.io/) | Workflow automation |
| [Zalo API](https://github.com/anhtai1907/n8n-nodes-zalo) | Messaging integration |
| [Tesseract.js](https://tesseract.projectnaptha.com/) | OCR text recognition |
| [Google Gemini AI](https://ai.google/) | AI data extraction |
| [Google Sheets API](https://developers.google.com/sheets/api) | Data storage |

## 📧 Support
For support or collaboration, please contact: **lichpham1125@gmail.com**
