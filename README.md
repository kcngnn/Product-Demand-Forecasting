# Product-Demand-Forecasting
The objective is to forecast demands for thousands of products at four central warehouses of a manufacturing company.

**Data Source:** [Kaggle](https://www.kaggle.com/felixzhao/productdemandforecasting)

**Data Description from Kaggle:** *The dataset contains historical product demand for a manufacturing company with footprints globally. The company provides thousands of products within dozens of product categories. There are four central warehouses to ship products within the region it is responsible for. Since the products are manufactured in different locations all over the world, it normally takes more than one month to ship products via ocean to different central warehouses. If forecasts for each product in different central with reasonable accuracy for the monthly demand for month after next can be achieved, it would be beneficial to the company in multiple ways.*

**Objective:** To produce forecasts from the month after next onwards. The latest data month is Jan 2017, thus forecast is for Mar 2017 onwards.

**Data overview**:
|Product_Code|Warehouse|Product_Category|Date|Order_Demand|
|-----------|---------|---------|---------|---------|
|Product_0993|Whse_J|Category_028|7/27/2012|100|
|Product_0979|Whse_J|Category_028|1/19/2012|500|
|Product_0979|Whse_J|Category_028|2/3/2012|500|
|Product_0979|Whse_J|Category_028|2/9/2012|500|
|Product_0979|Whse_J|Category_028|3/2/2012|500|

### Tool(s): 
Python

### Technique(s): 
ARIMA model, Simple/Double/Triple Exponential Smoothing models

### File(s) included: 
- Analysis and Model: This notebook provides analysis of the dataset, data preprocessing and model development.
- Code to run forecast automatically: This notebook gives code to run the forecast automatically based on analysis from the first file. The forecast user just needs to load data and choose the number of forecast periods to generate forecast and get lists of products that cannot be forecasts (stopped products and new products).

*Dataset can be accessed from the provided Kaggle link.*
