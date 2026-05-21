# 🏥 Hospital Clinical Deterioration Detection System

---

# 📌 Overview

The **Hospital Clinical Deterioration Detection System** is an AI-powered healthcare prediction application designed to identify patients at risk of clinical deterioration using Machine Learning algorithms.

The system analyzes hospital clinical datasets and predicts whether a patient is stable or at risk of deterioration.

This project provides:

* Clinical risk prediction
* Machine learning model comparison
* Patient deterioration analysis
* Real-time prediction interface
* Performance visualization dashboard
* GUI-based healthcare application

The proposed model uses a powerful **HistGradientBoostingClassifier** to improve prediction performance and achieve high clinical accuracy.

---

# 🚀 Features

✅ Upload hospital clinical datasets
✅ Automatic preprocessing and encoding
✅ Stratified train-test splitting
✅ Existing ML model evaluation
✅ Proposed advanced boosting model
✅ Clinical deterioration prediction
✅ Confusion matrix visualization
✅ Performance graph comparison
✅ Modern healthcare GUI dashboard
✅ Risk prediction for new patient records
---

# 🧠 Machine Learning Models Used
* Isolation Forest
* Bayesian Ridge
* Logistic Regression
* HistGradientBoostingClassifier (Proposed Model)
---

# 🖼 Project Preview

## Clinical Dashboard

* Upload dataset
* Preprocess data
* Train/test split
* Evaluate existing models
* Execute proposed model
* Predict patient risk
* Performance comparison
---
# 📂 Project Structure

```text
Hospital-Clinical-Deterioration/
│
├── main.py
├── background.png
├── LOGO.jpeg
├── Hospital Clinical Deterioration.csv
├── test_patients.csv
│
├── IsolationForest_weights.pkl
├── BayesianRidge_weights.pkl
├── LogisticRegression_weights.pkl
├── GradientBoosting_1weights.pkl
│
├── README.md
└── requirements.txt
```

---

# ⚙️ Technologies Used

## Programming Language
* Python

## GUI Framework
* Tkinter

## Machine Learning
* Scikit-learn

## Data Processing
* Pandas
* NumPy

## Data Visualization
* Matplotlib
* Seaborn

## Image Processing
* Pillow (PIL)

---
# 📦 Installation Guide
## Step 1: Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/Hospital-Clinical-Deterioration.git
```
---
## Step 2: Navigate to Project Folder
```bash
cd Hospital-Clinical-Deterioration
```
---
## Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```
---
# 📋 Requirements File
Create a `requirements.txt` file and add:
```text
pandas
numpy
matplotlib
seaborn
scikit-learn
pillow
joblib
```
---

# ▶️ Run the Project
```bash
python main.py
```
---
# 📊 System Workflow
## 1️⃣ Upload Dataset

Load the hospital clinical dataset in CSV format.

---
## 2️⃣ Preprocess Dataset

The system performs:

* Missing value removal
* Label encoding
* Feature preparation
* Data cleaning

---

## 3️⃣ Train-Test Splitting

Dataset is split into:

* 80% Training Data
* 20% Testing Data

Using stratified splitting for balanced prediction.

---

## 4️⃣ Existing Model Evaluation

The following models are evaluated:

* Isolation Forest
* Bayesian Ridge
* Logistic Regression

The system generates:

* Accuracy score
* Classification report
* Confusion matrix

---

## 5️⃣ Execute Proposed Model

The proposed:

## HistGradientBoostingClassifier

is trained with optimized hyperparameters for:

* Better accuracy
* Faster training
* Large dataset support
* Balanced prediction

---

## 6️⃣ Clinical Risk Prediction

The system predicts:

| Risk Level  | Status                |
| ----------- | --------------------- |
| Low Risk    | ✅ Stable              |
| Medium Risk | 🟡 Moderate Risk      |
| High Risk   | ⚠️ Deterioration Risk |

---

## 7️⃣ Performance Visualization

Performance graphs include:

* Accuracy comparison
* Confusion matrix
* Clinical model performance chart

---

# 🏥 Clinical Prediction Categories

| Risk Percentage | Prediction    |
| --------------- | ------------- |
| Below 40%       | Stable        |
| 40% - 74%       | Moderate Risk |
| 75% and Above   | High Risk     |

---

# 📈 Proposed Model Advantages

The proposed HistGradientBoosting model provides:

* High prediction accuracy
* Better handling of clinical imbalance
* Faster execution
* Large-scale hospital data support
* Improved patient deterioration detection

---

# 🔒 Future Enhancements

* Deep Learning Integration
* Real-Time Monitoring
* Cloud Deployment
* EHR Integration
* SMS/Email Alert System
* Multi-Hospital Support
* Doctor Dashboard
* Patient Analytics

---

# 👨‍💻 Author

## Bhaskar Yadav

B.Tech CSE Student

AI & Healthcare Enthusiast

---

# 📜 License

This project is developed for:

* Academic Purposes
* Research Work
* Healthcare AI Learning

---

# ⭐ GitHub Upload Commands

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
git push -u origin main
```

---

# 🌟 Support

If you like this project:

⭐ Star the repository

🍴 Fork the project

📢 Share with others

---

# 💡 Conclusion

The Hospital Clinical Deterioration Detection System demonstrates how Artificial Intelligence and Machine Learning can help healthcare organizations predict patient deterioration risk and improve clinical decision-making.

This project combines:

* Healthcare Analytics
* Machine Learning
* GUI Development
* Clinical Prediction
* Performance Visualization

into one complete intelligent healthcare solution.
