# 🛡️ Phishing Email Detection System

## 📌 Project Overview
This project is a **Machine Learning–based web application** designed to detect whether an email is **Phishing or Legitimate** by analyzing email content using **Natural Language Processing (NLP)** techniques.

Phishing is one of the most common cybersecurity threats where attackers send fraudulent emails to trick users into revealing sensitive information such as passwords, banking details, or personal data.

The system analyzes email text and classifies it as:
* ✔ **Legitimate Email**
* ❌ **Phishing Email**

The application integrates a **trained machine learning model** with a **Flask web application** to provide real-time phishing detection.

---

## 🛠 Tools & Technologies

### Backend
* **Python**
* **Flask**
* **Scikit-learn**
* **Pandas**
* **NumPy**

### Frontend
* **HTML**
* **CSS**
* **JavaScript**

### Database
* **SQLite**

### Machine Learning
* **Natural Language Processing (NLP)**
* **Text Feature Extraction**
* **Classification Model**

---

## ✨ Key Features
* **User Authentication System** (Login & Signup)
* **Email Phishing Detection** using Machine Learning
* **Email Content Analysis** using NLP techniques
* **Prediction Results** displayed with clear classification
* **Email Analysis Logs** to track previous detections
* **Model Retraining Functionality**
* **Simple and User-Friendly Web Interface**

---

## 🧠 Machine Learning Workflow
The system follows a structured workflow to detect phishing emails:

### Email Input
* User enters the email text into the system for analysis.

### Text Preprocessing
* The email content is cleaned and processed using NLP techniques.

### Feature Extraction
* Important features are extracted using a feature engineering model.

### Model Prediction
* The trained machine learning model analyzes the extracted features.

### Result Display
* The system predicts whether the email is **phishing or legitimate** and displays the result on the dashboard.

---

## ⚙️ Installation
### Clone the Repository
```bash
git clone https://github.com/Vasantlohar0504/phishing-email-detection.git
cd phishing-email-detection
```

### Create Virtual Environment
```bash
python -m venv venv
```

Activate the environment:
**Windows**
```
venv\Scripts\activate
```

**Mac / Linux**
```
source venv/bin/activate
```
### Install Dependencies
```
pip install -r requirements.txt
```

---

## ▶️ Run the Application
Start the Flask server:
```
python app.py
```

Open your browser and visit:
```
http://127.0.0.1:5000
```

---

## 📊 Example Usage
### Input Email

```
Dear user,
Your account has been suspended.
Click here to verify your account immediately.
```

### Prediction Result

```
⚠️ Phishing Email Detected
```

---

## 🚀 Project Outcome
This project demonstrates how **Machine Learning and NLP techniques** can be used to improve email security by automatically identifying phishing emails.

The system helps users:
* Detect suspicious emails
* Improve cybersecurity awareness
* Prevent phishing attacks
* Analyze email content efficiently



## 👨‍💻 Author
**Vasant Lohar**
Data Analyst | Data Science Enthusiast

If you want, I can also show you **one small trick used by top GitHub portfolios** that will make this project look **2× more professional to recruiters** (takes only **2 minutes to add**).
