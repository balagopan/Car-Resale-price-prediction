# 🚗 Used Car Resale Price Prediction using Machine Learning

An end-to-end machine learning project that predicts the resale price of used cars by applying data preprocessing, feature engineering, exploratory data analysis, and regression models. The project evaluates multiple machine learning algorithms and identifies the best-performing model through hyperparameter tuning.

---

## 📌 Project Overview

Pricing a used car accurately is challenging due to numerous influencing factors such as vehicle age, mileage, fuel type, transmission, engine specifications, and location.

This project aims to build a regression model capable of predicting the resale value of a used car using structured vehicle data.

The workflow follows a complete machine learning pipeline:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Hyperparameter Optimization
- Model Evaluation
- Performance Comparison

---

## 📂 Dataset

The dataset contains information about used vehicles, including:

- Vehicle Brand
- Model
- Manufacturing Year
- Registered Year
- Fuel Type
- Transmission Type
- Body Type
- Engine Capacity
- Maximum Power
- Mileage
- Kilometers Driven
- City
- Selling Price (Target Variable)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

# 📊 Exploratory Data Analysis

The dataset was explored to understand relationships between vehicle characteristics and resale price.

EDA included:

- Missing value analysis
- Distribution plots
- Correlation analysis
- Outlier inspection
- Feature relationship visualization

---

# 🧹 Data Preprocessing

Several preprocessing techniques were applied before model training.

### Data Cleaning

- Removed unnecessary columns
- Handled missing values
- Converted data types
- Extracted numerical values from text columns
- Converted price values into numerical format

### Feature Engineering

- Log transformation of skewed numerical features
- Creation of engineered features
- Feature scaling
- One-hot encoding of categorical variables

---

# 🤖 Machine Learning Models

The following regression models were trained and compared.

| Model | Purpose |
|--------|----------|
| Linear Regression | Baseline model |
| Ridge Regression | Regularized Linear Regression |
| Decision Tree Regressor | Non-linear regression |
| Random Forest Regressor | Ensemble learning model |

---

# ⚙ Hyperparameter Tuning

GridSearchCV was used to optimize model parameters for improved performance.

Examples of tuned parameters include:

- Maximum depth
- Minimum samples split
- Minimum samples leaf
- Number of estimators

---

# 📈 Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The best-performing model achieved approximately:

| Metric | Value |
|---------|--------|
| Test R² | ~0.94 |
| Train R² | ~0.99 |

Random Forest produced the highest predictive performance among the evaluated models.

---

# 📁 Project Structure

```
Used-Car-Price-Prediction/
│
├── Car_resale_price_prediction.ipynb
├── README.md
├── requirements.txt
└── dataset/
```

---

# 🚀 How to Run

## Clone the repository

```bash
git clone https://github.com/balagopan/Used-Car-Price-Prediction.git
```

## Navigate to the project

```bash
cd Used-Car-Price-Prediction
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Car_resale_price_prediction.ipynb
```

---

# 📌 Future Improvements

- Implement a Scikit-learn Pipeline for streamlined preprocessing and model training.
- Perform feature importance analysis using SHAP.
- Experiment with Gradient Boosting models such as XGBoost, LightGBM, and CatBoost.
- Develop a web application using Streamlit or Flask for real-time price prediction.
- Deploy the model on a cloud platform for public access.

---

# 💡 Key Learning Outcomes

This project demonstrates practical experience in:

- Data preprocessing
- Feature engineering
- Exploratory data analysis
- Regression modeling
- Hyperparameter tuning
- Model evaluation
- Machine learning workflow design

---

# 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**Balagopan G**

- MSc Artificial Intelligence, Asia Pacific University (APU)
- Former 2D Animator transitioning into Artificial Intelligence and Machine Learning

Feel free to connect or contribute to the project!
