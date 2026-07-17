📊 HR Analytics Dashboard | Power BI
📌 Project Overview

The HR Analytics Dashboard is an interactive Power BI solution developed to help HR managers and business leaders analyze workforce data, monitor employee distribution, and make data-driven decisions.

The dashboard provides insights into employee headcount, gender diversity, department performance, job roles, hiring trends, and geographical distribution through interactive visualizations.

This project demonstrates the complete Business Intelligence workflow, including data cleaning, data modeling, DAX calculations, dashboard design, and business insight generation.

🎯 Business Problem

Organizations often store HR information across multiple spreadsheets and systems, making it difficult to answer questions such as:

How many employees does the company have?
What is the gender distribution?
Which departments have the highest workforce?
Which job roles are most common?
How has employee hiring changed over time?
Which countries have the highest employee count?

Without a centralized dashboard, HR teams spend significant time preparing reports manually.

💡 Solution

Developed an interactive HR Analytics Dashboard using Power BI that transforms raw employee data into meaningful business insights.

The dashboard enables HR professionals to:

Monitor total workforce
Analyze employee demographics
Track hiring trends
Compare departments
Analyze job distribution
Monitor employee locations
Filter reports dynamically
🛠️ Tools & Technologies
Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Data Modeling
Excel Dataset
📂 Dashboard Features
📍 Executive KPIs
Total Employees
Male Employees
Female Employees
Gender Percentage
📈 Employee Trend Analysis

Visualizes employee growth by year.

Business Value:

Understand hiring trends
Identify recruitment growth
Analyze workforce expansion
👨‍💼 Gender Diversity Analysis

Displays

Male Employees
Female Employees
Gender Percentage

Business Value:

Monitor diversity initiatives
Track gender balance
🏢 Department Analysis

Shows employee count by department.

Departments include:

Engineering
Finance
HR
Marketing
IT
Sales
Accounting

Business Value:

Workforce planning
Department comparison
Resource allocation
💼 Job Role Analysis

Displays employee count across various job positions.

Business Value:

Understand organizational hierarchy
Identify workforce concentration
Support succession planning
🌍 Employee Distribution by Country

Shows employee count across countries.

Business Value:

Analyze global workforce
Identify regional employee concentration
🎛 Interactive Filters

Users can filter dashboard by:

Department

All visuals update dynamically.

📊 Dashboard KPIs
KPI	Description
Total Employees	Overall workforce
Male Employees	Total male employees
Female Employees	Total female employees
Gender Ratio	Male vs Female percentage
Department Count	Employees by department
Job Role Count	Employees by designation
Country Distribution	Employees by country
Hiring Trend	Employee growth over years
📁 Data Preparation

The dataset was cleaned using Power Query by:

Removing duplicates
Handling missing values
Correcting data types
Formatting date fields
Renaming columns
Removing unnecessary fields
⭐ Data Modeling

Implemented a structured Power BI data model with:

Optimized relationships
Clean column naming
Proper data types
DAX measures for KPI calculations
📐 DAX Measures Used

Examples include:

Total Employees = COUNT(Employee[Employee ID])

Male Employees =
CALCULATE(
    COUNT(Employee[Employee ID]),
    Employee[Gender]="Male"
)

Female Employees =
CALCULATE(
    COUNT(Employee[Employee ID]),
    Employee[Gender]="Female"
)

Gender % =
DIVIDE([Male Employees],[Total Employees])
📈 Business Insights

The dashboard helps answer key business questions:

What is the total employee strength?
What is the current gender ratio?
Which department has the largest workforce?
Which job positions have the highest employee count?
How has hiring changed over time?
Which countries contribute the most employees?
🚀 Business Impact

This dashboard enables HR teams to:

Reduce manual reporting effort
Improve workforce visibility
Support strategic hiring decisions
Monitor workforce diversity
Track organizational growth
Enable faster decision-making through interactive reporting
📸 Dashboard Preview

(Add your dashboard screenshot here)

Example:

images/HR_Analytics_Dashboard.png
📂 Project Structure
HR-Analytics-Dashboard/
│
├── Dashboard/
│   └── HR Analytics Dashboard.pbix
│
├── Dataset/
│   └── HR_Data.xlsx
│
├── Images/
│   └── Dashboard.png
│
├── README.md
│
└── LICENSE
🎯 Skills Demonstrated
Power BI Dashboard Development
Power Query (ETL)
Data Cleaning
Data Transformation
Data Modeling
DAX
KPI Design
Business Analytics
HR Analytics
Interactive Reporting
Data Visualization
📌 Future Enhancements
Employee Attrition Analysis
Employee Performance Dashboard
Salary & Compensation Analytics
Hiring Funnel Analysis
Employee Retention Metrics
Diversity & Inclusion Dashboard
Predictive HR Analytics using Machine Learning
👩‍💻 Author

Ranjani G

Aspiring Data Analyst | Power BI Developer | Excel
