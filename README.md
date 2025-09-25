## Research
- Goal: Analyze a 365-day health and fitness tracking dataset for 1000 users.  
- Source: Dataset obtained from **Kaggle**.  
- Research Questions:  
  - What are the patterns of daily activity (steps) and sleep among users?  
  - How does stress level influence physical activity and sleep?  
  - What is the relationship between heart rate, sleep hours, and calories burned?  
  - How is gender distributed, and does it affect health behaviors?  

---

## Exploration
- Dataset Overview: 268,378 rows × 12 columns.  
- Main Features: `date`, `user_id`, `steps`, `sleep_hours`, `calories_burned`, `exercise_minutes`, `heart_rate_avg`, `stress_level`, `gender`.  
- Data Cleaning:  
  - Checked missing values and duplicates.  
  - Converted `date` to datetime.  
  - Extracted `year` and `month`.  
- Feature Engineering:  
  - Created `sleep_pct` (sleep hours as % of 24h).  
  - Added `stress_label` (Low / Medium / High).  

---

## Data Analysis
- Descriptive Statistics: Mean, standard deviation, min, max for steps and sleep hours.  
- Sorting: By steps, calories burned, and date + steps.  
- Aggregations:  
  - Monthly averages (steps, sleep).  
  - Monthly totals (calories burned, exercise minutes).  
- Queries & Filters:  
  - Users with >10,000 steps.  
  - Users with heart rate <60 and sleep >7 hours.  
- Grouped Analysis: Average steps, sleep, and stress level per user.  

---

## Modeling & Visualization
- Distributions:  
  - Histogram of daily steps.  
  - Boxplot of sleep hours.  
  - Boxplot of heart rate by stress label.  
- Relationships:  
  - Bar chart of mean steps by stress level.  
  - Scatter plot of steps vs. calories burned (colored by stress level).  
- Categorical Distributions:  
  - Pie chart of stress levels.  
  - Pie chart of gender.  
