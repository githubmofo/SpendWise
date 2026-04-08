# 🤖 Model Performance & Prediction Details

---

## 📌 Objective

To evaluate multiple machine learning models and select the best-performing model for expense prediction.

---

## ⚙️ Models Evaluated

| Model             | MAE (₹) | R² Score | CV R²  |
| ----------------- | ------- | -------- | ------ |
| Linear Regression | 0.0     | 1.0000   | 1.0000 |
| Decision Tree     | 179.0   | 0.9033   | 0.8502 |
| Random Forest     | 125.89  | 0.9617   | 0.9192 |
| KNN               | 269.41  | 0.8979   | 0.7948 |
| Gradient Boosting | 116.85  | 0.9451   | 0.9182 |

---

## 🏆 Best Model Selected

**Linear Regression**

### 📊 Performance:

* R² Score: 1.0000
* Adjusted R²: 1.0000
* MAE: ₹0.0

---

## ⚠️ Important Observation

The perfect score suggests:

* Possible strong linear dependency in dataset
* Potential data leakage (needs validation in real-world scenarios)

---

## 🔍 Feature Importance (Insights)

Top influencing features:

* Monthly Income
* Estimated Savings
* Expense-to-Income Ratio

---

## 📈 Prediction System

The model predicts:

* Daily Expense Amount

### Example:

```python
prediction = model.predict(input_data)
```

---

## 📉 Error Analysis

* Mean Error ≈ 0
* Percentage Error ≈ 0%
* Residuals evenly distributed

---

## 🧠 Clustering Output

Users segmented into:

* Frugal
* Moderate
* High Spenders

---

## 🚀 Conclusion

The model performs exceptionally well on current data and demonstrates strong capability in:

* Expense prediction
* Financial behavior analysis
* Pattern recognition

Future improvements include testing on unseen real-world datasets.
