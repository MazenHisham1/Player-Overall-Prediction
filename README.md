# FIFA 23 Player Overall Rating Prediction ⚽️📊

## 📌 Project Overview
This project focuses on predicting the **Overall rating** of players in the FIFA 23 dataset using **machine learning techniques**. The "Overall" column represents a player’s general ability and is widely used for scouting, analysis, and team building.  

By analyzing player attributes such as pace, shooting, passing, dribbling, defending, and physicality, this project builds predictive models to estimate the **Overall rating** of football players.  

**Goals:**  
- Explore the FIFA 23 dataset through **Exploratory Data Analysis (EDA)**  
- Train machine learning models to predict the **Overall rating**  
- Evaluate models using appropriate metrics  
- Provide insights into the most important features influencing a player’s overall score  

---

## 📂 Dataset
- **Source:** [Kaggle - FIFA 23 Complete Player Dataset](https://www.kaggle.com/datasets/bryanb/fifa-player-stats-database)  
- **Key Features (attributes):**  
  - 'Age', 'Potential', 'Club', 'Value', 'Wage', 'Special',
  -  'Preferred Foot', 'International Reputation', 'Weak Foot',
  -  'Skill Moves', 'Body Type', 'Position', 'Height', 'Weight',
  -  'Release Clause', 'Role', 'Contract_years', 'Fitness_level',
  -  'Attacking_WorkRate', 'Defensive_WorkRate'  
  
- **Target Variable:**  
  - **`Overall`** → Player’s overall rating  

---

## 🛠️ Tech Stack
- **Language:** Python 
- **Libraries:**  
  - `numpy`, `pandas` → Data handling  
  - `matplotlib`, `seaborn`,`plotly` → Visualization  
  - `scikit-learn` → Machine learning models  
---

## 📊 Methodology
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features  
   - Feature scaling & normalization  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of player attributes  
   - Correlation heatmaps  
   - Top features influencing `Overall`  

3. **Model Building**  
   - Linear Regression  
   - Random Forest Regressor  
   - Gradient Boosting
   - Decision Tree
   - Extra Trees

4. **Model Evaluation**  
   - Metrics: `R²`, `RMSE`  
   - Feature importance analysis  

---

## 📈 Results
- The best-performing model achieved:  
  - **R² Score:** 97.5  
  - **RMSE:** 1.26  

---
