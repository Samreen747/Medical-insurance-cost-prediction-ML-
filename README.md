#  Medical Insurance Cost Prediction using Machine Learning

##  Overview

This project predicts medical insurance charges based on features such as age, BMI, smoking status, and region. It demonstrates a complete machine learning pipeline, including data preprocessing, feature engineering, model training, and comparison of multiple algorithms.

---

##  Features

* End-to-end machine learning pipeline
* Data cleaning and preprocessing
* Feature engineering and encoding
* Multiple model training and comparison
* Visualization and insight generation

---

##  Dataset

The dataset contains demographic and health-related information.

###  Features:

* **Age** – Age of the individual
* **Sex** – Gender
* **BMI** – Body Mass Index
* **Children** – Number of dependents
* **Smoker** – Smoking status
* **Region** – Residential area
* **Charges** – Medical insurance cost (**Target Variable**)

---

##  Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

##  Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Insights
4. Data cleaning and Preprocessing
5. Feature engineering 
6. Feature Scaling
7. Feature extraction
8. Model Training
9. Model Prediction
10. Model Evaluation
11. Model Comparison
12. Visualization

---

##  Models Used & Performance

### 🔹 Linear Regression

* R² Score: **0.80**
* Provides stable and consistent predictions

### 🔹 Decision Tree Regressor

* R² Score: **0.74**
* Lower performance due to overfitting

###  Random Forest Regressor  (Best Model)

* R² Score: **0.86**
* Improved accuracy by handling non-linear relationships
* Reduced overfitting compared to Decision Tree

---

##  Results

* Random Forest achieved the **best overall performance**
* Linear Regression performed well but struggled with non-linear patterns
* Decision Tree showed higher variance and overfitting
* Smoking status is the most significant factor affecting insurance charges
* BMI and age also have strong influence

---

##  Key Insights

* Smokers have significantly higher medical charges than non-smokers
* Higher BMI leads to increased insurance costs
* Age is positively correlated with charges
* Non-linear relationships exist in the dataset, better captured by ensemble models

---

##  Conclusion

This project demonstrates how different machine learning models perform on a real-world dataset.
Among all models, **Random Forest provided the best results** by capturing complex relationships in the data.

---

##  Future Improvements

* Hyperparameter tuning for better performance
* Try Gradient Boosting / XGBoost
* Deploy model using Streamlit
* Use larger datasets for better generalization

---

##  How to Run

```bash
git clone https://github.com/your-username/insurance-cost-prediction.git
cd insurance-cost-prediction
pip install -r requirements.txt
jupyter notebook
```

---

##  Project Structure

```
insurance-cost-prediction/
│
├── data/
│   └── insurance.csv
├── notebook/
│   └── insurance_cost_prediction.ipynb
├── README.md
└── requirements.txt
```

---

##  Author

**P Samreen**

* GitHub: https://github.com/Samreen747
* LinkedIn: https://www.linkedin.com/in/p-samreen/

---


