# Student Performance Factors – Machine Learning Project

## Overview

This project aims to **predict students' exam scores** using Machine Learning techniques based on different performance factors such as study habits, attendance, and lifestyle attributes.

The project demonstrates a **complete ML workflow**, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and model evaluation.

The dataset used in this project is **Student Performance Factors** from Kaggle.

---

## Project Workflow   

1. **Data Cleaning**

   * Handling missing values
   * Fixing inconsistent values
   * Preparing the dataset for analysis

2. **Exploratory Data Analysis (EDA)**

   * Visualizing feature distributions
   * Detecting outliers
   * Understanding relationships between variables

3. **Feature Engineering**

   * Encoding categorical variables
   * Scaling numerical features
   * Preparing features for machine learning models

4. **Model Training**
   Several regression models were trained to predict student exam scores:

   * Linear Regression
   * Ridge Regression
   * Random Forest Regressor
   * XGBoost Regressor
   * Decision Tree Regressor
   * KNN Regressor
   * SVR
   * Polynomial Regression

5. **Hyperparameter Tuning**

   * RandomizedSearchCV

   These techniques were used to optimize model performance.

6. **Model Evaluation**
   Models were evaluated using regression metrics such as:

   * R² Score
   * MSE (Mean Squared Error)
   * MAE (Mean Absolute Error)

---

## Visualization

The project includes several visualizations to better understand the dataset and the model performance:

* Distribution plots
* Correlation analysis
* Feature importance
* Actual vs Predicted comparison

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Repository Structure

```
student-performance-factors-ml/
│
├── student_performance_factors_project.ipynb
├── README.md
└── dataset/
```

---

## Key Takeaways

* Understanding how different factors affect student performance
* Building regression models for prediction
* Applying preprocessing pipelines for machine learning
* Performing hyperparameter tuning to improve model accuracy

---

## Conclusion

After training and evaluating multiple regression models, the **Random Forest Regressor** achieved the best performance with an **accuracy (R² score) of approximately 94%**.

Feature importance analysis showed that the most influential factors affecting student exam scores are:

* **Attendance**
* **Hours Studied**
* **Access to Internet / Learning Resources**

These features play a significant role in predicting student performance and highlight how study habits and access to educational resources strongly impact academic outcomes.

---

## Future Improvements

Possible future improvements for this project include:

* Building a deployment-ready model
* Creating a simple web application for predictions

---

## Author

**Hesham Dahy**

Machine Learning Enthusiast interested in Machine Learning Engineering.

