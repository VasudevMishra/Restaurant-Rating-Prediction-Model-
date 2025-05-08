# 🍽️ Zomato Restaurant Data Analysis

This project presents an exploratory data analysis (EDA) of the **Zomato Restaurant Dataset**, with the goal of uncovering insights about restaurants listed on Zomato. The analysis involves cleaning, transforming, and visualizing key attributes of restaurants — helping us understand trends in cuisine, location, pricing, and customer ratings.

## 📂 Dataset

The dataset contains details of restaurants listed on Zomato, including:

- Restaurant name
- Location and city
- Types of cuisines served
- Average cost for two people
- Online ordering availability
- Table booking availability
- User ratings

## 🚀 Objectives

- Clean and preprocess the Zomato dataset
- Analyze restaurant ratings, costs, and cuisines
- Identify patterns and insights such as:
  - Which cuisines and locations are most popular?
  - How does cost relate to ratings?
  - What impact does online ordering and table booking have?

## 🛠️ Tools & Libraries

- **Python** (Pandas, NumPy)
- **Data Visualization:** Matplotlib, Seaborn

## 📊 Key Steps

1. **Data Cleaning**  
   - Dropped unnecessary columns such as URL, address, phone numbers, and menu details
   - Cleaned the `rate` column (removed unnecessary text and converted ratings to numeric)
   - Handled missing values

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of ratings and costs
   - Top cuisines and restaurants
   - Location-wise restaurant analysis
   - Insights on online ordering and table booking features

## 🧐 Insights

- The majority of restaurants have ratings between **3.0 and 4.0**
- **North Indian** and **Chinese** cuisines dominate the listings
- Restaurants offering **online ordering** tend to have slightly higher customer engagement
- Cost for two people is generally clustered around ₹300 to ₹600

## 📈 Visualizations

The project includes several visualizations like:

- Bar charts of top cuisines and locations
- Heatmaps showing correlation between features
- Box plots of cost vs ratings

## 📌 Conclusion

This analysis provides a solid foundation for understanding customer preferences, popular cuisines, and location-specific trends in the restaurant industry through Zomato’s dataset. Such insights can be valuable for restaurant owners, food delivery platforms, and business analysts.
