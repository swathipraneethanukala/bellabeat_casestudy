# Bellabeat Fitness Tracker Data Analysis

## Overview
This project is the capstone requirement for the **Google Data Analytics Professional Certificate**. It involves an exploratory data analysis (EDA) of a public Fitbit dataset to understand user activity patterns and derive business recommendations for **Bellabeat**, a high-tech manufacturer of health-focused smart products for women.

## 1. Ask
**Business Task:** Analyze smart device usage data to identify how consumers use their devices and provide actionable insights to inform Bellabeat’s marketing strategy and app development.

**Key Stakeholders:**
* Urška Sršen (Co-founder & Chief Creative Officer)
* Sando Mur (Co-founder & Mathematician)

## 2. Prepare
* **Data Source:** [Fitbit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbeat) (Kaggle).
* **Limitations:** The dataset is from 2016, contains a relatively small sample size (33 users), and lacks demographic information (age, gender, location). These factors were considered when interpreting the results.

## 3. Process
* **Tools Used:** Python (Jupyter Notebook).
* **Cleaning & Manipulation:**
    * Standardized column names to `snake_case` for consistency.
    * Converted date strings into `datetime` format.
    * Validated data integrity by checking for null values and duplicates.
    * Engineered new features, such as `day_of_week` and `total_minutes`, to facilitate time-series analysis.

## 4. Analyze
Key insights uncovered during the exploration:
* **The Sedentary Trap:** Users spend an average of 991 minutes (16.5 hours) per day in sedentary activities.
* **Activity vs. Calorie Burn:** A strong positive correlation exists between daily steps and total caloric expenditure.
* **Consistency:** User activity is highest during the middle of the week (Tuesday–Thursday).
* **Intensity Gap:** Only a small percentage of daily time is spent in "very active" states, representing a significant area for potential growth and habit formation.

## 5. Share
The analysis confirmed that while users are diligent about tracking step counts, they struggle with prolonged sedentary behavior. The data highlights a clear opportunity to shift user behavior from passive tracking to active wellness management through the Bellabeat app.

## 6. Act (Recommendations)
1. **Smart Nudges:** Implement proactive, context-aware push notifications to encourage movement after long periods of sedentary behavior.
2. **Gamification:** Launch "Midweek Challenges" to capitalize on identified activity peaks and drive consistent app engagement.
3. **Personalization:** Use the app to deliver tiered content. "Sedentary" users should receive gentle, low-intensity transition content, while "Very Active" users should receive recovery-focused wellness tips.

## Technologies Used
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---
*Disclaimer: This project was completed as part of the Google Data Analytics Professional Certificate.*
