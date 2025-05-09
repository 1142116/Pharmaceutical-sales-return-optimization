💊 Pharmaceutical Sales & Return Optimization Using Data Analytics
Welcome to the Pharmaceutical Sales & Return Optimization project. This data analytics project is designed to uncover deep insights into the sales performance, return behavior, and operational inefficiencies in a pharmaceutical environment. It combines real-world healthcare retail data with advanced statistical analysis, visualization, and machine learning techniques.

🧠 Project Objective
To analyze pharmaceutical transaction data using Python, Excel, and statistical methods in order to:
Detect patterns in prescription drug sales and returns.
Identify underperforming products and departments.
Predict future net sales based on sales behavior.
Recommend data-driven strategies for inventory and sales optimization.

📊 Problem Statement
In the pharmaceutical industry, product returns and unsold stock are common and costly challenges. Hospitals and pharmacies need better forecasting and analytics to manage:
Overstocking or understocking critical drugs.
Inefficiencies due to high return rates.
Budget leaks from expired or unused inventory.
Performance tracking of departments and specializations.
This project helps stakeholders make evidence-based decisions using descriptive and inferential statistical techniques.

🧰 Tools & Technologies
Tool
Purpose
Python (Pandas, NumPy)
Data wrangling and manipulation
Excel
Raw data inspection and reporting
Seaborn, Matplotlib
Data visualization
Scikit-learn
Regression modeling
SciPy
Hypothesis testing
Jupyter Notebook
Interactive analytics


🗂️ Dataset Overview
Rows: 14,218 (Cleaned: 12,037)
Key Columns:
Typeofsales – Sale or Return
Patient_ID, Specialisation, Dept
Dateofbill, Quantity, ReturnQuantity
Final_Sales, Final_Cost, RtnMRP
DrugName, Formulation, SubCat, SubCat1


🧾 Derived Fields:
Net_Sales = Final_Sales - RtnMRP
Return_Rate = ReturnQuantity / Quantity


📈 Key Analyses Performed
1. Descriptive Analytics
Top-selling drugs and departments by quantity and revenue.
Net sales trends over time (monthly/quarterly).
Department-wise performance metrics.


2. Return Analysis
Return Rate distribution and outliers.
Most returned drug types and formulations.
Comparison between Injection vs. Tablet return rates.


3. Hypothesis Testing
T-Test: Are injectable drugs returned more than tablets?
Significance testing to validate trends and anomalies.


4. Regression Modeling
Linear Regression to predict Net_Sales using:
Quantity
Return Quantity
Department
R² Score used to evaluate model strength.


5. Visual Insights
Monthly sales trend chart.
Return rate histogram.
Bar plots for department-wise and drug-wise sales insights.

✅ Key Achievements
Achieved data-driven root cause analysis of return-heavy products.
Built a regression model with actionable variables to forecast future sales.
Identified high-risk product categories for procurement optimization.
Designed visual reports to communicate insights clearly to non-technical stakeholders.

📌 Business Impact
This project provides ready-to-implement analytics for any pharmaceutical retail or hospital chain looking to:
Optimize drug procurement and stock levels.
Minimize returns and improve compliance.
Monitor departmental performance.
Build forecasting models for inventory and revenue planning.

🚀 How to Use
Download the Jupyter Notebook
Load the Cleaned Excel Data
Run each section cell-by-cell to explore insights and visuals
Modify with your data or integrate into Power BI dashboards

💼 Ideal For
Aspiring Data Analysts in Healthcare or Pharma
MNC applications where domain + analytics skill is valued
Interview discussions for showcasing real-world problem-solving

📮 Contact
👤 Anup Umrekar (Data Analyst)
📧 anupumrekar@gmail.com
📍 Ahmedabad, India
🔗 [LinkedIn Profile](https://www.linkedin.com/in/anupumrekar/)
