# 🩺 Heart Disease Prediction using Machine Learning

## 📌 Overview
This project predicts heart disease using machine learning models based on patient medical records. The primary goal is to develop a predictive system that helps in the early detection of heart disease, potentially assisting healthcare professionals in diagnosis and risk assessment.

We implemented and compared two machine learning models:
- **Naïve Bayes** (Probabilistic Classifier)
- **Random Forest** (Ensemble Decision Trees)

## 📊 Dataset Description
The dataset consists of several patient health parameters, including age, cholesterol levels, chest pain type, and heart rate, among others.

| Column Name      | Description |
|-----------------|------------|
| **Age**         | Patient's age (in years) |
| **Sex**         | Gender (`M` = Male, `F` = Female) |
| **ChestPainType** | Type of chest pain: `ATA` (Atypical Angina), `NAP` (Non-Anginal Pain), `ASY` (Asymptomatic) |
| **RestingBP**   | Resting blood pressure (mmHg) |
| **Cholesterol** | Serum cholesterol (mg/dL) |
| **FastingBS**   | Fasting blood sugar (`1` = >120 mg/dL, `0` = Normal) |
| **RestingECG**  | Resting ECG results: `Normal`, `ST` (ST-T wave abnormality), `LVH` (Left Ventricular Hypertrophy) |
| **MaxHR**       | Maximum heart rate achieved |
| **ExerciseAngina** | Exercise-induced angina (`Y` = Yes, `N` = No) |
| **Oldpeak**     | ST depression induced by exercise |
| **ST_Slope**    | Slope of the ST segment: `Up`, `Flat`, or `Down` |
| **HeartDisease** | Target variable (`1` = Heart Disease, `0` = No Heart Disease) |

---

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `NumPy` - Numerical computations
  - `Pandas` - Data handling and manipulation
  - `Matplotlib & Seaborn` - Data visualization
  - `Scikit-Learn` - Machine learning models
  - `Jupyter Notebook` - Running and visualizing analysis

---

## 🧠 Machine Learning Models
### 1️⃣ Naïve Bayes
- Probabilistic classifier based on **Bayes’ theorem**
- Assumes feature independence
- Performs well with small datasets

### 2️⃣ Random Forest
- Ensemble method with multiple decision trees
- Reduces overfitting and improves accuracy
- Handles both numerical and categorical features

---

## 🚀 Model Performance
The models were evaluated using Accuracy, Precision, Recall, and F1-Score.

| Model           | Accuracy | Precision | Recall | F1 Score |
|----------------|---------|-----------|--------|---------|
| **Naïve Bayes** | 85%     | 83%       | 81%    | 82%     |
| **Random Forest** | **92%** | **90%**   | **89%** | **89%** |

### Observations:
✅ **Naïve Bayes** performed well but assumes feature independence, which may not always hold.  
✅ **Random Forest** achieved **higher accuracy** by leveraging multiple decision trees.  

---

## 📌 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
