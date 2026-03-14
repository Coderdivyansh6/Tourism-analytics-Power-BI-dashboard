# 🌍 Global Tourism Insights Dashboard

## 📌 Project Overview
Tourism plays a vital role in the economic development of countries. Governments and tourism authorities collect large volumes of data related to international tourist arrivals, visitor origins, and average stay durations. However, this data is often scattered and difficult to analyze effectively.

This project develops an **interactive tourism analytics dashboard using Power BI** to transform raw tourism data into meaningful insights. The dashboard helps policymakers, analysts, and researchers understand tourism trends, regional contributions, and visitor behavior.

---

## 🛠️ Problem Statement
Tourism data is often stored in raw formats and spread across multiple sources, making it difficult to analyze and interpret. Without proper analytical tools, it becomes challenging to:
- Identify growth trends in tourist arrivals  
- Understand regional tourism performance  
- Evaluate visitor behavior over time  

The key challenge is to **transform raw tourism data into actionable insights** that support data-driven decision making.

---

## ✅ Proposed Solution
The solution involves building a **Power BI dashboard** with the following steps:

1. **Data Collection**  
   - Dataset sourced from the **National Data & Analytics Platform (NDAP), Government of India**.  
   - Contains information on country, region, year, tourist arrivals, and average stay duration.

2. **Data Transformation (Power Query)**  
   - Renamed columns for clarity  
   - Extracted year values from raw text  
   - Converted data types to numeric formats  
   - Handled missing values (null strategy)

3. **Data Analysis (DAX Measures)**  
   - Created calculated metrics such as:  
     - `Total Arrivals`  
     - `Arrivals Growth %`  
     - `Average Stay Duration`  
     - `Top Source Country`  
     - `Total Tourist Days`

4. **Visualization (Dashboard)**  
   - KPI Cards for top metrics  
   - Bar + Line chart for arrivals trend  
   - Donut chart for regional distribution  
   - Treemap for country contribution  
   - Map visualization for global tourist sources  
   - Filters & slicers for interactive analysis  

---

## 📊 System Approach
- **Slicers**: Allow users to filter by year and region  
- **Charts**: Different chart types chosen for clarity  
  - Bar chart → Top source countries  
  - Donut chart → Regional distribution  
  - Treemap → Country contribution  
  - Map → Global distribution  
- **KPI Cards**: Highlight critical metrics with icons and comparison values  
- **Insights Box**: Provides analytical commentary (e.g., “South Asia contributes 27.8% of total tourists”)  

---

## 🔎 Analytical Workflow
1. Collect dataset from NDAP portal  
2. Import into Power BI  
3. Transform data using Power Query  
4. Handle missing values  
5. Create DAX measures  
6. Design dashboard layout with charts and KPIs  
7. Add filters, slicers, and insights  

---

## 📈 Results
The dashboard provides:  
- Identification of **top tourist source countries**  
- **Regional distribution** of tourist arrivals  
- **Trends in average stay duration**  
- **Geographic visualization** of global tourist movement  

---

## 📌 Conclusion
- Raw tourism data successfully transformed into meaningful insights  
- Dashboard highlights growth trends, regional contributions, and visitor behavior  
- Enables policymakers and analysts to make **data-driven decisions**  

---

## 🚀 Future Scope
- Integration of **real-time tourism data**  
- **Predictive analytics** using machine learning for forecasting arrivals  
- Expansion to include **multiple datasets** (e.g., domestic tourism, seasonal trends)  
- Deployment on **cloud platforms** for wider accessibility  

---

## 📚 References
- National Data & Analytics Platform (NDAP): [https://ndap.niti.gov.in](https://ndap.niti.gov.in)  
- Microsoft Power BI Documentation  
- Government of India Tourism Data  
- Power BI Community Resources  

---



## 👨‍💻 Author
**Divyansh Goswami**
Lakshmi Narain College of Technology — MCA
Email: divyanshgoswami62@gmail.com
