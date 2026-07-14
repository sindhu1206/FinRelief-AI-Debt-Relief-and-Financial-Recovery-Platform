# FinRelief-AI-Debt-Relief-and-Financial-Recovery-Platform
# 🏦 FinRelief AI  
### AI Powered Debt Relief & Financial Recovery Platform

FinRelief AI is an AI-powered web application that helps users manage debt, monitor financial health, receive personalized financial recommendations, generate lender negotiation letters, and download professional financial reports.

---

## 📌 Project Overview

Managing debt can be challenging, especially without personalized financial guidance. **FinRelief AI** leverages Artificial Intelligence to analyze a user's financial data and provide intelligent recommendations for improving financial stability.

The application also generates professional debt negotiation letters and downloadable PDF reports, making it easier for users to communicate with lenders and monitor their financial progress.

---

## ✨ Features

- 🔐 Secure User Registration & Login
- 🔒 Password Hashing using bcrypt
- 🔑 Forgot Password Functionality
- 📊 Financial Dashboard
- 💰 Financial Health Score
- 📈 Debt vs Income Visualization
- 🤖 AI-Powered Financial Recommendations
- 💬 Ask AI Chatbot
- 📝 AI Negotiation Letter Generator
- 📄 Download Financial Report as PDF
- 📚 Financial History Tracking
- 📱 Responsive User Interface

---

## 🖼️ Application Workflow

```text
Login / Register
        │
        ▼
   Home Page
        │
        ▼
Financial Details Form
        │
        ▼
    Dashboard
        │
        ▼
AI Recommendation
        │
        ▼
     Ask AI
        │
        ▼
Generate Negotiation Letter
        │
        ▼
Download PDF Report
        │
        ▼
      History
```

---

# 🛠️ Tech Stack

## Frontend

- React.js
- HTML5
- CSS3
- JavaScript
- Axios
- React Router
- Chart.js

## Backend

- FastAPI
- Python

## Database

- SQLite
- SQLAlchemy ORM

## AI

- Google Gemini API

## Security

- bcrypt Password Hashing

---

# 📊 Dashboard Includes

- 💰 Total Debt
- 💵 Monthly Income
- 📅 Monthly EMI
- ⏳ Remaining EMI Months
- ❤️ Financial Health Score
- ⚠️ Risk Status
- 📈 Debt vs Income Chart

---

# 🤖 AI Features

## 💡 AI Recommendation

Analyzes financial information and provides personalized debt management suggestions.

---

## 💬 Ask AI

Users can ask financial questions and receive concise AI-generated responses.

**Example**

```text
How can I reduce my debt?
```

---

## 📝 Negotiation Letter

Automatically generates a professional debt negotiation letter for lenders based on the user's financial condition.

---

# 📄 PDF Report

The downloadable report includes:

- Financial Summary
- Financial Health Score
- AI Recommendation
- AI Negotiation Letter

---

# 🔒 Security Features

- Secure Login
- Password Encryption using bcrypt
- Strong Password Validation
- Email Validation
- Password Reset

---

# 🚀 Future Enhancements

- Loan Eligibility Prediction
- Credit Score Analysis
- Email OTP Verification
- Budget Planning
- Expense Tracking
- Multi-language Support
- Cloud Deployment
- Admin Dashboard

---

# 📂 Project Structure

```text
AI-Debt-Relief/
│
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── requirements.txt
│   └── services/
│
├── frontend/
│   ├── src/
│   ├── assets/
│   ├── components/
│   ├── package.json
│   └── vite.config.js
│
├── README.md
└── .gitignore
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/vidyarayapati/FinRelief-AI.git
cd FinRelief-AI
```

---

## 2️⃣ Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux / macOS
source venv/bin/activate

pip install -r requirements.txt

uvicorn main:app --reload
```

The backend will run on:

```text
http://127.0.0.1:8000
```

---

## 3️⃣ Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

The frontend will run on:

```text
http://localhost:5173
```

---

# 📸 Application Screens

> Add screenshots here after uploading them.

| Login | Dashboard |
|-------|-----------|
| ![Login](images/login.png) | ![Dashboard](images/dashboard.png) |

| AI Recommendation | Negotiation Letter |
|-------------------|--------------------|
| ![AI](images/ai.png) | ![Letter](images/letter.png) |

---

# 👥 Contributors

- **Sri Sindhu Pondraj**
- **Vidya Rayapati**

---

# 📄 License

This project is developed for educational and academic purposes.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
