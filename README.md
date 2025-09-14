
#  Medical Charges Prediction using Linear Regression

This project predicts the **medical charges of a person based on their age**, assuming the person is a **smoker**.  
It is a beginner-level machine learning project built to demonstrate the use of **Linear Regression** for predictive modeling.

---

## 📊 Dataset
- The dataset is included in the repository
- Features used:
  - `age` → Age of the person  
  - `smoker` → Assumed "yes" for this model  
- Target:  
  - `charges` → Medical cost

---

## 🔎 Project Workflow
1. **Data Preprocessing**
   - Filtered dataset for smokers only.  
   - Used `age` as independent variable (X).  
   - `charges` as dependent variable (y).  

2. **Exploratory Data Analysis (EDA)**
   - Scatter plot of age vs. charges.  
   - Observed positive correlation (older smokers tend to have higher charges).  

3. **Model Training**
   - Applied **Linear Regression** using Scikit-learn.  
   - Fitted model: `charges = b0 + b1 * age`  

4. **Evaluation**
   - Metrics: R² Score, Mean Squared Error (MSE).  
   - Visualized regression line on scatter plot.  

