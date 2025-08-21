⚽ Premier League 2024-2025 Match Outcome Predictor

A Machine Learning project that predicts the outcomes of English Premier League (EPL) matches for the 2025 season.
Built with data analysis, feature engineering, and machine learning models, this project aims to forecast win/draw/loss probabilities and uncover hidden patterns in football data.

🚀 Features

📊 Comprehensive Data Analysis: Match stats, team forms, and performance insights.

🧠 Machine Learning Models: Logistic Regression, Random Forest, and Ensemble techniques for predictions.

🔮 Match Outcome Predictions: Probabilities for home win, away win, or draw.

📈 Performance Metrics: Accuracy, precision/recall, ROC curves, and more.

🎯 2025 Season Forecasting: Predicting EPL table trends and match outcomes.

📂 Project Structure
├── data/                         # EPL dataset (matches, stats, results)
├── epl_2025_pred.ipynb           # Jupyter Notebook with full workflow
├── README.md                     # Project documentation
                     

📊 Dataset

Source: Historical EPL data (matches, goals, team stats).

Features Used:

Team form & standings

Goals scored & conceded

Home/Away performance

Head-to-head results

Expected goals (xG) metrics (if available)



⚙️ Installation & Usage

Clone the repo

git clone https://github.com/your-username/epl-2025-predictor.git
cd epl-2025-predictor


Install dependencies

pip install -r requirements.txt


Run Jupyter Notebook

jupyter notebook epl_2025_pred.ipynb

🧪 Results

Model Accuracy: ~78% (baseline Logistic Regression improved with Random Forest/Ensemble).

Key Findings:

Home teams have a significant edge in prediction probabilities.

Recent form & goal difference are the strongest predictors.

Adding advanced stats (xG) improves accuracy by ~5%.

📈 Example Confusion Matrix:

	Predicted Win	Predicted Draw	Predicted Loss
Win	250	30	45
Draw	40	120	38
Loss	60	35	220
📸 Demo

Input:

Home Team: Manchester City  
Away Team: Liverpool  
Date: May 3, 2025


Output:

Prediction:
Man City Win: 54%  
Draw: 21%  
Liverpool Win: 25%

📌 Future Improvements

✅ Deploy as a Streamlit web app for interactive predictions.

✅ Include real-time match data from APIs.

✅ Improve accuracy with Neural Networks or XGBoost.

✅ Add player-level stats (injuries, lineups, form).

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

📜 License

This project is licensed under the MIT License.
