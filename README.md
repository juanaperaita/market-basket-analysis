# Market Basket Analysis for The Bread Basket

## Overview

This repository contains a Jupyter Notebook implementation of a Market Basket Analysis conducted on real transactional data from The Bread Basket, a bakery-café located in the historic center of Edinburgh. The purpose of this analysis is to derive actionable insights that align with the following business objectives:

1. **Understand the Best-Performing Products:** Identify which products are the most popular among customers.
2. **Develop Product Recommendations:** Generate suggestions for product pairings that could increase sales and provide a more personalized experience, even in the absence of a customer loyalty card.

## Project Description

The dataset includes 5 months of transaction data, capturing every purchase made at The Bread Basket. Using this data, we applied the Market Basket Analysis technique to discover associations between different products. These associations are used to recommend products that are frequently bought together, aiming to boost overall sales and enhance the customer experience.

### Key Objectives:

- **Product Performance:** Analyze the transaction data to determine which products are the most frequently purchased and contribute the most to revenue.
- **Recommendation Engine:** Use association rules generated from the transaction data to suggest additional items that customers are likely to purchase together, helping to optimize sales strategies.

## Files in the Repository

- `market_basket_analysis.ipynb`: The main Jupyter Notebook that performs the Market Basket Analysis. This notebook includes:
  - **Data Preprocessing:** Cleaning and organizing the transaction data to prepare it for analysis.
  - **Association Rule Mining:** Implementing the Apriori algorithm to extract meaningful association rules from the transaction data.
  - **Recommendations:** Generating and displaying product recommendations based on the association rules.
  
- `R3_BreadBasket-1.csv`: The CSV file containing the transactional data.
  
- `requirements.txt`: The list of required Python libraries for the project.

## How to Use

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/bread-basket-analysis.git
   cd bread-basket-analysis
   ```
2. **Install required libraries:**
```bash
pip install -r requirements.txt
```
3. **Run the Notebook:**: Open and run the market_basket_analysis.ipynb notebook using Jupyter. 
