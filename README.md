# Bellabeat Fitness Tracker Data Analysis

## Overview
This project is the final capstone for the **Google Data Analytics Professional Certificate**. It provides a deep-dive exploratory data analysis (EDA) of Fitbit tracker data to derive business strategies for Bellabeat, a company specializing in health-conscious smart products for women.

## 1. Ask
**Business Task:** Analyze activity, sleep, and intensity data to identify user behavior patterns and provide data-driven recommendations to improve the Bellabeat app’s engagement and user retention.

## 2. Prepare & Process
* **Data Source:** [Fitbit Fitness Tracker Data (Kaggle)](https://www.kaggle.com/datasets/arashnic/fitbeat)
* **Process Steps:**
    1. **Cleaning:** Standardized date formats and column names to ensure consistency.
    2. **Integration:** Merged activity and sleep datasets to enable cross-variable analysis.
    3. **Engineering:** Created time-based features (e.g., `day_of_week`, `hour`) to uncover trends.
    4. **Verification:** Conducted integrity checks to ensure the dataset was free of nulls or duplicates.
    5. **Statistical Analysis:** Performed correlation mapping to identify relationships between intensity, sleep, and health markers.

## 3. Analyze
* **Sedentary Dominance:** On average, users spend 991 minutes (16.5 hours) per day sedentary.
* **Sleep-Activity Correlation:** Users with higher "Very Active" minutes demonstrate a positive relationship with sleep quality metrics.
* **The Afternoon Slump:** Hourly data reveals a consistent decline in physical intensity between 2:00 PM and 4:00 PM.
* **Correlation Matrix:** Analysis shows the strength of relationships between steps, activity minutes, and sleep duration. 




## 4. Share
The analysis highlights that while users are consistent in tracking basic metrics like steps, there is a lack of engagement with high-intensity activity and sleep optimization. The clear correlation between activity levels and sleep quality presents a unique product positioning opportunity for Bellabeat to foster more holistic wellness.

## 5. Act (Business Recommendations)
1. **Intelligent "Power-Up" Nudges:** Integrate the app with a notification system that targets the 2:00 PM – 4:00 PM slump with short, 5-minute activity suggestions.
2. **Sleep-Sync Programs:** Implement a feature that recommends moderate daily activity based on a user's previous night's sleep quality data.
3. **Behavioral Segmentation:** Provide personalized content paths for "Sedentary" vs. "Active" users.

## Technologies Used
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---
*Disclaimer: This project was completed as part of the Google Data Analytics Professional Certificate.*
