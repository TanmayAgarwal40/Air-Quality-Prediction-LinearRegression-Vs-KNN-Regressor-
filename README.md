# Air Quality Index (AQI) Predictor

This project predicts Air Quality Index (AQI) pollutants (CO, NO₂, NMHC, etc.) using machine learning models such as **Linear Regression** and **KNN Regression**.  
The goal is to provide early insights into pollution levels using sensor and weather data, enabling better awareness, research, and decision-making.

---

## Features
- Multi-pollutant prediction (CO, NO₂, NMHC, etc.)  
- Implements Linear Regression and KNN Regression models  
- Performance evaluation with RMSE and R² Score  
- Side-by-side comparison of Linear vs KNN performance  
- Data preprocessing for missing or invalid values  
- Insights into how weather and sensors affect pollutant concentration

---

## Tech Stack
**Language:** Python

**Libraries:**
- `pandas`, `numpy` (data handling)  
- `scikit-learn` (machine learning models)  
- `matplotlib`, `seaborn` (visualization)

---

## Project Structure

AQI-Predictor/
┣ AQI.ipynb # Main notebook (training, evaluation, charts)
┣ requirements.txt # Dependencies
┣ README.md # Project documentation
┗ dataset/ # UCI Air Quality dataset
┗ results/ # Saved plots (rmse_comparison.png, co_actual_vs_pred.png)


---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AQI-Predictor.git
cd AQI-Predictor

pip install -r requirements.txt
jupyter notebook AQI.ipynb

Results and Comparison
Linear Regression: Fits a global line to model pollutant trends
KNN Regression: Uses neighborhood patterns for prediction
The comparison chart highlights RMSE and R² for each pollutant across both models.

Applications
Government: Early warning systems and policy-making
Education: Teaching data science and ML with real-world datasets
Public: Understanding pollution patterns and awareness

References
UCI Machine Learning Repository: Air Quality Dataset
WHO Air Quality Standards

👨‍💻 Author
Developed by: Tanmay Agarwal
🚀 Contributions and suggestions are welcome!


---

✅ This file already has:
- **Gray code blocks** (via fenced ```bash``` / ```python``` / ```markdown```)  
- **Graph placeholders** (`results/rmse_comparison.png`, `results/CO_actual_vs_pred.png`) — they will show up once you push the generated images into `results/` folder.  

Do you also want me to **generate the `requirements.txt` content** for you automatically from your notebook, so you don’t miss any library?
