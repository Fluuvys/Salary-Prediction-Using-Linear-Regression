# 📈 Salary Prediction Using Linear Regression

This project implements **linear regression from scratch** using **NumPy** to predict salaries based on years of experience. It demonstrates the fundamental concepts behind linear regression, including gradient descent optimization.

---

## 🚀 **Project Overview**

The goal is to predict the salary of an individual given their years of experience. The model is trained using a simple linear equation:

$$
y = mx + b
$$

Where:  
- **\( y \)** = Predicted salary  
- **\( m \)** = Slope of the line (weight)  
- **\( x \)** = Years of experience (input)  
- **\( b \)** = Intercept (bias)  

---

## 🧠 **Steps of Linear Regression**

1. **Pick a Sample from Training Data**  
   Select data points (years of experience, salary) for training.

2. **Compute Predicted Value (\( \hat{y} \))**  
   Apply the linear function:  
   $$
   \hat{y} = mx + b
   $$

3. **Compute Loss Function**  
   Use **Mean Squared Error (MSE)** to measure the difference between actual and predicted salaries:  
   $$
   L = (y - \hat{y})^2
   $$

4. **Compute Derivatives (Gradients)**  
   Find the gradients with respect to \( m \) and \( b \) to minimize the loss:  
   $$
   \frac{\partial L}{\partial m} = 2(x)(\hat{y} - y)
   $$  
   $$
   \frac{\partial L}{\partial b} = 2(\hat{y} - y)
   $$

5. **Update Parameters Using Gradient Descent**  
   Adjust \( m \) and \( b \) to reduce the loss:  
   $$
   m = m - \alpha \frac{\partial L}{\partial m}
   $$  
   $$
   b = b - \alpha \frac{\partial L}{\partial b}
   $$  
   Where \( \alpha \) is the **learning rate**.

---

## 📊 **Dataset**

- **`Salary_dataset.csv`**  
  Contains data with two columns:
  - **Years of Experience**  
  - **Salary**

---

## ⚙️ **How to Run**

1. **Install dependencies:**
   ```bash
   pip install numpy pandas

2. **Open my jupyter notebook**
---

## 📈 **Model Evaluation**
Mean Squared Error (MSE): Measures average squared difference between actual and predicted salaries.
Root Mean Squared Error (RMSE): Square root of MSE, interpretable in the same unit as the salary.

---

## 💡 **Future Improvements**
Implement Polynomial Regression for non-linear data.
Use real-world datasets for more complex predictions.
Add visualizations to show data trends and model fit.

---

## 📬 **Contact**
If you have any questions or suggestions, feel free to reach out!

Made with ❤️ using NumPy.
