# VAR Silver-Gold Commodity Pricing Prediction - Time Series

This repository contains the Colab notebook and datasets used to predict commodity prices (Gold, Silver) and analyze time series trends with the help of VAR (Vector Autoregression) and Prophet models. Follow the instructions below to clone the repository, upload the notebook to Google Colab, and run the analysis.

---

## **Table of Contents**
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [How to Run the Notebook](#how-to-run-the-notebook)
- [Dependencies](#dependencies)
- [Results and Insights](#results-and-insights)
- [License](#license)

---

## **Introduction**
This project aims to analyze the relationship between various commodity prices (Gold, Silver) and economic indicators using time series forecasting. We leverage VAR and Prophet models to gain insights into how these variables influence each other over time.

The notebook demonstrates how to preprocess the data, visualize trends, train forecasting models, and interpret the results.

---

## **Project Overview**
The goal of this Colab notebook is to:
- Explore relationships between economic indicators such as **Gold price, Silver price, and S&P Index values**.
- Train **VAR models** for time series forecasting.
- Attempt to use **Prophet** for univariate forecasting (Gold prices).
- Provide insights into the trends, relationships, and predictions for future values.

Key steps:
1. Data preprocessing and handling missing values.
2. Visualizing trends for various commodities and indexes.
3. Training **time series models** (VAR, Prophet).
4. Evaluating the forecasts and visualizing the predictions.

---

## **Datasets**
Below are the datasets used in this project:

1. **`lbma_gold_am_usd_1967-12-31_2022-03-31.csv`**  
   - Contains daily gold prices in USD from 1967 to 2022.

2. **`lbma_silver_am_usd_1967-12-31_2022-03-31.csv`**  
   - Contains daily silver prices in USD from 1967 to 2022.

3. **`DCOILWTICO_2022-03-31.csv`**  
   - Crude oil prices (WTI) up to March 2022.

4. **`FEDFUNDS_2022-03-31.csv`**  
   - Historical Federal funds rates up to March 2022.

5. **`DGS10.csv`**  
   - 10-year treasury constant maturity rates.

6. **`SPIndex_2022-03-31.csv`**  
   - S&P 500 index closing values.

---

## **How to Run the Notebook**

Follow these steps to run the notebook in Google Colab:

1. **Clone the repository**  
   Open your terminal and run:

   ```bash
   git clone https://github.com/Praful-John2409/VAR-Silver-Gold-Commodity-Pricing-Predict-Time-Series.git
   cd VAR-Silver-Gold-Commodity-Pricing-Predict-Time-Series
   ```

2. **Open Google Colab**  
   Upload the `CMPE256_VARSilverGoldCommodityPricingPredictByPraful.ipynb` notebook to Colab.

3. **Run the notebook step-by-step**  
   Start running each cell one by one.

4. **Upload datasets**  
   When prompted (in the **upload cell**), upload the datasets listed above to Colab.

5. **Run the remaining cells**  
   After uploading the datasets, continue running the rest of the notebook to see the results, analysis, and model predictions.

---

## **Dependencies**
Make sure you have the following Python packages installed:

```bash
pip install pandas numpy matplotlib prophet
```

Alternatively, these packages will be installed automatically in Google Colab if they are not already available.

---

## **Results and Insights**
This project helps us understand the dynamics between different commodities and economic indicators over time. Below are some key takeaways:

1. **Relationship Analysis:**  
   Using **VAR models**, we can see how gold and silver prices influence each other and how they react to changes in the S&P 500 index.

2. **Forecasting:**  
   - The **Prophet model** is used to predict future Gold prices.
   - VAR models analyze multiple time series variables and forecast their interactions.

3. **Visualizations:**  
   Graphs in the notebook reveal the trends in **Gold, Silver, Oil, and Stock prices** over time.

4. **Use Case:**  
   - This analysis is useful for investors, economists, and financial analysts to forecast commodity trends.
   - It also demonstrates the predictive capabilities of time series models in real-world datasets.

---
