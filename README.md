Churn Intelligence Engine
�
�
�
�
📌 Overview
This project focuses on predicting customer churn using Machine Learning.
Instead of chasing accuracy, the model is designed to maximize recall, ensuring that most at-risk users are identified early.
In simple terms:
Catch more churn users, even if it means a few false alarms.
⚙️ Tech Stack
Python
XGBoost
Scikit-learn
SHAP
Matplotlib
📊 Model Performance
🔹 Confusion Matrix
�
The model captures a large portion of churn users (high recall) but also produces false positives.
This trade-off is intentional and aligns with real-world business needs where missing a churn user is more costly than a false alert.
🔹 SHAP Feature Importance
�
SHAP analysis provides explainability by highlighting key drivers of churn:
Binge watch sessions
Watch sessions per week
Engagement recency
These features strongly influence user retention behavior.
🎯 Key Insights
Model is recall-focused, not accuracy-focused
User engagement patterns are strong churn indicators
Explainability (SHAP) adds trust to predictions
💼 Business Impact
Early identification of at-risk users
Enables targeted retention campaigns
Supports data-driven decision making
⚖️ Trade-Off Strategy
High Recall ⚡ vs Low Precision

More churn users detected ✅
More false positives ⚠️
This reflects a business-first ML approach rather than a purely academic one.
🚀 Conclusion
This project demonstrates how machine learning can go beyond metrics and focus on real-world impact, combining prediction with explainability.

![Confusion Matrix](https://github.com/santoshml-lab/beyond-accuracy-churn-model/blob/main/confusion_matrix%20(2).png)
![SHAP]()
