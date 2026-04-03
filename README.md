
# 🛡️ Phishing Email Detection System

![Python](https://img.shields.io/badge/Python-Backend-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![NLP](https://img.shields.io/badge/NLP-Text%20Processing-green)
![License](https://img.shields.io/badge/License-MIT-green)


> A full-stack **Flask-based cybersecurity application** that detects phishing emails using Machine Learning, provides detailed analysis, and generates professional PDF reports with verification.

---

## 🚀 Overview

This project is an intelligent **email security system** designed to identify phishing attempts by analyzing email content, URLs, and attachments.

It combines:

* 🧠 Machine Learning
* 🌐 Web Application (Flask)
* 📊 Data Storage & Retraining
* 📄 Automated Report Generation

---

## ✨ Features

### 🔐 Authentication System

* User Signup & Login
* Secure password hashing
* Google OAuth login integration
* Role-based access (Admin / User)
* Auto-generated avatars

---

### 🧠 Email Analysis

* Detects **Phishing vs Legitimate Emails**
* Extracts:

  * Sender domain
  * URLs from content
  * Attachments
* Provides:

  * Confidence score
  * AI-based explanation

---

### 📊 Data Handling

* Stores results in:

  * SQLite Database
  * CSV dataset (`email_data.csv`)
* Automatic dataset update
* Model auto-retraining after analysis

---

### 📄 PDF Report Generation

* Professional report with:

  * Report ID & timestamp
  * Detection result & risk level
  * Email details & URLs
  * Full email content
  * AI explanation
  * QR Code verification
* Watermark & styled layout

---

### 👨‍💼 Admin Dashboard

* View all users
* Manage roles
* Monitor analyzed emails
* Delete users/emails (single & bulk)

---

## 🛠️ Tech Stack

| Category         | Technology                   |
| ---------------- | ---------------------------- |
| Backend          | Flask (Python)               |
| Frontend         | HTML, CSS, Jinja2            |
| Database         | SQLite                       |
| Machine Learning | Scikit-learn (Pickle Model)  |
| PDF Engine       | ReportLab                    |
| Image Processing | Pillow (PIL)                 |
| Data Processing  | Pandas                       |
| Authentication   | Flask Session + Google OAuth |

---

## 📁 Project Structure

```id="proj-struct"
app/
│
├── models/
│   ├── user.py
│   └── email.py
│
├── routes/
│   ├── auth.py        # Authentication & Google Login
│   ├── main.py        # Core logic (analysis, PDF, admin)
│   ├── admin.py
│   └── analysis.py
│
├── services/
│   └── ml_service.py  # ML prediction & retraining
│
├── utils/
│
├── static/
│   ├── images/
│   └── assets/
│
├── templates/
│   ├── admin/
│   │   └── dashboard.html
│   ├── login.html
│   ├── signup.html
│   ├── index.html
│   ├── results.html
│   └── ...
│
├── extensions.py
└── __init__.py
│
├── config.py
├── run.py
├── requirements.txt
├── model_bundle.pkl
├── email_data.csv
└── database.db
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/phishing-email-detector.git
cd phishing-email-detector
```

---

### 2️⃣ Setup Virtual Environment

```bash
python -m venv venv
```

Activate:

```bash
# Windows
venv\Scripts\activate

# Linux / Mac
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run Application

```bash
python run.py
```

---

### 🌐 Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🧪 Usage Flow

1. Login / Signup
2. Enter email details:

   * Email address
   * Email body
   * URLs (optional)
   * Attachment (optional)
3. Click **Analyze**
4. View:

   * Detection result
   * Confidence score
   * Risk level
5. Download PDF report

---

## 🤖 Machine Learning Pipeline

* Model loaded from: `model_bundle.pkl`
* Core functions:

  * `ml_service.predict(text)`
  * `ml_service.explain_prediction(text)`
* Features used:

  * Email content
  * Domain
  * URLs
  * Attachments
* Continuous learning:

  * New data appended to CSV
  * Auto retraining triggered

---

## 🔐 Security Features

* Password hashing (`werkzeug.security`)
* Session-based authentication
* Role-based access control
* Admin route protection
* Input validation & sanitization

---


## 📈 Future Enhancements

* 🚀 REST API for external integration
* ☁️ Cloud deployment (AWS / Render)
* 📊 Advanced analytics dashboard
* 🔐 JWT authentication
* ⚡ Async ML processing
* 📧 Real-time email scanning

---



## 📜 License

This project is licensed under the MIT License.

# 👨‍💻 Author

**Vasant Lohar**
Data Analyst | Data Science Enthusiast
