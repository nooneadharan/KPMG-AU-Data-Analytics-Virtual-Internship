# KPMG-AU-Data-Analytics-Virtual-Internship
This repository showcases the tasks, deliverables, and projects I completed during the KPMG Australia Data Analytics Virtual Internship, hosted by Forage. It reflects my hands-on work and problem-solving approach for the internship’s data analysis challenges

## About the Internship
This repository documents my work for the **KPMG Australia Data Analytics Virtual Internship** hosted by Forage. The internship simulates a real-world project for **Sprocket Central Pty Ltd**, a medium-sized bike and cycling accessories company. Through hands-on tasks, I addressed data quality issues, identified high-value customers, and developed actionable insights to optimize marketing strategies. This experience mirrors the challenges faced by KPMG professionals in data analytics, from data cleaning to strategic visualization.

---

## Project Objectives
1. **Data Quality Assessment**: Ensure datasets are accurate, complete, and consistent for reliable analysis.  
2. **Customer Segmentation**: Identify high-value customers from 1,000 prospects using transaction history and demographics.  
3. **Data-Driven Strategy**: Create visual dashboards to communicate trends and propose growth strategies.  

---

## Tasks and Solutions

### **Task 1: Data Quality Assessment**  
- **Objective**: Evaluate datasets (Customer Demographic, Addresses, Transactions) for usability.  
- **Process**:  
  - Identified **missing values** (e.g., job industry fields) and **inconsistencies** (e.g., "VIC" vs. "Victoria").  
  - Flagged **duplicate records** and mismatched customer IDs across tables.  
  - Proposed solutions:  
    - **Imputation** for missing values (median for numeric fields, mode for categorical).  
    - **Standardization** of state abbreviations and date formats.  
  - Tools: Excel, Docx.
- **Deliverable**: [1. Data Quality Assessment](https://github.com/nooneadharan/KPMG-AU-Data-Analytics-Virtual-Internship/tree/main/1.%20Data%20Quality%20Assessment)

---

### **Task 2: Data Insights**  
- **Objective**: Prioritize 1,000 new customers using historical data.  
- **Process**:  
  - **Exploratory Analysis**:  
    - Age distribution: 40–49 age group dominated purchases (42% female).  
    - Top industries: Financial Services (23% profit), Health (17.9%), Manufacturing (12.5%).  
  - **Feature Engineering**:  
    - Created `wealth_segment` tiers (Mass, Affluent, High Net Worth).  
    - Derived `state` opportunities (NSW had highest car ownership-to-bike purchase gap).  
  - **Modeling**: Logistic regression to classify high-value customers.  
    - **Key criteria**: Female, 40–50 years, NSW/VIC residents, employed in Financial Services/Health/Manufacturing.  
  - Tools: Excel, Tableau.  
- **Deliverable**: [2. Data Insights](https://github.com/nooneadharan/KPMG-AU-Data-Analytics-Virtual-Internship/tree/main/2.%20Data%20Insights)

---

### **Task 3: Data Insights and Presentation**  
- **Objective**: Visualize trends and propose growth strategies.  
- **Process**:  
  - **Dashboard Design**:  
    - **Tab 1**: Profit by industry (Financial Services led with $12.5K).  
    - **Tab 2**: Customer demographics (females in NSW/VIC contributed 65% of revenue).  
    - **Tab 3**: Monthly trends (peak sales in March and October).  
  - **Recommendations**:  
    - Target **females aged 40–50** in NSW/VIC via partnerships with health insurers.  
    - Expand into NSW’s untapped car-owning market with bundled promotions.  
    - Enrich data with ABS census metrics (income brackets, commuting habits).  
  - Tools: Tableau.  
- **Deliverable**: [3. Data Insights and Presentation](https://github.com/nooneadharan/KPMG-AU-Data-Analytics-Virtual-Internship/tree/main/3.%20Data%20Insights%20and%20Presentation)

---

## Acknowledgements
- Thank you to KPMG and Forage for providing this hands-on learning opportunity.
- The datasets and scenarios are hypothetical and used solely for educational purposes.
