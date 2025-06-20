![sales forecast](https://github.com/user-attachments/assets/0cdf199f-e6cd-4928-b01e-0b1c6b2f863d)
![Monthly sales](https://github.com/user-attachments/assets/dd9ac335-811f-4f4b-8230-eefa11ef7127)
# 📈 Sales Forecasting using ARIMA

This project demonstrates time series forecasting of daily sales data using the ARIMA (AutoRegressive Integrated Moving Average) model. The goal is to analyze historical sales and predict future trends.

---

## 🔍 Project Overview

- **Dataset**: Daily sales data (CSV)
- **Objective**: Predict future sales values using ARIMA
- **Tools**: Python, Pandas, Matplotlib, Statsmodels, Jupyter Notebook
- **Output**: Forecasted sales values, RMSE metric, and plots

---

## 📊 Dataset Information

The dataset contains the following columns:

- `data`: Date of the sales
- `venda`: Number of units sold
- `estoque`: Inventory level
- `preco`: Price of the product

---

## 🧠 Methodology

1. **Load and explore** the data
2. **Resample** sales data to monthly level
3. **Visualize** trends over time
4. **Split** the data into train/test sets
5. **Build and train** ARIMA model
6. **Evaluate** predictions using RMSE
7. **Plot** actual vs predicted values

---

## 📂 Files Included

| File Name                  | Description                                |
|---------------------------|--------------------------------------------|
| `sales_forecasting.ipynb` | Jupyter notebook with full code and output |
| `mock_kaggle.csv`         | Raw sales dataset                          |
| `sales_forecast_results.csv` | CSV with actual vs forecasted values     |
| `forecast_plot.png`       | Visualization of forecast results          |

---

## 📉 Model Performance

- **Metric Used**: RMSE (Root Mean Squared Error)
- **Model RMSE**: `2450.38` 
---

## 📌 Visualization

![Sales Forecast](forecast_plot.png)
![Monthly sales](https://github.com/user-attachments/assets/dcbe5cef-66bb-463a-965d-0dd5455e9d23)

---

## 🛠 Libraries Used

- `pandas`
- `matplotlib`
- `statsmodels`
- `numpy`
- `seaborn` *(optional)*

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Geetika08Gorremkala/sales-forecasting-arima.git
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook sales_forecasting.ipynb
   ```
3. Run all cells to reproduce results.

---

## 🙋‍♀️ Author

**Geetika Gorremkala**  
Master's in Business Analytics | B.Com (Computer Applications)  
[LinkedIn Profile](https://www.linkedin.com/) *(www.linkedin.com/in/gorremkala-geetika-bb972b23a)*

---
#visuals 

## ⭐️ Feedback

If you find this project helpful, feel free to ⭐️ the repo and connect!
