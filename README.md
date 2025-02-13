##📌 Project Overview

This project builds a Machine Learning model to predict the future sale price of bulldozers based on their characteristics and historical sales data.

The dataset contains nearly 400,000 examples with 50+ different features, making it a time-series forecasting problem.


##🔍 Objective

The goal is to develop a model that accurately predicts bulldozer sale prices using a variety of features such as:

Bulldozer characteristics (make year, base model, model series, drive system, etc.)

Historical sales data (past sale prices)

Time-related features (year, month, sale date)


##🛠 Technologies Used

Python

Pandas, NumPy (Data Preprocessing)

Matplotlib, Seaborn (Data Visualization)

Scikit-Learn (Machine Learning)

Random Forest (Regression Models)

Time Series Forecasting Techniques


##📊 Dataset

📌 The dataset used for this project is from Kaggle’s "Blue Book for Bulldozers" competition.

It contains detailed sales records of bulldozers, including:

Features: 50+ attributes like ModelID, YearMade, MachineHours, Enclosure, etc.

Target Variable: SalePrice (The actual sale price of the bulldozer)

##🚀 How to Run the Project

1️⃣ Clone the repository:

```bash
git clone https://github.com/praca451/buldozer-price.git
cd bulldozer-price
```

2️⃣ ## Requirements

```bash
pip install -r requirements.txt
```

3️⃣ Run the Jupyter Notebook: 
```bash
jupyter notebook Buldozer_Price_Prediction.ipynb
```

🔬 Results & Performance

Model Used: Random Forest Regressor 

Evaluation Metric: Root Mean Squared Log Error (RMSLE)

Best Model Accuracy: Achieved high accuracy in predicting bulldozer prices.


📌 Next Steps

🔹 Improve feature engineering (handling missing values, outliers, categorical encoding)

🔹 Try deep learning models (LSTMs, Transformers for time series forecasting)

🔹 Deploy the model as a web API for real-time predictions



