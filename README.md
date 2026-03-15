
# 🛡️ Phishing Email Detection System

![Python](https://img.shields.io/badge/Python-Backend-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![NLP](https://img.shields.io/badge/NLP-Text%20Processing-green)
![License](https://img.shields.io/badge/License-MIT-green)

A **Machine Learning–powered web application** that detects whether an email is **Phishing** or **Legitimate**.
The system analyzes **email content, URLs, and attachments** using **Natural Language Processing (NLP)** and machine learning models to help users identify phishing attacks and improve email security.

---

# 📊 Project Overview

The **Phishing Email Detection System** demonstrates how **Artificial Intelligence and Machine Learning** can enhance cybersecurity by identifying malicious emails.

The system allows users to:

✔ Analyze suspicious emails

✔ Detect phishing links and malicious attachments

✔ Get real-time ML predictions

✔ Track previously analyzed emails

This project highlights the use of **AI for cybersecurity applications**.

---

# 🛠 Tools & Technologies
| Technology                | Purpose                                         |
| ------------------------- | ----------------------------------------------- |
| **Python**                | Backend programming & ML model development      |
| **Flask**                 | Web application framework                       |
| **Scikit-learn**          | Machine learning model training                 |
| **Pandas & NumPy**        | Data preprocessing & analysis                   |
| **SQLite**                | Database for storing logs and users             |
| **HTML, CSS, JavaScript** | Frontend user interface                         |
| **NLP Techniques**        | Email text preprocessing and feature extraction |
| **GitHub**                | Version control and project hosting             |

---

# 📂 Dataset

The dataset used in this project contains labeled emails used to train the phishing detection model.

### Dataset Features
* **Email Content (Text)**
* **URLs contained in emails**
* **Attachments**
* **Email Labels**
  * Phishing
  * Legitimate

This dataset helps train the model to recognize **patterns commonly used in phishing attacks**.

---

# 🔎 Machine Learning Workflow

The system follows this workflow to detect phishing emails:

1️⃣ **Email Input**
User enters email content, URLs, or attachments.

2️⃣ **Text Preprocessing**
Email text is cleaned using NLP techniques such as:
* Stopword removal
* Tokenization
* Text normalization

3️⃣ **Feature Extraction**
Important features are extracted from:
* Email text
* URLs
* Attachments

4️⃣ **Model Prediction**
The trained ML model predicts whether the email is:
* **Phishing**
* **Legitimate**

5️⃣ **Result Display**
Prediction results are displayed on the dashboard with detected suspicious elements.

---

# 📈 Key Features
* 🔐 **User Authentication** (Login & Signup)
* 🤖 **Machine Learning–based phishing detection**
* 🔗 **URL Analysis** for detecting malicious links
* 📎 **Attachment Analysis** for harmful files
* 📊 **Prediction Dashboard** showing analysis results
* 🗂 **Email Analysis Logs**
* 🔄 **Model Retraining Support**
* 🎨 **Simple and User-Friendly Interface**

---

# 🎯 Key Insights

From the analysis of phishing emails:
* Phishing emails frequently contain **urgent or threatening language**.
* **Suspicious URLs and attachments** are strong phishing indicators.
* Machine learning helps **automate phishing detection** efficiently.
* Model accuracy improves with **continuous retraining on new data**.

---

# 🚀 How to Run This Project
## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Vasantlohar0504/phishing-email-detection.git
cd phishing-email-detection
```

---

## 2️⃣ Create Virtual Environment
```bash
python -m venv venv
```
### Activate Environment
**Windows**
```bash
venv\Scripts\activate
```
**Mac / Linux**
```bash
source venv/bin/activate
```
---
## 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
---
## 4️⃣ Run the Flask Application
```bash
python app.py
```
Open your browser and visit:
```
http://127.0.0.1:5000
```
---

# 📊 Example Usage
### Input Email
> Dear user,
> Your account has been suspended. Click the link below to verify your account immediately.

### Prediction Result
⚠️ **Phishing Email Detected**

### Analysis
* Suspicious URL detected
* Attachment status: Safe
---

# 📜 License

This project is licensed under the **MIT License**.

You are free to **use, modify, and distribute** this project.

---

# 👨‍💻 Author

**Vasant Lohar**
Data Analyst | Data Science Enthusiast
