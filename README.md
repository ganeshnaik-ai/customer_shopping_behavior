
# E-Commerce Sales Analytics Dashboard using Streamlit

## Description:
An interactive data analytics dashboard built using Streamlit to analyze e-commerce sales data. The project includes KPI tracking, customer segmentation, and dynamic visualizations to derive business insights such as revenue trends, top-selling products, customer demographics, and purchase behavior.

 Complete Project Report
## Project Overview

This project focuses on analyzing e-commerce transaction data and transforming it into meaningful business insights using data analytics and visualization techniques. The final output is an interactive dashboard built with Streamlit that allows users to explore key performance indicators (KPIs) dynamically.

## Objectives
Analyze customer purchasing behavior
Identify top-selling products and categories
Understand revenue distribution
Perform customer segmentation
Build an interactive dashboard for decision-making
## 📂 3 Dataset Description

The dataset contains the following features:

Customer Details: customer_id, age, gender, age_group
Purchase Details: item_purchased, category, purchase_amount
Product Attributes: size, color, season
Customer Behavior: previous_purchases, frequency_of_purchases
Transaction Details: payment_method, shipping_type, discount_applied
Location Data: location
Feedback: review_rating

## Technologies Used
- Python
- Pandas (Data Processing)
- Matplotlib (Visualization)
- Streamlit (Dashboard UI)
  
## Data Processing Steps
- Data loading using Pandas
- Handling missing values
-Feature exploration and validation
- Creating derived features (e.g., spending levels)
  
## Business KPIs
- Total Revenue
- Total Orders
- Average Customer Rating
- Top Selling Item

## Customer Insights
- Gender-based purchases
- Age group distribution
- Customer segmentation (Low / Medium / High spending)

## Sales Insights
- Top products sold
- Category-wise revenue
- Location-wise sales
- 
## Behavioral Insights
Purchase frequency
Payment method usage
Discount impact on revenue

## Visualizations

The dashboard includes:

- Bar charts for categorical insights
- Revenue comparisons
- Customer distribution charts
- Purchase behavior analysis

All visualizations are interactive and update based on selected filters.

## Dashboard Features
- Interactive filters (Gender, Category, Location)
- Real-time KPI updates
- Dynamic charts
- Customer segmentation
- Raw data view
- 
## Customer Segmentation

Customers are segmented into:
- Low Spenders
- Medium Spenders
- High Spenders

### This helps businesses:

- Target premium users
- Improve marketing strategies
- Increase retention
## Key Insights (Example)
- Certain categories generate the highest revenue
- Discounts significantly influence purchasing behavior
- Specific locations contribute more to sales
- High-frequency customers drive consistent revenue
## How to Run the Project
- Step 1: Install dependencies
pip install streamlit pandas matplotlib
- Step 2: Run the application
streamlit run app.py
- Step 3: Open in browser
http://localhost:8501
```
📁 Project Structure
project/
│── app.py
│── dataset.csv
│── analysis.ipynb
│── README.md
```
## Future Improvements
- Add Machine Learning models (sales prediction)
- Integrate recommendation system
- Use advanced visualizations (Plotly)
- Deploy dashboard online
- Add chatbot for querying data
## Conclusion
This project demonstrates the complete pipeline from data analysis to dashboard development.
It highlights the ability to extract business insights and present them effectively 
using interactive tools.
