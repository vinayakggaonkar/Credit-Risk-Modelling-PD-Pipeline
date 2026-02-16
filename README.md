Credit Risk Modelling and PD Prediction Pipeline



📌 Overview



End-to-end Probability of Default (PD) modelling pipeline built on retail unsecured loan data. The project demonstrates institutional-grade preprocessing, leakage handling, feature engineering, model development, and risk evaluation using banking-standard metrics.



📊 Model Performance



ROC-AUC: 0.70



KS Statistic: 0.30



Gini Coefficient: 0.40



Accuracy: 84.5%



🔍 Methodology



Data cleaning \& leakage removal



Feature engineering (loan-to-income, credit depth, inquiry pressure)



One-hot encoding



XGBoost model training



ROC \& KS curve validation



Monotonic risk band segmentation



🏦 Risk Segmentation



The model produces monotonic risk bands with increasing default rates:



Very Low: ~5%



Low: ~9%



Medium: ~14%



High: ~20%



Very High: ~31%



⚙️ Tools Used



Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, SciPy


📈 Visual Evaluation









💼 Business Impact



Enabled risk-based borrower segmentation using monotonic PD ranking



Demonstrated application-level PD modelling with leakage-safe validation



Produced interpretable risk bands for potential credit decisioning



Validated discriminatory power using ROC-AUC, KS, and Gini metrics

