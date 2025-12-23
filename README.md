# Bellabeat Capstone – Google Data Analytics Certificate  
**Case Study: Bellabeat Fitness Data Analysis**

This case study analyzes Fitbit smart device usage data to identify trends in physical activity, calorie expenditure, and sleep behavior. The objective is to understand how users interact with their devices throughout the day and translate these insights into actionable marketing recommendations for Bellabeat.

---

## ASK — Business Task

**Business Task:**  
Analyze Fitbit smart device usage data to identify trends related to physical activity, sleep, and daily behavior that can inform Bellabeat’s marketing strategy and product positioning.

**Key Stakeholders:**  
- Urška Sršen — Co-founder & Chief Creative Officer  
- Sando Mur — Co-founder & Executive Team Member  
- Bellabeat Marketing Team  
- Bellabeat Data Analytics Team  

**Guiding Questions:**  
1. What daily activity patterns do users exhibit?  
2. How do sleep habits relate to physical activity and calorie burn?  
3. When during the day are users most and least active?

---

## PREPARE — Data Collection & Integrity Review

**Data Source:**  
Fitabase 2016 Fitness Tracker Data (Kaggle), collected from 30 Fitbit users between March and May 2016.

**Datasets Used:**  
- Daily activity, steps, calories, and intensity  
- Hourly activity datasets  
- Minute-level sleep data  

Not all users appear in every dataset due to optional device features and manual logging.

**Data Limitations:**  
- Small sample size (30 users)  
- Incomplete participation across datasets  
- Limited sleep and weight data  
- No demographic information  
- Data collected in 2016  

**Tool Selection:**  
RStudio Cloud was used for data cleaning and analysis due to its ability to handle large datasets and ensure reproducibility.

---

## PROCESS — Data Cleaning & Preparation

Data was cleaned and validated using R and tidyverse packages.

**Key Actions:**  
- Verified data structure and consistency  
- Checked and removed duplicate records where applicable  
- Converted date and datetime fields to proper formats  
- Confirmed datasets were suitable for daily and hourly analysis  

All datasets used in analysis were confirmed clean and properly formatted.

---

## ANALYZE — Data Analysis

Analysis was conducted at two levels:

### Daily-Level Analysis
- Average daily step count is approximately **6,500 steps**  
- Users spend a large portion of the day sedentary  
- A positive relationship exists between steps and calories burned  
- Higher activity levels correspond to lower sedentary time  

### Hourly-Level Analysis
- Activity is lowest during late night and early morning  
- Activity increases from early morning, peaking midday and early evening  
- Patterns indicate consistent daily routines across users  

**Key Insight:**  
User activity follows predictable daily rhythms, creating opportunities for time-based engagement strategies.

---

## SHARE — Data Visualization & Key Insights

### Insight 1: Average Steps by Hour of Day
User activity is lowest between 12 AM and 5 AM, increases from 6 AM onward, and peaks around midday and early evening.

**Business implication:**  
Bellabeat can schedule reminders during low-activity hours and reinforce engagement during peak activity periods.

🔗 **Visualization:**  
[Average Steps by Hour of Day – Tableau Public](https://public.tableau.com/views/BellabeatCaseStudyAverageStepsbyHourofDay/Hoja1)

---

### Insight 2: Relationship Between Steps and Calories Burned
There is a clear positive relationship between daily steps and calories burned.

**Business implication:**  
Step-based goals can be promoted as a simple and effective driver of calorie expenditure.

🔗 **Visualization:**  
[Average Daily Steps vs Calories Burned – Tableau Public](https://public.tableau.com/views/BellabeatCaseStudyStepsvsCaloriesRelationship/Hoja1)

---

### Insight 3: Average Daily Sleep Duration
Most users sleep between 5 and 7 hours per night, below the recommended range.

**Business implication:**  
Bellabeat can introduce sleep education, bedtime reminders, and recovery-focused features.

🔗 **Visualization:**  
[Average Daily Sleep Duration – Tableau Public](https://public.tableau.com/views/BellabeatCaseStudyUserActivitySleepInsights/Hoja2)

---

## ACT — Final Recommendations & Next Steps

### Final Conclusion
Users display consistent daily routines. Activity peaks during daytime and early evening, step count strongly correlates with calorie burn, and many users sleep less than recommended. These patterns present clear opportunities for targeted engagement.

### How Bellabeat Can Apply These Insights
- Launch challenges during peak activity hours  
- Send nudges during low-activity periods  
- Emphasize step-based goals  
- Promote sleep education and bedtime routines  

### Recommended Next Steps
- Segment users by activity and sleep behavior  
- Personalize notification timing  
- Develop sleep-focused features  
- Test behavior-based nudges  

### Additional Data to Strengthen the Analysis
- Sleep quality metrics  
- User demographics  
- Longer time-series data  
- Relationship between sleep and next-day activity  
