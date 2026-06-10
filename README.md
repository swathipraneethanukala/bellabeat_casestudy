# Bellabeat Fitness Tracker Data Analysis

## Overview
This project is the final capstone for the **Google Data Analytics Professional Certificate**. It provides a deep-dive exploratory data analysis (EDA) of Fitbit tracker data to derive business strategies for Bellabeat, a company specializing in health-conscious smart products for women.

## 1. Ask
**Business Task:** Analyze activity, sleep, and intensity data to identify user behavior patterns and provide data-driven recommendations to improve the Bellabeat app’s engagement and user retention.

## 2. Prepare & Process
* **Data Sources:** Multi-dataset analysis including Daily Activity, Sleep logs, and Hourly Intensities.
* **Methodology:** Data was cleaned, transformed, and aggregated using Python (Pandas/NumPy). Features such as `day_of_week` and `hourly_intensity` were engineered to reveal temporal trends. 
* **Data Integrity:** Handled date-time formatting to ensure accurate merging between sleep and activity logs, allowing for cross-variable correlation analysis.

## 3. Analyze
* **Sedentary Dominance:** On average, users spend 991 minutes (16.5 hours) per day sedentary.
* **Sleep-Activity Correlation:** Users with higher "Very Active" minutes demonstrate a more positive relationship with sleep quality metrics.
* **The Afternoon Slump:** Hourly data reveals a consistent decline in physical intensity between 2:00 PM and 4:00 PM, identifying a clear opportunity for intervention.




## 4. Share
The analysis highlights that while users are consistent in tracking basic metrics like steps, there is a lack of engagement with high-intensity activity and sleep optimization. The clear correlation between activity levels and sleep quality presents a unique product positioning opportunity for Bellabeat.

## 5. Act (Business Recommendations)
1. **Intelligent "Power-Up" Nudges:** Integrate the app with a notification system that targets the 2:00 PM – 4:00 PM slump with short, 5-minute activity suggestions to boost user movement.
2. **Sleep-Sync Programs:** Implement a feature that recommends moderate daily activity based on a user's previous night's sleep quality data to promote a balanced, healthy lifestyle.
3. **Behavioral Segmentation:** Provide personalized content paths:
    * *Sedentary Users:* Focus on low-friction, desk-friendly movement habits.
    * *Active Users:* Focus on performance recovery and deeper wellness insights.

## Technologies Used
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---
*Disclaimer: This project was completed as part of the Google Data Analytics Professional Certificate.*
