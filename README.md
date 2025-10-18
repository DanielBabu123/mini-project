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

Install dependencies using either of the two methods below:

### 👉 Option 1: Using `requirements.txt`
```bash
pip install -r requirements.txt
👉 Option 2: Manually install each package
bash
Copy code
pip install django mysqlclient numpy pandas scikit-learn matplotlib joblib
🛠️ How to Run the Project
1️⃣ Clone the repository:
bash
Copy code
git clone-https://github.com/VithanalaLakshminarasimhaSwamy/Multi-Perspective-Fraud-Detection-System
cd multi-perspective-fraud-detection
2️⃣ Create and activate a virtual environment:
bash
Copy code
python -m venv venv
venv\Scripts\activate       # On Windows
# source venv/bin/activate  # On Mac/Linux
3️⃣ Install dependencies:
Follow the Requirements section above.

4️⃣ Set up the MySQL database:
Open  MySQL Workbench

Create a database named multi_db

Update database configuration inside a_multiperspective_fraud_detection/settings.py

Example:

python
Copy code
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
5️⃣ Apply Django migrations:
bash
Copy code
python manage.py makemigrations
python manage.py migrate
6️⃣ Run the server:
bash
Copy code
python manage.py runserver
7️⃣ Open your browser and visit:
👉 http://127.0.0.1:8000/

✅ Done!
Your app should now be running locally 🎉

📸 Screenshots Overview
Screenshot	Description
🏠 Home Page	Entry screen of the web application
📝 Registration Page	Allows users to register with details
🔑 Remote User Login	User login screen for accessing prediction features
📋 Remote User Details Table	Displays all remote users and their metadata
📈 Accuracy Line Graph	Line chart showing accuracy of ML models
📊 Accuracy Bar Chart	Bar chart comparison of ML models by performance
🥧 Accuracy Pie Chart	Pie chart showing proportional accuracy of algorithms

💡 Future Enhancements
Integration of Deep Learning models (LSTM/ANN)

Live transaction data monitoring

Advanced anomaly detection using hybrid models

👨‍💻 Author
Lakshminarasimha Swamy Vithanala
📧 lakshminarasimhaswamyvithanala@gmail.com
🌐 GitHub Profile
