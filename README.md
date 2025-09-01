**Air Quality Index (AQI) Predictor**
This project predicts Air Quality Index (AQI) pollutants (CO, NO₂, NMHC, etc.) using machine learning models such as Linear Regression and KNN Regression.
The goal is to provide early insights into pollution levels using sensor and weather data, enabling better awareness, research, and decision-making.
Features
Multi-pollutant prediction (CO, NO₂, NMHC, etc.)
Implements Linear Regression and KNN Regression models
Performance evaluation with RMSE and R² Score
Side-by-side comparison of Linear vs KNN performance
Data preprocessing for missing or invalid values
Insights into how weather and sensors affect pollutant concentration
Tech Stack
Language: Python
Libraries:
pandas, numpy (data handling)
scikit-learn (machine learning models)
matplotlib, seaborn (visualization)
Project Structure
AQI-Predictor/
 ┣ AQI.ipynb         # Main notebook (training, evaluation, charts)
 ┣ requirements.txt  # Dependencies
 ┣ README.md         # Project documentation
 ┗ dataset/          # UCI Air Quality dataset
How to Run
Clone the repository:
git clone https://github.com/yourusername/AQI-Predictor.git
cd AQI-Predictor
Install dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook:
jupyter notebook AQI.ipynb
Results and Comparison
Linear Regression: Fits a global line to model pollutant trends
KNN Regression: Uses neighborhood patterns for prediction
The comparison chart highlights RMSE and R² for each pollutant across both models.
Sample Output:
Applications
Government: Early warning systems and policy-making
Education: Teaching data science and ML with real-world datasets
Public: Understanding pollution patterns and awareness
References
UCI Machine Learning Repository: Air Quality Dataset
WHO Air Quality Standards
Developed by: Tanmay Agarwal
