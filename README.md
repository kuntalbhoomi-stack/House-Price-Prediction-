# 🏡 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation using multiple regression algorithms.

The objective is to identify the key factors affecting house prices and build a model capable of accurately predicting the price of a house based on its features.

---

## 📂 Dataset

* **Dataset:** Housing Prices Dataset
* **Format:** CSV
* **Target Variable:** `price`

### Features

The dataset includes attributes such as:

* Area
* Number of Bedrooms
* Number of Bathrooms
* Number of Stories
* Parking Spaces
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Preferred Area
* Furnishing Status

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Explored the dataset structure and data types.

### 2. Data Cleaning

* Checked for missing values.
* Checked for duplicate records.
* Verified data types.
* Prepared the dataset for analysis.

### 3. Exploratory Data Analysis (EDA)

Created multiple visualizations to understand the data, including:

* Correlation Heatmap
* Price Distribution
* Boxplots
* Scatter Plots
* Count Plots
* Pairplot
* Feature Relationships

### 4. Feature Engineering

* Encoded categorical variables.
* Prepared features and target variable.
* Split the dataset into training and testing sets.

### 5. Model Building

The following regression models were trained and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor

### 6. Model Evaluation

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 7. Results

The model with the highest R² score provided the best predictive performance and demonstrated the importance of comparing multiple machine learning algorithms for regression tasks.

---

## 📁 Project Structure

```text
House-Price-Prediction/
│
├── data/
│   └── Housing.csv
│
├── notebook/
│   └── House Price Prediction.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook.
4. Run all cells sequentially.

---

## 📈 Future Improvements

* Hyperparameter tuning
* Cross-validation
* XGBoost and LightGBM models
* Model deployment using Streamlit or Flask
* Interactive dashboard for predictions

---

## 🎯 Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Regression Modeling
* Model Evaluation
* Machine Learning
* Python Programming

---

## 👩‍💻 Author

**Bhoomi Kuntal**

B.Tech (CSE – Data Science)

If you found this project helpful, feel free to ⭐ the repository and connect with me on LinkedIn.
