# ₿ Cryptocurrency Price Movement Analysis

A Machine Learning project that analyzes historical cryptocurrency market data and predicts short-term price movements using regression models. The project explores trends, performs feature engineering, and compares the performance of Linear Regression and Random Forest Regressor for cryptocurrency price prediction.

---

## 📖 Overview

Cryptocurrencies such as **Bitcoin (BTC)**, **Ethereum (ETH)**, and **Cardano (ADA)** are known for their high volatility. This project analyzes historical market data to identify trends and build predictive models that estimate future closing prices using machine learning techniques.

The project follows a complete data analysis pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## ✨ Features

- 📊 Historical cryptocurrency price analysis
- 🧹 Data cleaning and preprocessing
- 📈 Exploratory Data Analysis (EDA)
- ⚙️ Feature Engineering
- 🤖 Machine Learning-based price prediction
- 📉 Performance comparison of regression models
- 📊 Interactive visualizations using Matplotlib

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

### Machine Learning Models
- Linear Regression
- Random Forest Regressor

### Development Environment
- Jupyter Notebook
- Google Colab

---

## 📂 Dataset

The dataset contains historical cryptocurrency information including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

Cryptocurrencies analyzed include:

- Bitcoin (BTC)
- Ethereum (ETH)
- Cardano (ADA)

---

## ⚙️ Project Workflow

### 1. Data Collection
Historical cryptocurrency data is collected from reliable financial sources.

### 2. Data Preprocessing
- Handle missing values
- Remove duplicates
- Convert date formats
- Sort chronological records

### 3. Exploratory Data Analysis
- Price trend analysis
- Correlation analysis
- Volatility measurement
- Statistical summaries

### 4. Feature Engineering
Generated features include:
- Moving Averages
- Lag Features
- Percentage Change
- Technical Indicators

### 5. Model Training
Two regression models are implemented:

- Linear Regression
- Random Forest Regressor

### 6. Model Evaluation
Models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)

---

## 📁 Project Structure

```
Cryptocurrency-Price-Movement-Analysis/
│
├── data/
│   ├── bitcoin.csv
│   ├── ethereum.csv
│   └── cardano.csv
│
├── notebooks/
│   └── Crypto_Analysis.ipynb
│
├── images/
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📊 Machine Learning Models

### Linear Regression
A baseline regression model used to predict future cryptocurrency prices based on historical features.

### Random Forest Regressor
An ensemble learning model capable of capturing complex relationships within cryptocurrency market data.

---

## 📈 Evaluation Metrics

The prediction models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)

These metrics help compare model performance and prediction accuracy.

---

## 📸 Screenshots

- Data Visualization
- Correlation Heatmap
- Model Prediction
- Performance Comparison
  <img width="603" height="630" alt="image" src="https://github.com/user-attachments/assets/ad617759-0c91-4246-864b-355f4cdd688f" />
<img width="603" height="630" alt="image" src="https://github.com/user-attachments/assets/276cbf10-fbc6-4eb8-a864-dce6c08804da" />
<img width="700" height="726" alt="image" src="https://github.com/user-attachments/assets/264e1389-c1c9-4eac-a9e9-0ce28dd00946" />
<img width="727" height="485" alt="image" src="https://github.com/user-attachments/assets/09baf203-674d-4241-b13b-5a00fd19f2f6" />
<img width="661" height="668" alt="image" src="https://github.com/user-attachments/assets/9a1ca425-5292-4b30-b061-409af4b03cfd" />
<img width="662" height="731" alt="image" src="https://github.com/user-attachments/assets/9f61446d-745d-4003-b410-8c591a2dad67" />


## 🔮 Future Enhancements

- Deep Learning using LSTM
- XGBoost Regression
- Prophet Time Series Forecasting
- Real-Time Cryptocurrency Price Prediction
- Sentiment Analysis from News & Social Media
- Interactive Dashboard using Streamlit
- Automated Trading Signal Generation

---

## 👨‍💻 Authors

- N. Abhirishitha
## 📚 Academic Project

Submitted to **APSSDC**

## 📜 License

This project is developed for educational, research, and learning purposes.
