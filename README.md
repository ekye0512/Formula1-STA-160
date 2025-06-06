# Predicting Formula 1 Finishing Positions with Machine Learning  
**Final Capstone Project — STA 160 @ UC Davis**

Hi! I’m **Eric Kye**, a huge Formula 1 fan and a stats major at UC Davis.  
This project is my final capstone for **STA 160** and wraps up my four-year undergrad journey in statistical data science.

Using historical race data from a Kaggle competition, I applied machine learning models to predict driver finishing positions (1–20). This challenge let me bring together everything I’ve learned in undergrad—data cleaning, visualization, model building—and apply it to a real-world problem in a sport I love.

---


![image](https://github.com/user-attachments/assets/1eefe209-3412-422c-a3ab-cbfff1838d6c)
*Photo credit: [Motorsport Week](https://www.motorsportweek.com/2025/02/20/lewis-hamilton-names-detail-that-will-make-charles-leclerc-not-easy-to-beat-at-ferrari/)*

---

## Project Overview
- **Course**: STA 160 - Statistical Learning
- **Dataset**: Formula 1 race data (2.8M+ rows cleaned to 21,998)
- **Goal**: Predict race finishing positions using pre-race features
- **Models Used**:
  - Random Forest (Best - RMSE: 4.47)
  - XGBoost
  - Gradient Boosting
  - Lasso Regression
  - Ridge Regression

---

## Key Takeaways
- Tree-based models worked best with F1’s complex, non-linear dynamics
- Starting grid, wins, and season points were the most predictive features
- XGBoost improved with tuning, but Random Forest remained the most accurate
- Data cleaning was the most important (and hardest) step
