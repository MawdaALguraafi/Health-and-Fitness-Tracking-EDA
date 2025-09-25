# Health-and-Fitness-Tracking-EDA

## Exploration
- Dataset shape: (365000, 12).  
- Key columns: date, user_id, steps, sleep_hours, calories_burned, exercise_minutes, heart_rate_avg, stress_level, gender.  
- New features: sleep_pct (of 24h), stress_label (Low/Medium/High).  

---

## Data Analysis
- Descriptive stats: mean, std, min, max for steps & sleep.  
- Sorting by steps & calories.  
- Monthly agg: avg steps & sleep, total calories & exercise.  
- Filters: high steps (>10k), low HR + good sleep.  
- Grouped by Month → avg steps, sleep, stress.  

---

## Modeling & Visualization
- Distributions: steps histogram, sleep boxplot, heart rate vs stress.  
- Relationships: bar (steps vs stress), scatter (steps vs calories).  
- Categories: pie (stress levels, gender). 

