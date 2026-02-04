**power-query-hr-analytics**

##  Project Overview
This project focuses on performing **data transformation using Power Query** and building an **HR Analytics dashboard** using **Power BI Desktop**.  
The dashboard helps analyze employee attrition, salary distribution, and workforce characteristics using cleaned and transformed HR data.

##  Tools Used
- Power BI Desktop  
- Power Query Editor  
- HR Analytics Dataset (CSV)

##  Dataset Description
The HR Analytics dataset contains employee-related information such as:
- Age and Age Group
- Department and Job Role
- Gender and Marital Status
- Monthly Income and Job Level
- Attrition status
- Work-life balance, overtime, training, and experience details

## Data Transformation (Power Query)
All data preparation was performed in **Power Query Editor**, and each step is recorded under **Applied Steps**.

### Key transformation steps:
1. Imported HR Analytics dataset into Power BI.
2. Removed unnecessary columns such as EmployeeCount, EmployeeNumber, Over18, and StandardHours.
3. Renamed column headers to improve readability.
4. Checked for missing values and handled them using replace or filter methods.
5. Corrected data types for numeric and categorical columns.
6. Split columns where required (Age Group).
7. Created conditional columns:
   - **Age Category** (Young, Mid-Age, Senior)
   - **Salary Band** based on Monthly Income
8. Applied all transformations and loaded the cleaned data into the Power BI model.
   
##  Dashboard Visualizations
The dashboard includes the following visualizations:

- **Count of Employee ID by Department and Attrition**  
  Identifies departments with higher employee attrition.

- **Sum of Monthly Income by Job Role**  
  Compares salary distribution across different job roles.

- **Count of Employee ID by Age Category**  
  Shows employee distribution across age groups.

- **Count of Employee ID by Gender and Attrition**  
  Analyzes attrition trends among male and female employees.

- **Sum of Monthly Income by Job Level**  
  Displays how income varies across job levels.

- **Count of Employee ID by OverTime**  
  Highlights employee distribution based on overtime status.

- **Sum of Distance From Home by Attrition**  
  Analyzes whether distance from home impacts attrition.

- **Sum of Performance Rating by Training Times Last Year**  
  Shows the relationship between training frequency and performance.

##  Key Insights
- Certain departments show higher attrition rates.
- Mid-age employees form the largest workforce group.
- Employees working overtime show noticeable attrition trends.
- Monthly income increases with job level.
- Training frequency has an impact on performance ratings.

