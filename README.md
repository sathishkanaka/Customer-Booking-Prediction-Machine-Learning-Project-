# Customer-Booking-Prediction-Machine-Learning-Project-

Customer Booking Prediction (Machine Learning Project)

This project builds a machine learning model to predict whether a customer will complete a booking based on flight search and behavioral data. The goal is to assist airlines in identifying high-value customers and improving marketing or operational decisions.

🔍 Project Summary

Performed data exploration and cleaning

Engineered features such as lead-time bins, time-of-day, and extras requested

Trained a RandomForest model to predict booking_complete (0/1)

Evaluated model using 5-fold cross-validation

Generated key metrics and a one-slide PowerPoint summary

Built a feature importance chart to explain the model

📊 Model Performance (CV Evaluation)
Metric	Value
Accuracy	~0.84
Precision	~0.43
Recall	~0.05
F1-Score	~0.09
ROC AUC	~0.72
📁 Files Included

expanded_booking_notebook.ipynb — Full notebook with EDA, modeling & evaluation

booking_model_cv_results.pptx — One-slide summary

feature_importances_final.png — Top features chart

model_metrics_final.json — Evaluation metrics

🚀 How to Run
1. Install dependencies:
pip install -r requirements.txt


Or install manually:

pip install pandas numpy scikit-learn matplotlib python-pptx

2. Run the notebook:
jupyter notebook expanded_booking_notebook.ipynb

3. Upload customer_booking.csv

Place the dataset in the project root or /data folder.

🧠 Key Insights

Booking behavior is strongly influenced by:

Country of booking (booking_origin)

Route

Purchase lead time

Length of stay

Flight hour and duration

Probability predictions can be used to:

Target likely bookers

Optimize marketing

Improve booking funnel insights

📌 Notes

This is a simplified machine learning pipeline focused on model interpretability, explainability, and business usefulness rather than deep optimization.
