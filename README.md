# 🔥 Wildfire Risk Prediction Using Regression ML Model

This project performs end-to-end wildfire risk prediction using multiple regression models based on the **Algerian Forest Fires dataset**. It covers complete data preprocessing, feature engineering, model training, evaluation, and deployment.

---

## 📌 Project Overview

Wildfires have become increasingly frequent and intense, affecting ecosystems and economies. In this project, we use real-world data from Algerian forests to build predictive models that estimate **Fire Weather Index (FWI)**, which indicates the potential for wildfire risk.

We build multiple regression models and compare their performance using standard metrics.

---

## 📊 Dataset Information

- **Source**: Algerian Forest Fires Dataset (UCI Repository)
- **Attributes**:
  - Temperature, Relative Humidity, Wind, Rain
  - DC, DMC, FFMC, ISI (fire danger indices)
  - FWI (target variable)
- **Target**: `FWI` (Fire Weather Index — numerical value)

---

## 🧹 Data Preprocessing

- Combined two region-wise datasets into one
- Converted region column to numerical category
- Converted all columns to appropriate data types
- Handled missing values
- Feature scaling using `StandardScaler`
- Split into `train` and `test` sets (80:20)

---

## 🤖 ML Models Used

- Linear Regression
- Lasso Regression
- Ridge Regression
- ElasticNet Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## 📈 Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## ✅ Best Model

After comparing multiple models, **Random Forest Regressor** achieved the best performance based on R² score and lowest errors.

---

## 📊 Visualizations

- Correlation Heatmap
- Feature Distribution
- Actual vs Predicted Line Plots
- Residual Plots

*(All visuals are included in the notebook for deeper insights.)*

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run Locally

1. Clone this repository
```bash
git clone https://github.com/udityamerit/Wildfire-Risk-Prediction-Using-Regression-ML-Model.git
cd Wildfire-Risk-Prediction-Using-Regression-ML-Model
````

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook End-to-End-ML_Project.ipynb
```

---

## 🧠 Future Scope

* Add Streamlit/Flask-based UI for public access
* Use time-series wildfire prediction (e.g. LSTM)
* Integrate satellite imagery using deep learning
* Build a real-time dashboard with geolocation mapping

---

## 🙋 Author

**Uditya Narayan Tiwari**
🎓 B.Tech CSE (AI/ML) – VIT Bhopal
🔗 [Portfolio](https://udityanarayantiwari.netlify.app)
🔗 [GitHub](https://github.com/udityamerit)
🔗 [LinkedIn](https://www.linkedin.com/in/uditya-narayan-tiwari-562332289/)

---

## 📄 License

This project is open-sourced under the MIT License.

