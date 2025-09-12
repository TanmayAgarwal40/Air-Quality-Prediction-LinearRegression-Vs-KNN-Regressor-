# 🌍 Air Quality Prediction: Linear Regression vs KNN Regressor

This project focuses on predicting **Air Quality Index (AQI)** pollutants using **Machine Learning models**.  
It compares **Linear Regression** and **KNN Regressor** in predicting pollutant concentrations like CO, NO₂, and NMHC.

---

## 📌 Features
- Data preprocessing and cleaning  
- Predictive modeling using:
  - **Linear Regression**
  - **KNN Regressor**
- Model evaluation with metrics:
  - **RMSE (Root Mean Square Error)**
  - **R² Score**
- Visualization of actual vs predicted values  
- Clear comparison of both models  

---

## 📊 Technologies Used
- **Python 3**
- **pandas, numpy** (data preprocessing)
- **scikit-learn** (machine learning models & metrics)
- **matplotlib, seaborn** (visualizations)

---

## 📂 Project Structure
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for experiments
├── src/ # Source code
│ ├── preprocess.py # Data cleaning and preprocessing
│ ├── train.py # Model training scripts
│ └── evaluate.py # Model evaluation
├── results/ # Plots and model comparisons
└── README.md # Project documentation

---

![Liner Reggession vs KNN Reggession](https://github.com/TanmayAgarwal40/Air-Quality-Prediction-LinearRegression-Vs-KNN-Regressor-/blob/main/results/sample_results.png)


## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/TanmayAgarwal40/Air-Quality-Prediction-LinearRegression-Vs-KNN-Regressor-.git
   cd Air-Quality-Prediction-LinearRegression-Vs-KNN-Regressor-

pip install -r requirements.txt

jupyter notebook notebooks/AQI_Prediction.ipynb


📈 Results
Linear Regression performed well on continuous pollutant prediction but was sensitive to outliers.
KNN Regressor handled non-linear patterns better but required tuning (K-values).
Sample Visualization:
(Add plots like Actual vs Predicted here for better visibility)

🔮 Future Improvements
Try other regression models (Random Forest, Gradient Boosting)
Incorporate time-series forecasting for AQI trends
Deploy the model using Streamlit or Flask

🧑‍💻 Author
Tanmay Agarwal
LinkedIn : https://www.linkedin.com/in/tanmay-agarwal-496bb132a/
GitHub : https://github.com/TanmayAgarwal40/Air-Quality-Prediction-LinearRegression-Vs-KNN-Regressor-
