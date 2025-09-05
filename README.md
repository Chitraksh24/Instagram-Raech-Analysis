# 📊 Instagram Reach Analysis using Machine Learning

## 📌 Overview
Instagram is one of the most popular social media platforms, widely used for business promotion, content creation, and personal branding.  
However, frequent algorithm changes affect the reach of posts, making it harder for creators to plan content strategies.  

This project uses **Data Science & Machine Learning** to analyze Instagram reach data and predict post impressions.  
By applying multiple regression models and performing hyperparameter tuning, we significantly improved prediction accuracy.

---

## 🚀 Features
✔️ Exploratory Data Analysis (EDA) with visualizations  
✔️ Synthetic data augmentation for better training  
✔️ ML models tested:  
- Passive Aggressive Regressor (baseline)  
- Random Forest Regressor (tuned)  
✔️ Hyperparameter tuning using GridSearchCV  
✔️ Performance comparison **before vs after tuning**  
✔️ Export-ready results for reporting  

---

## 📂 Dataset
- Dataset contains Instagram post statistics (likes, comments, shares, hashtags, captions, etc.).  
- **Target variable:** Impressions (Reach).   

---

## 📊 Results

### 🔹 Before Hyperparameter Tuning
- **R² Score:** 0.4945  
- **RMSE:** 4430.86  
- **Mean CV Score:** 0.6963  

### 🔹 After Hyperparameter Tuning
- **Best CV Score:** 0.7718  
- **R² Score:** 0.8912  
- **RMSE:** 2055.18  

✅ Accuracy nearly doubled, and error reduced by **2x**.  

---

## 📈 Visuals

| Metric          | Before Tuning | After Tuning |
|-----------------|---------------|--------------|
| R² Score        | 0.4945        | 0.8912       |
| RMSE            | 4430.86       | 2055.18      |
| Mean CV Score   | 0.6963        | 0.7718       |

(Add plots here if you export them as PNGs — e.g., model comparison bar chart, correlation heatmap, word clouds)

---

## ⚙️ Installation & Usage

1. **Clone the repository**
```bash
git clone https://github.com/your-username/instagram-reach-analysis.git
cd instagram-reach-analysis
