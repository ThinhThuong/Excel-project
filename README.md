# Bike Sale Data Analysis (using Excel)
## Introduction:
This report presents a data analysis conducted on a dataset containing information about bike sales over a one-year period. 
## Dataset: 
<a href="https://github.com/ThinhThuong/Excel-project/blob/main/1.%20Project%20Bike%20Sales.xlsx">Bike Sale</a> The dataset comprises 1027 rows (including a header row) and 13 columns.

## Objective:
To identify potential target markets and ideal customer profiles to optimize sales strategies and attract more customers.

## Question
1. Which country has the highest bike sales?
2. What gender is more likely to buy a bike?
3. Is there a relationship between commute distance and bike purchases?
4. Which age range has the highest number of bike buyers?

## Process
### 1. Eliminate Duplicate Records
Start by removing duplicate rows to ensure the dataset is clean and accurate for analysis.

### 2. Simplify Confusing Values
Replace ambiguous values in the columns “Marital Status” and “Gender” for better readability:
- Convert M to Married and S to Single.
- Convert F to Female and M to Male.
Example: Change M in Marital Status to Married for clarity.

### 3. Group Age into Categories
Simplify the continuous Age feature by grouping it into meaningful categories:
- Adolescent (<31 years)
- Middle Age (31–54 years)
- Old (>54 years)
- Invalid (if age falls outside these ranges)

Add a new column, “Age Bracket”, to store these categories for enhanced interpretability.

![image](https://github.com/user-attachments/assets/da986eb8-b62b-4ab3-b839-2f1638f51f5a)

### 4. Create Pivot Tables for Insights
- Dedicate a separate sheet for pivot tables to facilitate easy updates and adjustments.
- Build pivot tables based on specific questions and outline the key metrics.
- Lay the groundwork for a simple dashboard to present data interactively.
![image](https://github.com/user-attachments/assets/b425a221-16d0-4f53-971c-34a2a7fd3fd7)

### 5. Design an Interactive Dashboard
- Create a dedicated sheet for the dashboard.
- Incorporate slicers to filter variables dynamically and uncover deeper insights.
- Format the dashboard and slicers with a cohesive and professional theme to enhance visual appeal.

![image](https://github.com/user-attachments/assets/3b2a2e04-b396-48eb-9335-4cf27eb9fc7e)

