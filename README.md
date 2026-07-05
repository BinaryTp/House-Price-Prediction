# 🏠 House Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas)
![License](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

This project predicts house prices using Machine Learning regression algorithms based on property characteristics such as bedrooms, bathrooms, living area, location, floors, and construction details.

The project demonstrates the complete Machine Learning workflow including:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Residual Analysis
- Model Saving
- Sample Prediction

---

## 🎯 Objective

Develop a regression model capable of accurately predicting house prices by comparing multiple machine learning algorithms and selecting the best-performing model.

---

## 📂 Dataset Information

The dataset contains **4,600 residential property records** with **18 features**.

### Features Include

- Date
- Bedrooms
- Bathrooms
- Living Area
- Lot Area
- Floors
- Waterfront
- View
- Condition
- Above Ground Area
- Basement Area
- Year Built
- Year Renovated
- Street
- City
- State & ZIP
- Country

### Target Variable

- **Price**

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📊 Exploratory Data Analysis

The following visualizations were performed:

- Correlation Heatmap
- Price Distribution
- Living Area vs Price
- Bedrooms vs Price
- Bathrooms vs Price
- Floors vs Price
- Pairplot

---

## ⚙️ Feature Engineering

The following preprocessing steps were performed:

- Duplicate Check
- Missing Value Analysis
- Date Feature Extraction
- One-Hot Encoding
- Train-Test Split

---

## 🤖 Machine Learning Models

Three regression models were trained and compared:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The model with the highest R² Score was selected as the final model.

---

## 📁 Project Structure

```text
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── data.csv
├── house_price_model.pkl
├── model_comparison.csv
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/House-Price-Prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd House-Price-Prediction
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the Notebook

Run the notebook using Google Colab or Jupyter Notebook.

---

## 📷 Project Screenshots

### Correlation Heatmap

*(Add screenshot later)*

### Model Comparison

*(Add screenshot later)*

### Residual Plot

*(Add screenshot later)*

---

## 📌 Results

- Successfully built a complete regression pipeline.
- Compared three machine learning algorithms.
- Selected the best-performing model based on evaluation metrics.
- Saved the trained model using Joblib.
- Demonstrated prediction using unseen data.

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Advanced feature engineering
- Web application deployment using Streamlit

---

## 👨‍💻 Author

**Tushar Patel**

AI & ML Enthusiast | Machine Learning | Python | Data Science

GitHub: https://github.com/BinaryTp

LinkedIn: www.linkedin.com/in/tushar-patel-2a7167323

---

⭐ If you found this project useful, consider giving it a star!
