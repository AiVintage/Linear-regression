# 🌸 Insurance Dataset – Linear Regression Analysis

## 📌 Project Overview
This project applies **Linear Regression** to explore the relationship between a person’s **age** and **insurance charges**.  
We evaluate the model using **Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score** to assess prediction accuracy.  

---

## 📂 Dataset
- **Source:** `insurance.csv`  
- **Features:** age, sex, bmi, children, smoker, region  
- **Target:** charges  

**Sample data:**
| age | sex    | bmi   | children | smoker | region    | charges      |
|-----|--------|-------|----------|--------|-----------|--------------|
| 19  | female | 27.9  | 0        | yes    | southwest | 16884.924    |
| 18  | male   | 33.77 | 1        | no     | southeast | 1725.5523    |
| 28  | male   | 33.0  | 3        | no     | southeast | 4449.462     |

---

## ⚙️ Approach
1. **Data Preprocessing**  
   - Identified numeric and categorical columns.  
   - Selected `age` as the independent variable and `charges` as the target.  

2. **Model Training**  
   - Linear Regression model (`sklearn.linear_model.LinearRegression`)  

3. **Evaluation**  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - R² Score  
   - Regression coefficients and intercept  

---

## 📊 Results
**Regression Equation:**  
charges = 257.72 * age + 3165.89


- **Mean Squared Error (MSE):** 133,440,978.61  
- **Root Mean Squared Error (RMSE):** 11,551.67  
- **R² Score:** 0.089  

**Scatter Plot with Regression Line:**  
![Age vs Charges](scatter_plot.png)  

**Conclusion:**  
- Age is **positively correlated** with insurance charges.  
- The low R² (0.089) indicates age alone explains **only ~8.9%** of the variability in charges.  
- Other factors like BMI, smoking, and number of children likely have a stronger influence.  

---

## ✅ Key Takeaways
- Linear regression captures a **general upward trend** of charges with age.  
- For **better prediction accuracy**, a more complex model including additional variables is recommended.  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** pandas, matplotlib, scikit-learn  

---

## 👨‍💻 Author
**AiVintage (Veli)**  
Data Science Graduate | Skilled in Python, Machine Learning, AI, SQL & Data Analysis  
[GitHub](https://github.com/AiVintage) | [LinkedIn](#)
