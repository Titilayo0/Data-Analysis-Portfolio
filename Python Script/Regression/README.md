# Insurance Cost Prediction using Regression Analysis

## Executive Summary
This project aims to predict **insurance costs** using **regression analysis** based on key factors such as age, BMI, smoking status, and other demographic details. The model is implemented using Python and leverages **linear regression** for cost estimation.

---
## Project Objectives
- Develop a **predictive model** to estimate insurance costs.
- Utilize **regression analysis** for cost estimation.
- Interpret feature importance to understand cost drivers.
- Ensure model accuracy through **performance evaluation metrics**.

---
## Project Scope
- **Data Preprocessing:** Handling missing values, encoding categorical features.
- **Exploratory Data Analysis (EDA):** Identifying trends and relationships in the data.
- **Model Selection:** Using **Linear Regression**, with potential comparisons to other models.
- **Evaluation Metrics:** Using **Mean Squared Error (MSE)** and **R-squared (R²)** for performance assessment.

---
## Dataset Used
The dataset contains key attributes affecting insurance costs:
| Feature          | Description                            |
|----------------|--------------------------------|
| age           | Age of the individual           |
| sex           | Gender (Male/Female)            |
| bmi           | Body Mass Index                 |
| children      | Number of dependent children    |
| smoker       | Smoker status (Yes/No)          |
| region       | Residential region              |
| charges      | Actual insurance cost (target)  |

---
## Methodology
1. **Import Libraries**: Use Pandas, NumPy, Scikit-learn, and Matplotlib.
2. **Load Dataset**: Read data into a Pandas DataFrame.
3. **Data Cleaning**: Handle missing values, convert categorical variables using encoding.
4. **EDA**: Visualize correlations and outliers.
5. **Feature Engineering**: Scale numerical variables and apply one-hot encoding for categorical data.
6. **Model Training**: Use `LinearRegression()` from `sklearn.linear_model`.
7. **Model Evaluation**: Assess performance using **MSE, RMSE, and R² Score**.
8. **Prediction**: Use the trained model to predict new insurance costs.

---
## Installation & Setup
### Prerequisites:
Ensure you have **Python 3.7+** installed with the following dependencies:
```sh
pip install pandas numpy scikit-learn matplotlib seaborn
```
### Running the Script:
```sh
python insurance_cost_prediction.py
```

---
## Key Performance Indicators (KPIs)
- **Mean Squared Error (MSE)**: Measures average squared differences between actual and predicted values.
- **Root Mean Squared Error (RMSE)**: Helps interpret model error in cost units.
- **R-squared (R²)**: Explains variance captured by the model.

---
## Conclusion & Recommendations
- The regression model successfully predicts insurance costs with reasonable accuracy.
- Feature analysis shows that **smoking** and **BMI** are the strongest predictors of insurance costs.
- Future improvements can include **non-linear models** like **Random Forest or XGBoost** for better accuracy.

---
## Author
Developed by **Titilayo Ologun**


