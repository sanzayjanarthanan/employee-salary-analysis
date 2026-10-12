# Employee Salary Analysis

Python and Pandas project to analyze employee salary data. Built as Task 3 of the AI & ML Internship at Veda Technology.

## Problem
Analyze employee salaries and calculate the total, average, highest and lowest salary.

## Objective
Practice numerical data processing using Python and Pandas.

## Approach
1. Created the employee salary data manually as a Pandas DataFrame (name, department, salary).
2. Calculated the statistics using built-in Pandas functions:
   - Total salary: `sum()`
   - Average salary: `mean()`
   - Highest salary: `max()`
   - Lowest salary: `min()`
3. Found the employees with the highest and lowest salary using `idxmax()` and `idxmin()`.
4. Verified the calculated values against the original data using `assert`.
5. Extra: calculated the department-wise average salary using `groupby()`.

## Sample Output
```
Total salary   : 272000
Average salary : 45333.33
Highest salary : 60000 (Rahul)
Lowest salary  : 36000 (Meena)

Department
Finance    41000.000000
HR         37000.000000
IT         52333.333333
Name: Salary, dtype: float64
```

## Files
- `Employee_Salary_Analysis.ipynb`: notebook with the complete analysis
- `README.md`: project explanation

## How to Run
1. Open `Employee_Salary_Analysis.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells from top to bottom.

## Tools Used
Python, Pandas, Jupyter Notebook

## Key Learnings
- Using Pandas for basic statistical calculations
- Difference between total salary and average salary
- Grouping data with `groupby()` for department-level insights

## Author
J Sanjay, AI & Data Science student
