# **Sales Forecasting Project**

## **Project Objective**

**Goal:**  
The goal of this project was to apply various quantitative methods (i.e., Time Series Models and Causal Models) to forecast the sales of the products available in the dataset.

### **Objectives:**
- Perform time series analysis to understand the data and trends  
- Use multiple forecasting models on the training dataset  
- Select the best model to run predictions on the test dataset  

---

## **Models Covered**

The notebook includes the following forecasting models:

1. **Seasonal Naive Model**  
2. **ARIMA Model**  
3. **Seasonal ARIMA (SARIMA) Model**  
4. **Linear Regression Model**

---

## **Conclusion**

We considered different time-series models as well as a regression model for time series forecasting. From our results, we saw that the **Linear Regression Model outperformed all the other time-series models**.

This indicates that for this dataset, a **regression approach** is more suitable than traditional time-series models. One of the main assumptions of regression models is that historical patterns will repeat in the future. Since our dataset showed **strong seasonality and a clear linear trend**, the linear regression model performed best.

---
