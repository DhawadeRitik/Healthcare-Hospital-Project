# 🏥 Healthcare Analytics Dashboard  
### Power BI | DAX | Data Modeling | Business Intelligence Project  

---

## 📌 Project Overview  

The **Healthcare Analytics Dashboard** is a comprehensive Business Intelligence solution designed to analyze hospital operations, doctor performance, and patient trends.

The solution is divided into three analytical reports:

1. **Healthcare Overview Report**
2. **Patient Analysis Report**
3. **Doctor Overview Report**

This dashboard enables hospital management to monitor KPIs, evaluate doctor efficiency, analyze patient distribution, and optimize operational performance.

---

# 📊 1️⃣ Healthcare Overview Report

## 🎯 Objective  
Provide a high-level operational summary of the hospital.

## 🔹 Key KPIs
- Total Patients
- Bed Nights
- Average Age
- Referral Percentage (RP %)
- In-Patient %
- Average Daily Patients (DAP)

## 🔹 Insights Included
- 📈 Patient Trend Over Time
- 👨‍⚕️ Patient Distribution by Gender
- 🏥 Patient Count by Department
- 📊 Patient Distribution by Age Group
- 📋 Doctor Performance Table:
  - Total Patients
  - IP %
  - Referral %
  - Average Daily Patients

## 💡 Business Value
- Monitor hospital capacity
- Identify high-performing departments
- Track patient growth trends
- Understand demographic distribution

---

# 📊 2️⃣ Patient Analysis Report

## 🎯 Objective  
Analyze patient handling patterns and doctor contribution.

## 🔹 Core Features

### ✅ Dynamic Top N Doctor Analysis
- User-controlled Top N selection (1–5)
- Automatic calculation of:
  - Contribution %
  - Remaining doctors grouped as **"Others"**

Example Output:
> Top 5 Doctors Handle 27.3% of Total Patients

---

### ✅ Department-wise Breakdown
- Donut chart showing department contribution

### ✅ Referred Patient % vs Total Patients
- Scatter plot analyzing referral behavior

### ✅ In-Patient vs Out-Patient Daily Comparison
- Day-wise trend analysis
- Hospital workload distribution

### ✅ Weekend Analysis
- Patients handled on weekends
- In-Patient vs Out-Patient weekend breakdown

## 💡 Business Value
- Identify workload concentration
- Measure doctor dependency
- Evaluate referral performance
- Analyze weekend operational efficiency

---

# 📊 3️⃣ Doctor Overview Report

## 🎯 Objective  
Deep-dive performance evaluation at individual doctor level.

## 🔹 Key KPIs
- Total Patients
- Bed Nights
- Average Age
- Referral %
- In-Patient %
- Follow-up %
- Average Daily Patients

## 🔹 Doctor Profile Section
- Doctor Image
- Department Name
- Rank in Department
- Total Patients
- Referral Contribution
- In/Out Patient Split
- Follow-up Count
- Average Daily Patients

## 🔹 Additional Analysis
- Top 5 Doctors by Patients
- Top 5 Doctors by Referral %
- Patient Type Breakdown
- Visit Type Analysis (New vs Follow-up)

## 💡 Business Value
- Doctor performance benchmarking
- Department-level ranking
- Referral efficiency evaluation
- Patient retention analysis

---

# 🧠 Data Model & Relationships

The report is built using a **Star Schema Data Model**.

# Schema Diagram
<img width="1498" height="672" alt="image" src="https://github.com/user-attachments/assets/04989452-f9a9-4a10-8387-0d40e5ab3c48" />


## 🗂 Fact Table
- Patient Table (Transactional Data)

## 📁 Dimension Tables
- Doctor Table
- Calendar Table

## 🔗 Relationships
- One-to-Many → Doctor → Patient
- One-to-Many → Calendar → Patient
- Proper filter propagation for accurate DAX evaluation

### Model Benefits
- Clean filter context
- High-performance calculations
- Scalable architecture
- Optimized DAX implementation

---

# ⚙️ Advanced DAX Implemented

- Dynamic Top N with "Others" grouping
- RANKX for department-wise ranking
- ALLSELECTED for slicer-aware calculations
- TOPN with parameter table
- CALCULATE context transition
- Dynamic Title Measures
- Contribution Percentage Calculations
- Weekend & Visit Type Segmentation

---

# 🎨 Dashboard Design Features

- Clean healthcare theme
- KPI highlight cards
- Slicer-driven dynamic filtering
- Drill-down capable visuals
- Executive-level presentation layout
- User-friendly report navigation

---

# 🚀 Business Questions Answered

- Which departments handle the highest patient load?
- What percentage of patients are referred?
- Who are the top-performing doctors?
- How dependent is the hospital on Top N doctors?
- What is the In-Patient vs Out-Patient distribution?
- How does weekend load vary?
- What is the follow-up rate?

---

# 🏆 Skills Demonstrated

- Power BI Dashboard Development
- Data Modeling (Star Schema)
- Advanced DAX Calculations
- Filter Context & Context Transition
- Healthcare KPI Analytics
- Performance Optimization
- Data Storytelling & Visualization

---

# 📌 Project Highlights

✔ Dynamic Top N Contribution Analysis  
✔ Department Ranking Logic  
✔ Doctor-Level Drilldown View  
✔ Patient Demographic Segmentation  
✔ Referral & Weekend Analysis  
✔ Professional Executive Dashboard  

---

## 📎 Tools Used
- Power BI
- DAX
- Data Modeling
- Excel / SQL (Data Preparation)

---

## 📬 Author

**Ritik Dhawade**  
Aspiring Data Analyst | Business Intelligence Developer  

