# Analyzing Customer Satisfaction and Engagement Based on Women’s Clothing E-Commerce Sales

## Overview
This project analyzes customer reviews of women’s clothing from an e-commerce platform to identify key factors influencing customer satisfaction, engagement patterns, and seasonal trends. The goal is to provide actionable insights that improve product offerings, optimize customer experiences, and guide marketing strategies effectively.

## Objectives
- Identify key factors that impact customer satisfaction, focusing on ratings and recommendations.
- Analyze monthly trends in customer feedback to uncover seasonal variations.
- Explore patterns in positive feedback counts to better understand customer engagement.
- Provide insights to inform product strategy, enhance customer experience, and optimize marketing initiatives.

## Dataset
The dataset includes customer reviews of women’s clothing products with attributes such as:
- **Demographics:** Customer age and recommendation status.
- **Review Details:** Star ratings, textual feedback, and positive feedback counts.
- **Product Information:** Product division, department, and class for categorization.
- **Temporal Data:** Review dates for trend and seasonal pattern analysis.

## Methodology
### Data Preparation
- **Data Loading:** Imported dataset into a Python environment using the Pandas library.
- **Data Cleaning:** 
  - Handled missing values, outliers, and inconsistent data types.
  - Ensured data integrity for analysis.
- **Tools:** Python (Pandas, NumPy).

### Data Analysis
1. **Descriptive Statistics:**
   - Analyzed ratings distribution, recommendation rates, and feedback counts.
   - Explored engagement by demographic groups and product categories.
2. **Time Series Analysis:**
   - Identified seasonal trends in ratings and engagement metrics.
   - Analyzed monthly peaks during holidays and promotional periods.
3. **Data Aggregation:**
   - Grouped data by demographics, product divisions, and categories for comparative analysis.

### Data Visualization
- Used Matplotlib and Seaborn to create the following visualizations:
  - **Ratings Distribution:** Histograms showing customer satisfaction trends.
  - **Product Category Performance:** Bar plots of average ratings and feedback counts.
  - **Temporal Trends:** Time series graphs of monthly engagement metrics.

## Key Insights
1. **Ratings and Satisfaction:**
   - Customers aged 30–50 dominate reviews, providing consistently high ratings.
   - "Intimates" and "General" divisions perform well, while "General Petite" shows variability.
2. **Recommendations:**
   - High recommendation rates align with higher ratings in top-performing divisions.
3. **Temporal Trends:**
   - Engagement peaks during June and November–December due to seasonal promotions.

## Actionable Insights
- **Seasonal Engagement:** Focus marketing efforts during high-engagement periods.
- **Underperforming Divisions:** Investigate "General Petite" for improvement opportunities.
- **Younger Demographics:** Target personalized offers and loyalty programs to retain this active segment.
- **Older Demographics:** Develop tailored products or services to engage neutral feedback groups.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook

