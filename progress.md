# 🚀 ISLP Implementation Progress

Tracking hands-on implementations from *Introduction to Statistical Learning with Python (ISLP)*.

---

## 📊 Linear Regression

### 📌 Simple Linear Regression
- 🔗 [Notebook](./code/LinearRegression.ipynb)
- ⚙️ Implemented: From scratch using NumPy + comparison with `scikit-learn`
- ✅ Status: Completed
- 🧠 Key Learnings:
  - Manual calculation of slope and intercept
  - Evaluated model using **R² score**
  - Matched results with `sklearn.linear_model.LinearRegression`
  - Visualized the fitted regression line on scatter plot

---

### 📌 Multiple Linear Regression
- 🔗 [Notebook](./code/mlr.ipynb)
- ⚙️ Implemented: From scratch using vectorized matrix algebra + `scikit-learn` comparison
- ✅ Status: Completed
- 🧠 Key Learnings:
  - Matrix formula: \( \beta = (X^T X)^{-1} X^T y \)
  - Evaluated model using **R²** and **MSE**
  - Visualized model predictions and performance using data plots
  - Verified results using `sklearn.linear_model.LinearRegression`

---

## 🔜 Coming Next

- [ ] Logistic Regression (Chapter 4)
- [ ] Polynomial Regression (as extension)
