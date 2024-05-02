# Food Consumption and Online Shopping Analysis

## Project Overview
This project focuses on analyzing food consumption patterns across different regions, along with exploring online shopping data to provide recommendations using collaborative filtering. It involves data generation, exploratory data analysis, recommendation system development, sales forecasting, clustering analysis, market basket analysis, and a content-based recommendation system. Various algorithms such as Random Forest Regression, K-Means Clustering, Apriori Algorithm, and Collaborative Filtering using Singular Value Decomposition (SVD) are implemented.

## Project Scope
1. **Data Generation:**
   - Random data is generated for food consumption and online shopping.
   - Food consumption data includes regions, product categories, population density, income levels, climate types, seasons, and sales figures.
   - Online shopping data includes portals, product categories, brands, locations, ratings, discount levels, prices, and order numbers.

2. **Exploratory Data Analysis (EDA):**
   - Statistical analysis and visualization of sales data by region, product category, income level, etc.

3. **Recommendation System using Collaborative Filtering:**
   - Collaborative Filtering algorithm (SVD) is used to generate recommendations for each region based on historical sales data.
   - Singular Value Decomposition is applied to the data using the Surprise library for recommendation generation.

4. **Sales Forecasting using Random Forest Regression:**
   - Random Forest Regression is implemented to forecast sales based on various features such as region, product category, population density, income level, climate, and season.
   - The model is trained on historical sales data and evaluated using R-squared score.

5. **K-Means Clustering for Consumer Segmentation:**
   - K-Means Clustering algorithm is used to segment consumers based on population density and income level.
   - Clustering helps in understanding consumer behavior and targeting specific groups for marketing strategies.

6. **Market Basket Analysis:**
   - Apriori Algorithm is applied to perform market basket analysis on food consumption data.
   - Association rules are generated to identify frequent itemsets and potential relationships between products.

7. **Content-Based Recommendation System:**
   - A content-based recommendation system is developed using TF-IDF and cosine similarity.
   - User input (shopkeeper's region, targeted region, targeted brand, and product category) is used to recommend similar products from the online shopping data.

## Implementation
1. Clone the repository or download the project files.
2. Ensure Python and required libraries are installed (Pandas, NumPy, Matplotlib, Surprise, Scikit-Learn, MLxtend).
3. Run each Python script (`data_generation.py`, `eda_visualization.py`, `collaborative_filtering.py`, `sales_forecasting.py`, `clustering_analysis.py`, `market_basket_analysis.py`, `content_based_recommendation.py`) in the specified order to execute the respective analyses and algorithms.
4. Follow the comments and output to understand each step and result.
5. Modify parameters or algorithms as needed for specific use cases or datasets.

## Dataset
The generated datasets (`food_consumption.csv` and `online_shopping_data.csv`) are included for analysis and demonstration purposes. These datasets contain synthetic/random data and are used for illustration only. For real-world applications, replace these datasets with actual data.

## Performance Metrics
The performance metrics for the implemented algorithms are as follows:

### Performance Metrics

#### Collaborative Filtering (SVD) Metrics
- RMSE: 5252.0044
- RMSE for SVD: 5252.00
- MAE: 4545.0072
- MAE for SVD: 4545.01
- FCP: 0.0000
- FCP for SVD: 0.00
- MSE for SVD: 27583550.06
- MAE for SVD (scikit-learn): 4545.01

#### Random Forest Regression Metrics
- RMSE: 2849.0304
- RMSE: 2849.03
- MAE: 2479.4972
- MAE: 2479.50
- FCP: 0.0000
- FCP: 0.00

#### Collaborative Filtering (SVD) Metrics on Online Shopping Data
- RMSE: 2868.9605
- RMSE for SVD on online shopping data: 2868.96
- MAE: 2495.3701
- MAE for SVD on online shopping data: 2495.37
- FCP: 0.0000
- FCP for SVD on online shopping data: 0.00
- MSE for SVD on online shopping data: 8230934.51
- MAE for SVD on online shopping data (scikit-learn): 2495.37

