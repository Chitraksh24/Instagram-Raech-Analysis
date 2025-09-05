 Overview

Instagram is one of the most popular social media platforms, widely used for business promotion, content creation, and personal branding. However, frequent algorithm changes affect the reach of posts, making it harder for creators to plan content strategies.

This project uses Data Science & Machine Learning to analyze Instagram reach data and predict post impressions. By applying multiple regression models and performing hyperparameter tuning, we significantly improved prediction accuracy.

⸻

 Features

✔ Exploratory Data Analysis (EDA) with visualizations
✔ Synthetic data augmentation for better training
✔ ML models tested:
	•	Passive Aggressive Regressor (baseline)
	•	Passive Aggressive Regressor (tuned)
✔ Hyperparameter tuning using GridSearchCV
✔ Performance comparison before vs after tuning
✔ Export-ready results for reporting

⸻

📂 Dataset
	•	Dataset contains Instagram post statistics (e.g., likes, comments, shares, hashtags, captions, etc.).
	•	Target variable: Impressions (Reach)

Synthetic augmentation was performed to generate more training samples.

⸻

 Results

 Before Hyperparameter Tuning
	•	R² Score: 0.4945
	•	RMSE: 4430.86
	•	Mean CV Score: 0.6963

 After Hyperparameter Tuning
	•	Best CV Score: 0.7718
	•	R² Score: 0.8912
	•	RMSE: 2055.18

 Accuracy nearly doubled, and error reduced by 2x.`
