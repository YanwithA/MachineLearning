**ML Coursework: Airbnb Price & Telco Churn**

This repo contains two end-to-end ML pipelines showcasing practical data prep, imbalance handling, model training, and honest evaluation.

Regression (Airbnb NYC): Predict nightly listing price using LightGBM (Huber) vs MLPRegressor on log-price, with metrics reported in both log and original price units.

Classification (IBM Telco Churn): Predict customer churn using Logistic Regression (class-weighted) vs MLPClassifier + SMOTENC, with PR-AUC/F1 focus and threshold tuning from out-of-fold probabilities.

**Dataset Link**
Airbnb_listings_nyc : https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/data

telco_churn : https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data
