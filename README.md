# AssingmentCipherSchool
## Contains Assingment Files for CIpher Schools


## ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### TODO
Weekly assignment for practice : 
🎯 Objective:
Perform data cleaning and analysis on employee performance data using Python (pandas) and save the output in an Excel file with multiple sheets.

Data set : https://docs.google.com/spreadsheets/d/1wrH9VMn3BB1t8Y5F7bmtC0z0-8QCRFRf/edit?usp=drive_link&ouid=106177324977353126171&rtpof=true&sd=true

✅ Tasks to Perform in Python:
🔹 1. Data Cleaning
Load the data using pandas.

Convert JoinDate to datetime format (dd-mm-yyyy).

Ensure Salary and PerformanceRating are numeric.

Check and handle any missing values (if any).

🔹 2. Feature Engineering
Create a new column Tenure:
→ Tenure = 2025 − Year(JoinDate)

Create a new column SalaryCategory:

Salary < 50,000 → "Low"

Salary between 50,000–90,000 → "Medium"

Salary > 90,000 → "High"

🔹 3. Aggregated Analysis (GroupBy / Pivot Logic)
Generate the following summary tables:

avg_salary_by_dept: Average Salary per Department

gender_count_by_dept: Count of Employees by Gender and Department

avg_rating_by_dept: Average Performance Rating per Department

low_performers: Employees with Performance Rating ≤ 2

🔹 4. Output
Save all the above into a single Excel file with multiple sheets using pandas.ExcelWriter.
