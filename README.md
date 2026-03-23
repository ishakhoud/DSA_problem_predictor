# 📊 DSA Progress Prediction using Simple Linear Regression

This project uses **Simple Linear Regression** to predict how many problems can be solved based on the number of days of practice.

---

## 🚀 Project Idea

The goal of this project is to understand and implement a basic Machine Learning model that predicts:

> 📈 *Number of problems solved (output)*  
> based on  
> ⏳ *Number of days practiced (input)*  

---

## 🧠 Concepts Used

- Simple Linear Regression
- Data Visualization (Matplotlib)
- Train-Test Split
- Model Training & Prediction

---

## 📂 Dataset

The dataset is manually created and represents a learning pattern over time.

| Days | Problems Solved |
|------|-----------------|
| 1    | 1               |
| 2    | 6               |
| 4    | 10              |
| ...  | ...             |

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📈 Model Workflow

1. Load dataset using Pandas  
2. Split data into training and testing sets  
3. Train model using `LinearRegression()`  
4. Visualize results using scatter plot + regression line  
5. Predict future outcomes  

---

## 🔮 Example Prediction

```python
model.predict([[23]])
