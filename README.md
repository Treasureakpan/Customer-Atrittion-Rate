# Customer Attrition Rate
![Alt text](https://github.com/Treasureakpan/Customer-Atrittion-Rate/blob/main/Customer%20Atrittion%20rate.jpg)
## Introduction
The aim of this project is to create an **interactive employee analytics dashboard** in **Power BI** for **AMC Company**.  
This dashboard provides key stakeholders with **meaningful insights** and supports **data-driven decisions** related to the workforce, covering areas such as:

- Employee demographics  
- Salary trends  
- Performance metrics  

---

## Dataset and Data Sourcing
The dataset used consists of **one table** (`employee` table) with:  

- **14 columns**  
- **1,000+ rows**  

---

## ⚠️ Note
The dataset used in this project is **entirely fictional** and created **solely for demonstration purposes**.  
It does **not** represent any real company, organization, or individual.  

The content is intended to showcase the **data visualization** and **analytical capabilities** of **Power BI**.
# Employee Analytics Dashboard (Power BI)

## Skills / Concepts Demonstrated
The following **Power BI features and concepts** were applied:


- **Data Ingestion** into the Power BI environment
- **Data Modeling**: Not applied (dataset had only one table)
- **DAX Concepts**: Calculated Columns, Measures, Aggregation Functions
- **KPIs Tracked**:  
  - Total Employees  
  - Total Annual Salary  
  - Bonus Percentage  
  - Exited Employees  
  - Attrition Rate  
  - Average Annual Salary  

---

## 🚨 Problem Identified

### 🔴 High Attrition Rate (10.3%)
- Indicates the company is losing a significant portion of its workforce.  
- Impacts: **Reduced productivity, increased hiring costs, and loss of knowledge.**

### 🔴 Departments Most Affected
- **IT, Human Resources, and Engineering** → highest number of exited employees.  
- **Support & Finance** → highest attrition rates, signaling dissatisfaction.  

### 🔴 Disparity in Bonus & Salary
- **Corporate & Specialty sectors** → highest bonuses.  
- **Manufacturing** → lowest bonuses.  
- **Vice Presidents & Directors** → significantly higher pay than Managers → dissatisfaction at lower levels.  

### 🔴 Demographic Imbalance
- Concentration of employees within specific **age groups** and **locations**.  
- Suggests limited diversity or over-reliance on certain demographics.  

---

## Data Transformation & Cleaning
![Alt text](https://github.com/Treasureakpan/Customer-Atrittion-Rate/blob/main/Power%20query%202.png)

Data was cleaned and transformed in **Power Query Editor** with steps such as:  
- Adjusting **Age** and **Bonus** columns from *text → number*.  
- Adjusting **Employee ID** from *number → text*.  

---

## Visualizations

![Alt text](https://github.com/Treasureakpan/Customer-Atrittion-Rate/blob/main/Customer%20Attrition%20.png)

The dashboard includes:  
- Employee distribution by **gender** and **ethnicity**  
- **Top 5 annual salaries** by employees  
- **Bonus percentage** across business units  
- Exited employees by **department**  
- **Age distribution** by age group & gender  
- **Geographical distribution** of employees (country & city map)  
- Highest & lowest salary employees  
- **Attrition rate** by department & business unit  
- **Average annual salary** by department & job title  

---

## Recommendations

1. **Conduct Exit Interviews**  
   - Investigate why IT, HR, and Engineering employees are leaving.  
   - Explore workload, job satisfaction, management, and growth opportunities.  

2. **Review Compensation Strategy**  
   - Ensure bonuses & salaries are performance-based and fair.  
   - Adjust incentives for under-compensated departments (e.g., Manufacturing).  

3. **Focus on Employee Retention Programs**  
   - Launch mentorship, upskilling, and internal mobility programs.  
   - Improve work-life balance & mental health support.  

4. **Address Diversity & Inclusion**  
   - Use demographic data to build a more balanced and inclusive workforce.  
   - Ensure equal opportunities in **hiring and promotions**.  

---

## Conclusion
The AMC Employee Analytics Dashboard reveals a **10.3% attrition rate**, with IT, HR, and Engineering most affected.  
Key issues include **compensation disparities** and **workforce imbalances**.  

By implementing **fair pay strategies, retention programs, and inclusive hiring practices**, AMC can:  
- Reduce turnover  
- Boost employee morale  
- Retain top talent in the long term  
