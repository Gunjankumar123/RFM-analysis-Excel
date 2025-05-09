# NeighborMart Customer Segmentation Project

## Overview
This project uses RFM (Recency, Frequency, Monetary) analysis to segment and profile customers for NeighborMart, a retail business, in order to implement more targeted and effective marketing campaigns. The analysis was carried out using Microsoft Excel for data cleaning, processing, visualization, and customer segmentation.

## Business Problem
NeighborMart needed to identify and categorize customers into segments based on their buying behavior to improve marketing strategies and customer engagement. The key challenge was distinguishing high-value, loyal customers from low-engagement ones to better allocate resources and tailor marketing efforts.

## Methodology
The project follows these key steps:

### 1. Data Cleaning
Cleaned the dataset by filling in missing values, correcting typos, and removing duplicates.

### 2. Data Aggregation
Created new columns for customer attributes such as age, total monetary value spent, and purchase frequency.

### 3. Feature Selection
Identified key features relevant for customer segmentation.

### 4. Percentrank Calculation
Used Excel's Percentrank function to normalize the values of Recency, Frequency, and Monetary metrics.

### 5. RFM Score Creation
Calculated RFM scores based on Percentrank values and created a new column, "RFM Score," for customer segmentation.

### 6. Customer Segmentation
Segmented customers into distinct groups based on their RFM scores using VLOOKUP.

### 7. Visualization
Created pivot charts to display the count of customers in each segment.

Visualized KPIs and provided insights into top customers and "Immediate Attention" segments.

## Dataset
The project uses a Kaggle dataset containing customer information from NeighborMart, including 2,240 customers with 27 columns that cover various customer attributes such as customer ID, purchase behavior, and demographic data.

Dataset Link: Kaggle Dataset

## Key Recommendations
Based on the RFM analysis, the following marketing strategies were proposed:

### For Top Customers:
Exclusive Offers: Special discounts and offers.
Personalized Recommendations: Tailored product suggestions.
Priority Support: Enhanced customer service.
Loyalty Program: Reward programs for consistent purchases.

### For At-Risk or Immediate Attention Customers:
Re-Engagement Campaigns: Special offers and discounts to bring them back.
Feedback Request: Engage customers by asking for feedback.
Proactive Customer Support: Address past issues to regain trust.
Win-Back Offers: Attractive offers for customers who have not made a recent purchase.

## Tools Used
Microsoft Excel: Data cleaning, analysis, aggregation, and visualization.

Kaggle: Dataset for customer information.

Excel Functions: VLOOKUP, Percentrank, Pivot Tables, and Pivot Charts.

## Getting Started
Download the Dataset: Access the dataset from Kaggle or use your own customer data.

Load and Clean Data: Open the dataset in Excel and perform cleaning, such as handling missing values and correcting errors.

Perform RFM Analysis: Calculate RFM scores for each customer and categorize them into segments.

Create Visualizations: Use Excel pivot charts to visualize the customer segments and performance.

## Example Code (Excel Formulas)
Here are some key Excel formulas used in the analysis:
Percentrank:
=PERCENTRANK(data_range, value)
VLOOKUP for Segment Assignment:
=VLOOKUP(RFM_Score, Segment_Range, 2, FALSE)

## Conclusion
This project successfully segments customers into actionable categories, providing NeighborMart with clear insights to improve marketing strategies, customer engagement, and business growth.


![RFM Analysis Dashboard ](https://github.com/user-attachments/assets/f87daf17-9a6a-4d29-99b2-b9ed92caaa58)
