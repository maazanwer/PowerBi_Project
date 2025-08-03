# Power BI Dashboard Portfolio

This repository contains multiple Power BI projects designed to showcase skills in data analysis, DAX, data modeling, and professional dashboard design. Each project focuses on a specific domain and demonstrates end-to-end report building.

---

## 📌 Table of Contents
- [Project 4: Batch Performance Analytics – Power BI Dashboard](#Batch-Performance-Dashboard)
- [Project 1: Sales Analytics Dashboard](#project-1-sales-analytics-dashboard)
- [Project 2: Insurance Analytics Dashboard](#project-2-insurance-analytics-dashboard)
- [Project 3: UPI Transaction Analytics Dashboard](#project-3-upi-transaction-analytics-dashboard)
- [Notes](#notes)
- [Connect with Me](#connect-with-me)

---

## 🎓 Batch Performance Dashboard

## 📌 Project Overview
This project analyzes the academic performance of an entire university batch using **Power BI**.  
It is based on **real-world data** (4,000+ rows, 6–7 columns), which I personally collected, cleaned, and transformed from raw numeric sheets.  

The dashboard is designed to:
- Track individual student performance across 8 semesters and 20+ subjects
- Compare students against class averages, rankings, and percentiles
- Highlight anomalies, failures, and consistency patterns
- Reveal grading trends and subject difficulty across instructors
- Provide interactive exploration where each visual filters others logically

---

## 🛠️ Features & Pages

### ✅ **1. Personal & Subject Overview**
- Displays an individual student's strongest and weakest subjects  
- Shows semester-wise performance trend  
- KPIs: Average Score, Best/Weakest Subject

### ✅ **2. Peer Comparison**
- Ranks all students (1–82) and calculates percentiles dynamically  
- Score distribution histogram with highlighted individual performance  
- Comparison bar chart by IDs

### ✅ **3. Consistency & Anomaly Analysis**
- Scatter plot: **Average Score vs Consistency vs Rank** (bubble size scaled by inverted rank)  
- Heatmap showing pass/fail trends per student and subject  
- Insights into students with irregular performance patterns

### ✅ **4. Instructor Insights**
- Average scores grouped by instructor  
- Breakdown of subject performance by instructor  
- Identifies toughest and easiest graders

### ✅ **5. Individual vs Class Battle**
- Side-by-side comparison of **individual average vs class average** (subject-wise and semester-wise)  
- Dynamic filtering for subject, semester, and instructor

### ✅ **6. Top 10 Performance Battle**
- Semester-wise line chart of the top 10 performers  
- Shows ranking shifts across semesters (who rose, who fell)

---

## 🧹 Data Preparation
- **Source:** Raw numeric grade sheets (manually compiled)  
- **Rows:** 4,000+  
- **Columns:** 6–7 (Student ID, Subject, Instructor, Semester, Exam Type, Score, etc.)  
- Cleaned, standardized, and transformed using Power Query and manual checks.

---

## 🧠 Techniques & Skills Demonstrated
- **Power BI Development**
  - DAX measures (Ranking, Percentile, Consistency, Inverted Rank Bubble Sizes)
  - Dynamic cross-filtering and drill-downs
  - Heatmap and custom scatter plot sizing logic
- **Data Cleaning**
  - Manual inspection and correction of 4,000+ raw rows
  - Handling missing/erroneous data
- **Data Storytelling**
  - Visualization flow designed to answer "why" questions
  - Logical narrative from personal performance → class patterns → instructor influence

---

## 🎨 Design & Theme
- **Dark Theme** with **Gold Accents** for clear readability and a professional aesthetic  
- Interactive elements configured for logical exploration

---

## 🚀 Key Insights
- Some subjects had extremely high failure rates compared to others  
- Certain instructors consistently graded lower/harder than peers  
- Top performers maintained high consistency, while low performers showed irregular patterns  
- The dashboard provides **evidence-backed insights** into grading fairness, student trends, and anomalies

---

## 📂 Files Included
- `Batch_Performance.pbix` – Power BI report file  
- `Dataset.xlsx` – Cleaned dataset (if shareable)  
- `README.md` – Project documentation (this file)  

---

## 📈 Future Enhancements
- Add **predictive analytics** (GPA forecast) using Python
- Integrate with **Plotly/Dash** for interactive web deployment
- Expand visuals with **advanced Power BI bookmarks** and **storytelling animations**

---

## 🏆 Why This Project?
This dashboard not only analyzes data but also **tells a story** of performance, struggle, and growth.  
It is my **flagship project** to demonstrate:
- **Technical Power BI expertise**
- **Analytical thinking**
- **Real-world data handling**
- **Strong data storytelling skills**

---

## Project 1: Sales Analytics Dashboard

A dynamic and interactive sales dashboard built using fictional sales data.

### Key Features
- KPI Cards for Total Sales, Profit, Orders, and Units Sold  
- Year-over-Year Growth Tracking  
- Daily and Monthly Sales Trends  
- Top & Bottom 5 Products  
- Calendar Heatmap (Week × Month)  
- Dynamic, Context-Aware Filtering  
- Map-based Regional Sales Performance  

### Tools Used
- Power BI Desktop  
- DAX  
- Data Modeling

---

## Project 2: Insurance Analytics Dashboard

An insurance dashboard focused on claim trends, risk profiling, and premium analysis.

### Key Features
- High-Risk Customer Identification using Risk Ratio  
- Claims-to-Premium Ratio Analysis  
- 30/60/90-Day Policy Expiry Tracker  
- Age Group & Policy Type Claim Distribution  
- Gender-based Premium Contributions  
- Claim Explorer with Drill-through Functionality  
- KPI Cards for Settled Claims, Pending Claims, and Premiums  

### Tools Used
- Power BI Desktop  
- DAX  
- Relationship Modeling  
- Conditional Formatting & Custom Filtering Logic  
- MSSQL

---

## Project 3: UPI Transaction Analytics Dashboard

An analytical dashboard visualizing UPI transaction behavior, with an emphasis on interactivity and user-centric insights.

### Key Features
- Monthly Transaction Trend (Line & Bar toggle using Bookmarks)  
- Matrix visual for city-wise monthly breakdown of Amounts & Remaining Balances  
- Time vs Purpose Heatmap to analyze customer behavior patterns  
- Bubble chart showing transaction device types across Age Groups  
- Smart Tooltips with on-hover insights including:
  - Merchant-specific metrics  
  - Purpose distributions  
  - Failed transaction tracking  
- Dynamic filtering for Payment Method, City, Purpose, Bank Name, and more  

### Tools Used
- Power BI Desktop  
- DAX  
- Tooltip Pages & Bookmark Navigation  
- UX-focused Visual Layout  
- Data Modeling



---

## Connect with Me

Feel free to connect on [LinkedIn](https://www.linkedin.com/in/muhammad-maaz-anwer-63105523a/) or reach out if you're interested in collaboration, feedback, or just to talk data.
