

# 🌱 Prosperity Prognosticator

### Machine Learning for Startup Success Prediction

## 📌 Project Overview

**Prosperity Prognosticator** is a machine learning–based project that predicts whether a startup is likely to succeed or fail using historical startup data. By analyzing financial, categorical, and operational features, the model provides data-driven insights to help investors, founders, and analysts make informed decisions.

The final model achieves **~94% precision and recall**, indicating strong predictive performance.

---

## 🎯 Problem Statement

Startups play a critical role in innovation and economic growth, but a large percentage fail due to financial, operational, or market-related factors.
The goal of this project is to:

* Analyze startup-related features
* Identify patterns linked to success or failure
* Build a reliable machine learning model to predict startup outcomes

---

## 📊 Dataset Description

The dataset contains information related to startups, including:

* **Numerical features** (funding amounts, milestones, etc.)
* **Categorical features** (industry, country, status, etc.)
* **Target variable**: `status` (Success / Failure)

### Key Preprocessing Steps

* Handling missing values
* Encoding categorical variables
* Feature scaling
* Converting target labels into machine-readable format

---

## 🔍 Exploratory Data Analysis (EDA)

The project includes:

* Data type identification
* Separation of numerical and categorical features
* Distribution analysis
* Correlation checks
* Feature importance understanding

EDA helps uncover trends and relationships that influence startup success.

---

## 🤖 Machine Learning Models Used

Multiple models were trained and evaluated, including:

* Logistic Regression
* Decision Tree
* Random Forest
* Other classification algorithms

### Evaluation Metrics

* Precision
* Recall
* F1-score
* Accuracy

✅ The best-performing model achieved **approximately 94% precision and recall**.

---

## ⚙️ Technologies & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib / Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📈 Results

* High predictive accuracy with balanced precision and recall
* Strong classification performance on unseen data
* Suitable for real-world startup evaluation scenarios

---

## 🚀 How to Run the Project

1. Clone the repository

   ```bash
   git clone https://github.com/eswarsaikiran15/prosperity-prognosticator.git
   ```
2. Navigate to the project directory

   ```bash
   cd prosperity-prognosticator
   ```
3. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook

   ```bash
   jupyter notebook startup-success-prediction-precision-recall-94.ipynb
   ```

---

## 🔮 Future Enhancements

* Deploy model as a web application (Flask / FastAPI)
* Add real-time startup data
* Improve explainability using SHAP or LIME
* Include deep learning models for comparison

