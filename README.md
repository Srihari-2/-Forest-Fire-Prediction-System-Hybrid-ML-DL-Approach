Forest Fire Prediction:A Hybird Approach Using CBFR,LSTM, and XGBoost
A hybrid wildfire prediction system using CBFR, LSTM, and XGBoost models with a Linear Regression meta-learner. It analyzes historical and real-time data to predict forest fire risks accurately, supporting early warnings and proactive disaster management

Features
CBFR (Context-Based Fire Risk Model): Analyzes historical weather and wildfire data, detects anomalies using clustering techniques, and generates dynamic fire risk scores.  
LSTM Model: Captures long-term temporal dependencies to identify wildfire trends over time.  
XGBoost Model: Learns complex, non-linear patterns in fire behavior based on environmental features.  
Ensemble Meta-Learner: Combines predictions from LSTM and XGBoost using Linear Regression for higher accuracy.  
Performance Evaluation: Compared with Random Forest, achieving lower RMSE and improved prediction reliability.

Tech Stack
Languages/Frameworks:Python, TensorFlow/Keras, XGBoost  
Data Processing: pandas, NumPy  
Visualization: Matplotlib, Seaborn  
Platform: Google Colab  
Modeling: Clustering, Time Series Analysis, Linear Regression Ensemble  

 Results
Real-time fire risk estimation  
Adaptive, region-specific forecasting  
Better performance than traditional models (e.g., Random Forest)
