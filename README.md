# 🏥 Risk-Based Health Analysis

A Machine Learning project that predicts health risk levels using patient health, lifestyle, and medical data. The project applies data preprocessing, exploratory data analysis (EDA), feature engineering, and classification models to identify potential health risks.

---

## 📌 Project Overview

The goal of this project is to analyze various health-related factors and predict the health risk category of an individual.

The model considers:

- Health metrics
- Lifestyle habits
- Medical history
- Physical activity
- Dietary information

and predicts the corresponding health risk level.

---

## 📊 Dataset Information

| Attribute | Value |
|------------|---------|
| Records | 9,549 |
| Features | 22 |
| Target Variable | Target |

### Features Included

#### Health Metrics
- Age
- BMI
- Blood Pressure
- Cholesterol
- Glucose Level
- Heart Rate

#### Lifestyle Factors
- Sleep Hours
- Exercise Hours
- Water Intake
- Stress Level
- Smoking
- Alcohol Consumption

#### Medical Factors
- Mental Health
- Physical Activity
- Medical History
- Allergies

#### Encoded Features
- Diet Type (Vegan, Vegetarian)
- Blood Group (AB, B, O)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🔄 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Health Risk Prediction

---

## 🤖 Machine Learning Models

The project can be extended using:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Voting Classifier
- Stacking Classifier

---

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 82.25% |
| Gradient Boosting | 91.83% |
| Voting Classifier | 92.46% |
| Random Forest | 94.08% |
| Stacking Classifier | 94.24% |

### Best Model
The Stacking Classifier achieved the highest accuracy of **94.24%**, outperforming all other models tested.
---

## 📁 Project Structure

```text
risk-based-health-analysis/
│
├── data/
│   └── novagen_dataset.csv
│
├── notebooks/
│   └── risk-based_analysis_of_health.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/risk-based-health-analysis.git
cd risk-based-health-analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/risk-based_analysis_of_health.ipynb
```

---

## 📌 Future Improvements

- Hyperparameter Tuning
- Ensemble Learning
- Streamlit Web Application
- Real-Time Health Risk Prediction
- Model Deployment on Cloud

---

## 👨‍💻 Author

**Abhishek Nangare**

Final Year B.E. Artificial Intelligence & Data Science

GitHub: https://github.com/Abhishek-Nangare1431

---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
