# 📊 Excel Data Analysis Project: Sales Analysis and Order Management.

![](intro.jpeg)

### 📁 Project Summary
This project was initiated to help a retail business address core operational concerns through data-driven insights. The client posed the following key business questions:

- Which products generate the highest revenue and profit? What are their associated costs?
- What are the trends in revenue, cost, and profit over time?
- How do order statuses (Completed vs. Returned) evolve, and what patterns can be identified?

To address these, I developed a fully automated, dynamic Excel dashboard that integrates data collection, cleaning, analysis, and visualization. The tool empowers stakeholders to make informed decisions and optimize operations independently.

### 🎯 Project Objectives
1. Analyze trends and patterns in order statuses (Completed vs. Returned).
2. Test two competing hypotheses regarding delivery time and its influence on return rates:
  - H₀ (Null): Delivery time has no impact on returns.
  - H₁ (Alternative): Orders with longer delivery times are more likely to be returned.
3. Build a dynamic Excel dashboard that automates the end-to-end data analysis workflow.

### 🧹 Data Cleaning
- Standardized Formats: Ensured consistency across date, time, numeric, and text formats.
- Validation: Performed column-by-column error checking and corrected irregularities (e.g., spacing, capitalization).
- Duplicates Removed: Eliminated repeated entries to maintain data integrity.
- Missing Values: Filled critical missing data (e.g., revenue) using mean imputation.

**Raw data (Before data cleaning)**              |  **Raw data (After data cleaning)**
:----------------------------------------------: | :------------------------------:
![](raw_data.png)                                |  ![](Cleaned_data.png)  
[Download data here](sales_data.xlsx)            |  [Download data here](Cleaned_data(2).xlsx)


### 🛠 Data Processing
- Derived Columns: Extracted Day, Month, Year, and calculated Profit from existing Order Date and numeric fields.
- VLOOKUP: Linked related tables to enrich data context.
- Filtering & Sorting: Structured the dataset to focus on relevant subsets for analysis.

### 📈 Exploratory Data Analysis (EDA)
- Descriptive Statistics: Uncovered key data patterns, distributions, and outliers.
- Hypothesis Testing (Two-Sample t-Test): Tested the influence of delivery time on return likelihood.
- Validated results statistically to drive actionable insights.

### 🔁 Automated Data Pipeline
- Data Entry Form: Built a user-friendly Excel form using VBA to allow seamless data input and data collection.
- Macro-Driven Automation:
  - Submission button populates and stores data.
  - Confirmation pop-up upon successful submission.
  - Automatic form reset for new entries.

**Automated Data Pipeline (Data Entry Form)**
![](Pipeline(Sales Form).png)
