# 🛡️ Multi-Perspective Fraud Detection for E-Commerce Transactions

A **web-based machine learning project** to detect fraudulent transactions in **multi-participant e-commerce systems** by analyzing behavior using a combination of **process mining** and **machine learning (SVM, etc.)**.
---
## 🚀 Features

- 📊 **Analyze user behavior** from multiple perspectives (time, resource, control flow)  
- ✅ **Predict** whether a transaction is fraudulent  
- 🔐 **Role-based login** for Remote Users and Service Providers  
- 📈 **Visualize model accuracy** using graphs (Bar, Pie, Line)  
- 🧠 **SVM-based classification** integrated with Django backend  
- 📂 **Upload and process datasets** from the admin interface  

---

## 🏗️ Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Python, Django |
| **Database** | MySQL (via MySQLWORKBENCH) |
| **ML Algorithms** | SVM, Decision Tree, Logistic Regression, Naive Bayes, Random Forest |
| **Visualization** | Matplotlib |
| **Deployment** | Git + GitHub |

---


## 🧰 Requirements

Install dependencies using **one** of the two options below:

### 👉 Option 1: Using `requirements.txt`
```bash
pip install -r requirements.txt
```
### 👉 Option 2: Manual Installation
```bash
pip install django mysqlclient numpy pandas scikit-learn matplotlib joblib
```
🚀 How to Run the Project
1️⃣ Clone the Repository
```bash
git clone https://github.com/VithanalaLakshminarasimhaSwamy/Multi-Perspective-Fraud-Detection-System.git
cd Multi-Perspective-Fraud-Detection-System
```
2️⃣ Create & Activate a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate       # On Windows
# source venv/bin/activate  # On Mac/Linux
```
3️⃣ Install Dependencies
Follow the steps mentioned in the Requirements section above.

4️⃣ Set Up the MySQL Database
1.Open MySQL Workbench.
2.Create a new database named multi_db.
3.Update your database configuration inside a_multiperspective_fraud_detection/settings.py:
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'multi_db',
        'USER': 'root',
        'PASSWORD': 'root',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}

```
5️⃣ Apply Django Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
6️⃣ Run the Server
```bash
python manage.py runserver
```
7️⃣ Access the Application
Open your browser and go to:
👉 http://127.0.0.1:8000/
```
```
✨ Features
📊 Multi-perspective behavior analysis

✅ Fraudulent transaction prediction

🔐 Role-based login for Remote Users & Service Providers

📈 Model accuracy visualization using interactive graphs

```
```
💡 Future Enhancements
```
```
🤖 Integration of Deep Learning models (LSTM / ANN)

📡 Live transaction data monitoring

🧠 Advanced anomaly detection using hybrid models
```
```
👨‍💻 Author
```
```
Lakshminarasimha Swamy Vithanala
📧 lakshminarasimhaswamyvithanala@gmail.com
🌐 GitHub Profile

```
```
📜 License
```
```
This project is intended for academic learning and educational submission only.
Not intended for commercial use.
```
