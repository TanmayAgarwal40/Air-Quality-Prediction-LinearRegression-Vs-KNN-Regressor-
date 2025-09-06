# 🌍 Air Quality Prediction: Linear Regression vs KNN Regressor

This project predicts **Air Quality Index (AQI) pollutants** (CO, NO₂, NMHC, etc.) using machine learning.  
It compares **Linear Regression** and **KNN Regressor** models to evaluate prediction accuracy and provide insights into pollution patterns.

---

## 📌 Features
- Multi-pollutant prediction (CO, NO₂, NMHC, etc.)
- Implements **Linear Regression** and **KNN Regressor**
- Model evaluation using:
  - **RMSE (Root Mean Square Error)**
  - **R² Score**
- Visualizations of actual vs predicted values
- Side-by-side model comparison
- Data preprocessing for missing/invalid values

---

## 📊 Tech Stack
- **Python 3**
- **pandas, numpy** – data handling
- **scikit-learn** – machine learning models & metrics
- **matplotlib, seaborn** – visualization

---

## 📂 Project Structure
```
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks
│   └── AQI_Prediction.ipynb
├── src/                 # Source code
│   ├── preprocess.py    # Data cleaning
│   ├── train.py         # Model training
│   └── evaluate.py      # Model evaluation
├── results/             # Plots (rmse_comparison.png, co_actual_vs_pred.png)
├── requirements.txt     # Dependencies
└── README.md            # Documentation
```

---

## 🚀 Installation & Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/TanmayAgarwal40/Air-Quality-Prediction-LinearRegression-Vs-KNN-Regressor-.git
   cd Air-Quality-Prediction-LinearRegression-Vs-KNN-Regressor-
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook notebooks/AQI_Prediction.ipynb
   ```

---

## 📈 Results
- **Linear Regression**:
  - Good for continuous trends
  - Sensitive to outliers
- **KNN Regressor**:
  - Better at capturing non-linear patterns
  - Requires tuning of K-values

Example Visualization:  
![RMSE Comparison](results/rmse_comparison.png)  
![CO Prediction](results/co_actual_vs_pred.png)

---

## 🌐 Applications
- **Government** – early warning systems & policy-making  
- **Education** – teaching ML with real-world datasets  
- **Public Awareness** – understanding pollution patterns  

---

## 🔮 Future Improvements
- Try additional models (Random Forest, Gradient Boosting)  
- Explore time-series forecasting of AQI trends  
- Build an interactive dashboard (Streamlit/Flask)  

---

## 📚 References
- [UCI Machine Learning Repository: Air Quality Dataset](https://archive.ics.uci.edu/)  
- [WHO Air Quality Standards](https://www.who.int/)  

---

## 🧑‍💻 Author
**Tanmay Agarwal**  
- [LinkedIn](https://www.linkedin.com/in/tanmay-agarwal-496bb132a/)  
- [GitHub](https://github.com/TanmayAgarwal40)
