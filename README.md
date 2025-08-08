🏏 Cricket Match Analysis & Prediction Platform
📌 Overview
This project is a real-time cricket match prediction and analysis platform powered by Apache Spark, Kafka, and Machine Learning models. It predicts match results and player performance with up to 92% accuracy and visualizes live insights through Power BI dashboards.

The platform is designed to assist analysts, coaches, and cricket enthusiasts with data-driven decision-making during live matches.

🚀 Features
Real-time data pipeline using Apache Spark and Kafka to process live cricket stats.

Machine Learning models (Logistic Regression, Random Forest, K-Means) for outcome predictions.

Dynamic Power BI dashboards to display:

Live win probabilities

Player performance stats

Strategic recommendations

Interactive team selection for head-to-head match predictions.

Visualization of clustering results for team performance grouping.

🛠️ Tech Stack
Languages & Libraries:

Python, Pandas, NumPy, Matplotlib, Seaborn

PySpark (MLlib, DataFrames)

Scikit-learn

Data Processing:

Apache Spark

Apache Kafka (for streaming data)

Visualization:

Power BI

Tableau (optional)

Databases:

CSV, Excel

📂 Project Structure

├── Cricket Analysis and Prediction Using ML Tools.py  # Main Python script
├── Team India.pbix                                    # Power BI dashboard (India)

├── Team Australia.pbix                                # Power BI dashboard (Australia)

├── winning.xlsx                                       # Match results dataset

├── batting.xlsx                                       # Player batting stats

├── bowling.xlsx                                       # Player bowling stats

└── README.md                                          # Documentation

📊 Machine Learning Models
Logistic Regression – Multinomial classification for match outcomes.

Random Forest Classifier – Ensemble learning for robust predictions.

K-Means Clustering – Grouping teams based on performance metrics.

Model performance is evaluated using Accuracy Scores and Confusion Matrices.

👤 My Major Role
I was responsible for:

Data Cleaning & Preprocessing – Ensuring accuracy and consistency in raw datasets.

Power BI Dashboard Development – Integrating player statistics into interactive visual reports.

Visualization Integration – Making real-time insights accessible and visually engaging.

📈 Sample Output

Prediction Example:

Logistic Regression predicts: India wins  

Random Forest predicts: India wins  


