# Retail Price Optimization Dashboard
![Dashboard Screenshot](https://github.com/wahidur0547/Retail-Price-Optimization-Dashboard/assets/141988307/b12241ed-2b49-4664-a60b-3b889cce0b40)
## Overview

This project aims to optimize retail prices by analyzing various factors that influence pricing decisions. Using exploratory data analysis (EDA) and machine learning techniques, we build a comprehensive dashboard to visualize key insights. The dashboard helps in understanding customer behavior, market trends, and pricing strategies to maximize profits.

## Objectives

The main objectives of this project are:
1. **Analyze Retail Data**: Perform exploratory data analysis to understand the distribution of prices, quantities, and other relevant features.
2. **Time Series Analysis**: Analyze trends in total price and quantity sold over time.
3. **Customer Segmentation**: Segment customers based on their purchasing behavior.
4. **Competitor Analysis**: Compare our prices with competitors to identify pricing strategies.
5. **Predict Optimal Prices**: Use regression models to predict optimal prices based on various features.
6. **Build an Interactive Dashboard**: Develop an interactive dashboard to visualize the results of our analysis.

## Methodology

### Data Loading and Preparation

We start by loading the retail data into a pandas DataFrame and preparing it for analysis. This includes converting date columns to the appropriate format and handling missing values.

### Exploratory Data Analysis (EDA)

1. **Distribution Analysis**: We analyze the distribution of total prices and unit prices.
2. **Scatter Plot Analysis**: We examine the relationship between quantity and total price.
3. **Box Plots by Category**: We visualize total price and unit price distributions across different product categories.

### Time Series Analysis

We perform a time series analysis to identify trends in total price and quantity sold over time. This helps in understanding how sales and pricing have evolved.

### Customer Segmentation

Using KMeans clustering, we segment customers based on their purchasing behavior. This helps in identifying distinct customer groups and tailoring pricing strategies accordingly.

### Competitor Analysis

We compare our unit prices with those of competitors to understand our position in the market and identify opportunities for price adjustments.

### Predicting Optimal Prices

We train a regression model using relevant features from the dataset to predict optimal prices. This includes factors like quantity sold, competitor prices, and more.

### Building the Dashboard

We use Dash and Plotly to create an interactive dashboard that displays the results of our analyses. The dashboard includes various sections for time series analysis, distributions, scatter plots, box plots by category, customer segmentation, competitor analysis, and predicted prices.

## Analysis

### Time Series Analysis

1. **Total Price Over Time**: Shows the total price of products over different months.
2. **Quantity Sold Over Time**: Displays the quantity of products sold over different months.

### Distributions

1. **Distribution of Total Price**: A histogram showing the distribution of total prices.
2. **Distribution of Unit Price**: A histogram showing the distribution of unit prices.

### Scatter Plot Analysis

- **Quantity vs. Total Price**: A scatter plot showing the relationship between quantity sold and total price.

### Box Plots by Category

1. **Total Price by Category**: Box plots showing the distribution of total prices across different product categories.
2. **Unit Price by Category**: Box plots showing the distribution of unit prices across different product categories.

### Customer Segmentation

A scatter plot showing customer segments based on total price and quantity.

### Competitor Analysis

Box plots comparing our unit prices with those of competitors.

### Predicted Prices

Scatter plots showing predicted unit prices based on quantity sold and competitor prices.

## Results

The dashboard provides valuable insights into retail pricing strategies. Key findings include:

1. **Trends in Sales**: Identification of seasonal trends and patterns in sales.
2. **Customer Segments**: Identification of distinct customer groups based on purchasing behavior.
3. **Competitive Positioning**: Understanding of how our prices compare with competitors.
4. **Optimal Prices**: Predicted prices based on regression models to help in making data-driven pricing decisions.

## Conclusion

This project successfully builds a comprehensive dashboard for retail price optimization. The insights gained from the analysis can help retailers make data-driven pricing decisions, improve competitiveness, and maximize profits. The interactive dashboard serves as a valuable tool for business analysts and decision-makers.

## How to Run the Dashboard

1. Install the required libraries:

    ```bash
    pip install dash
    pip install plotly
    pip install pandas
    pip install scikit-learn
    ```

2. Save the `app.py` file in your project directory.

3. Run the dashboard:

    ```bash
    python app.py
    ```

4. Open a web browser and go to `http://127.0.0.1:8050/`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
