# 📊 Zomato Data Analysis

A **Zomato Data Analysis** project that explores customer preferences, restaurant types, and online ordering trends. This project utilizes **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** to perform data cleaning, transformation, and visualization.

---

## 📈 Project Overview

This project analyzes a dataset from **Zomato**, focusing on:
- **Restaurant Types** and their popularity
- **Online Order** trends
- **Rating Distribution**
- **Votes Analysis** for different categories
- **Heatmap Visualization** of online orders by restaurant type

---

## 🗂️ Dataset Information

The dataset includes the following key columns:
- **Name**: Restaurant name
- **Rate**: Customer rating (e.g., 4.2/5)
- **Votes**: Number of votes received
- **Online Order**: Whether online orders are available (`Yes`/`No`)
- **Listed_in(type)**: Type of restaurant (e.g., Casual Dining, Café)
- **Approx Cost (for two people)**: Estimated price for two customers

---

## 🛠️ Project Workflow

1. **Data Cleaning**: 
   - Extracting and converting rating values.
2. **Data Visualization**:
   - Count plots for restaurant type and online orders.
   - Line plot showing total votes by restaurant type.
   - Boxplot analyzing online orders vs. rating.
   - Heatmap to visualize online orders across different restaurant categories.
3. **Insights Extraction**:
   - Identify the restaurant with the highest votes.
   - Understand customer preferences and rating distribution.

---

## 📊 Visualizations

### 1. Restaurant Type Distribution
Displays the frequency of different restaurant categories.

### 2. Votes by Restaurant Type
Line plot showing the total votes for each restaurant type.

### 3. Rating Distribution
Histogram visualizing the distribution of customer ratings.

### 4. Online Orders vs. Rating
Boxplot comparing online order availability and average ratings.

### 5. Online Orders Heatmap
Heatmap showing the relationship between restaurant types and online ordering.

---

## 🧰 Requirements

Ensure the following libraries are installed:

bash
pip install pandas numpy matplotlib seaborn


## ▶️ Usage
- git clone https://github.com/ShivamAralikatti/zomato-analysis.git
- cd zomato-analysis
- python zomato_analysis.py

## 📌 Key Findings
- The restaurant with the most votes is displayed in the output.
- Online orders are more common in specific restaurant categories.
- Ratings are distributed across different ranges with notable peaks.

## Acknowledgments
This project uses the dataset available on Kaggle. 

Thank You
