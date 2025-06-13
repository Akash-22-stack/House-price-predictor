# House-price-predictor
Mini project using Linear regression to predict prices using room count
# House Price Predictor (Linear Regression from Scratch)

> A mini-project where I implemented linear regression **from scratch using only NumPy**, without scikit-learn, to predict housing prices based on the number of rooms in Boston Housing Dataset.

---

## Project Highlights

-  Implemented core linear regression logic using gradient descent
-  Built full pipeline from loading data → preprocessing → training → prediction
-  Visualized training loss and model performance
-  Learned the math behind gradient descent and model fitting
-  No use of external ML libraries like scikit-learn — everything done manually

---

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Dataset Used

- **Boston Housing Dataset**  
- Feature Used: `RM` (average number of rooms per dwelling)  
- Target: `MEDV` (Median value of owner-occupied homes)

---

##How It Works

1. Load dataset from `sklearn.datasets`
2. Normalize input features
3. Initialize weights `W` and bias `b`
4. Train model using gradient descent to minimize MSE loss
5. Plot training loss and predicted regression line

---

