# Customer-Churn-Analysis

**The Problem Statement:**
The primary goal of churn analysis is to understand why customers churn by examining customer behavior patterns. Churn analysis often reveals patterns that indicate common motivators for customers to leave you, such as price sensitivity or poor product adoption. It also demonstrates how customers engage with your product throughout its lifecycle. These insights will help businesses strategize and make informed decisions to reduce churn.

**DataSet**:
The data for this project is a CSV file containing the following columns:

**Column Description:**
  customer_id = Unique identifier for each customer
  credit_score = Credit score of the customer
  country = Country of the customer
  gender = Gender of the customer
  age = Age of the customer
  tenure Duration (in years) = the customer has been with the company
  balance = Account balance of the customer
  products_number = Number of products owned by the customer
  credit_card = Whether the customer owns a credit card (1 = Yes, 0 = No)
  active_member = Whether the customer is an active member (1 = Active, 0 = Inactive)
  estimated_salary = Estimated salary of the customer
  churn = Whether the customer churned (1 = Yes, 0 = No)

**Key Highlights:**
  Comprehensive Overview: Visualizes total customers, active vs. inactive customers, and churn rate.
  Demographic Insights: Analyzes customer distribution by gender, age group, and country.
  Behavioral Analysis: Examines the impact of credit scores and account balances on churn.
  Geographical Breakdown: Highlights churn rates across different cities.

**Steps:**
  Downloaded the dataset from Kaggle, performed basic ETL processes in Power Query, and uploaded data to Power BI desktop.
  Created Conditional Columns for Age groups, credit scores, Account Balances.
  Data Modelling: Created a reference table for Age Group, reference query for credit scores, Account Balances and removed duplicates.
  Created DAX measures and built relationships with many-to-one and one-to-many.
  Used Donut charts, Line and Clustered Column Charts, Slicers, Gauge chart, KPI for enhanced visualizations and created a report.
   
**Findings:**
  Churn Rate: ~20-25% of customers are churning.
  Region-Specific Trend: Spain exhibits slightly higher churn than France and Germany.
  Inactive members and those without credit cards show higher churn.
  Product 3 adoption is low (~3%) and associated with higher attrition.

**What I learnt:**
  The power of data storytelling in delivering actionable insights for business challenges. I learned how to clean and transform data for accurate analysis in Power BI. I gained insights into customer churn and     key metrics like churn and retention rates. I enhance my skills in data visualization and segmentation to identify trends. I also learned to use predictive analysis to forecast churn and develop retention         strategies. Finally, I improved my ability to present findings clearly to stakeholders.

