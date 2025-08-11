
# 🏠 House Price Prediction using Linear Regression

## 📌 Overview

This project implements a **Linear Regression model** to predict house prices based on:

* **Square footage**
* **Number of bedrooms**
* **Number of bathrooms**

It uses a **House Price Dataset** and trains a model to make predictions on unseen data.

---

## 📂 Dataset

The dataset contains the following columns:

* `square_footage` – Total area of the house in square feet.
* `bedrooms` – Number of bedrooms.
* `bathrooms` – Number of bathrooms.
* `price` – Price of the house (target variable).

---

## ⚙️ Installation

To run the project locally, install the required Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib
```

---

## 🚀 Usage

1. **Clone the repository** or download the project files.
2. Place the dataset file (e.g., `house_prices.csv`) in the project folder.
3. Run the Python script:

```bash
python house_price_prediction.py
```

---

## 📊 Model Details

The project uses **Multiple Linear Regression** from the `scikit-learn` library:

```python
from sklearn.linear_model import LinearRegression
```

**Steps:**

1. Load the dataset using **Pandas**.
2. Select features: `square_footage`, `bedrooms`, `bathrooms`.
3. Train the linear regression model.
4. Predict prices for test data.
5. Evaluate using metrics like **R² score** and **Mean Squared Error (MSE)**.

---

## 📈 Example Output

After training, you’ll get:

* Model coefficients
* Model intercept
* R² score
* Predictions for sample houses

Example:

```
Model Coefficients: [150.5, 20000, 30000]
Intercept: 50000
R² Score: 0.85
Predicted Price for sample input: $320,000
```

---

## 📌 Future Improvements

* Add more features (location, age of property, etc.).
* Experiment with **polynomial regression** for better accuracy.
* Deploy as a **Flask/Django API**.

---

## 🖋 Author

**Nirmal Chaturvedi**

---

If you want, I can now **write the complete Python code** for this README and run it with your dataset to generate real output.
Do you want me to proceed with that?
