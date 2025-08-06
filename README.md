# house-price-prediction-ml
A beginner-friendly regression project predicting house prices using ML
House Price Prediction using Machine Learning

This is a beginner-friendly regression project where I predict house prices using real-world housing data. Built using Python, Pandas, Scikit-learn, and visualized with Seaborn and Matplotlib.

---

## 📌 Problem Statement

The goal is to predict the sale prices of houses based on various features such as the number of rooms, overall quality, living area size, and more. This helps understand how different attributes affect housing prices.

---

## 📊 Dataset

- Source: [Kaggle – House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- File used: train.csv

---

## 🛠️ Tools & Libraries

- Python
- Google Colab
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn (LinearRegression, RandomForestRegressor)

---

## 🚀 Steps Followed

1. *Data Cleaning*:
   - Removed columns with too many missing values
   - Filled numerical missing values with median
   - One-hot encoded categorical variables

2. *EDA (Exploratory Data Analysis)*:
   - Checked correlation between variables
   - Visualized feature relationships

3. *Model Building*:
   - Linear Regression
   - Random Forest Regressor

4. *Evaluation*:
   - Metric used: RMSE (Root Mean Squared Error)
   - Compared both models’ performance

---

## 🔍 Results

| Model                | RMSE (Lower is Better) |
|---------------------|------------------------|
| Linear Regression    | ~68,702            |
| Random Forest Regressor | ~46,560 ✅            |

*Random Forest performed better* by making more accurate predictions on house prices.

---

## 💡 What I Learned

- Basics of regression modeling
- Data preprocessing and handling missing values
- Model comparison using error metrics
- Importance of feature engineering

---

## 📂 How to Use

1. Download the dataset from Kaggle
2. Open the notebook in Google Colab
3. Upload the train.csv file when prompted
4. Run all cells to see results and plots

---

## 🌟 Future Improvements

- Hyperparameter tuning
- Feature selection
- Model saving and deployment
- UI integration with Streamlit or Flask

---

## 🙋‍♀️ About Me

Hi, I'm Kunti!  
I'm learning Machine Learning and building real-world projects as part of my internship prep and career growth.  
Let’s connect on [LinkedIn](https://www.linkedin.com/) and learn together. 💖
