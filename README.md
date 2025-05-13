# 🧠 NYC Public Schools SAT Performance Analysis

This project is part of a **DataCamp** Python course and involves analyzing SAT performance data of New York City (NYC) public high schools. The SAT is a standardized test with three sections: **Reading**, **Math**, and **Writing**, each scored out of **800 points**. These scores are critical for college admissions and are closely monitored by educators, policymakers, and parents.

## 📊 Project Objectives

The project answers three key analytical questions:

### 1. Which NYC schools have the best math results?

- Criteria: Schools with an average math score of **at least 80% of 800 (≥ 640)**.
- Output: A DataFrame named `best_math_schools` with:
  - `school_name`
  - `average_math`
- Sorted by `average_math` in descending order.
- Visualized using a horizontal bar chart.

### 2. What are the top 10 performing schools based on combined SAT scores?

- A new column `total_SAT` is created by summing scores from the three sections.
- Output: A DataFrame named `top_10_schools` with:
  - `school_name`
  - `total_SAT`
- Sorted by `total_SAT` in descending order.
- Visualized with a horizontal bar chart.

### 3. Which borough has the largest standard deviation in combined SAT scores?

- Grouped schools by `borough` and computed:
  - `num_schools`: Number of schools in each borough
  - `average_SAT`: Mean total SAT score
  - `std_SAT`: Standard deviation of total SAT scores
- Output: A one-row DataFrame named `largest_std_dev` showing the borough with the highest standard deviation.
- All numeric values are rounded to **two decimal places**.

## 🧰 Technologies Used

- **Python**: Pandas, Matplotlib
- **Jupyter Notebook**
- **Data source**: `schools.csv` (provided by DataCamp)

## ✅ Conclusion

This analysis provided practical insights into:

- Filtering and transforming data with pandas
- Performing group-based statistical analysis
- Visualizing SAT performance patterns across NYC

It also emphasizes the value of data in guiding educational decisions and policy.

## 🚀 Possible Extensions

- Merge with demographic/socioeconomic datasets
- Analyze SAT trends over multiple years
- Use machine learning to forecast school performance


