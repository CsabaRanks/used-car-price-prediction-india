# AI-Based Used Car Price Prediction (India)

## 📄 Project Overview

This project develops a machine learning model to predict used car prices in the Indian market.
The objective is not only to achieve high predictive accuracy, but also to understand the **economic structure of price formation**.

The project combines:

* structured feature engineering
* model benchmarking
* economic interpretation of model behavior

---

## 🚀 Key Results

* Best model: **Random Forest**
* Test performance: **R² ≈ 0.91**
* Lowest RMSE among all tested models
* Strong generalization with controlled overfitting

---

## 🧠 Key Insight

Used car pricing follows a **dual structure**:

* **Technical value drivers**
  → Power, Age, Engine, Mileage

* **Market adjustment factors**
  → Brand, Model, Location

👉 Machine learning models do not only predict prices —
they implicitly learn the **pricing logic of the market**.

---

## 📊 Model Comparison

| Model               | Test R²   | Test RMSE |
| ------------------- | --------- | --------- |
| Linear Regression   | 0.866     | 3.994     |
| Decision Tree       | 0.875     | 3.858     |
| Tuned Decision Tree | 0.894     | 3.550     |
| Lasso Regression    | 0.884     | 3.710     |
| **Random Forest**   | **0.913** | **3.205** |

---

## 📈 Visual Insights

### Feature Importance

* Power and Age dominate price formation
* Mileage has reduced importance due to correlation

### Error Behavior

* Strong accuracy for low and mid-range vehicles
* Higher deviations in premium segment

---

## 💰 Business Impact

Even small improvements in pricing accuracy create significant value:

* Average vehicle price: ~9.48 lakh INR
* 1% improvement ≈ 9,480 INR per vehicle
* At scale: **multi-million INR annual impact**

---

## 📄 Full Paper

👉 [Download Paper](paper/csaba_bakay_used_car_pricing.pdf)

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* Pandas / NumPy
* Matplotlib / Seaborn

---

## 📁 Repository Structure

```id="3df76a"
used-car-price-prediction-india/
│
├── paper/
├── notebook/
├── Figures/
```

---

## 👤 Author

**Csaba Bakay**
MIT Professional
Strategic Procurement & AI Benchmarking
