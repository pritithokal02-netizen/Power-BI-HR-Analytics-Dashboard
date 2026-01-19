# 📊 HR Analytics Dashboard — Power BI Project

A Power BI dashboard that provides **HR insights and attrition analysis** for employee data.

---

## 💼 Project Overview

This dashboard was created in **Power BI Desktop** to analyze key HR metrics such as:

- Total number of employees  
- Employee attrition (count & rate)  
- Average age, salary, and tenure  
- Attrition analysis by **education**, **age group**, **salary slab**, **years at company**, **job role**, and **gender**

It enables interactive exploration of HR trends and helps stakeholders make informed decisions. :contentReference[oaicite:1]{index=1}

---

## 📊 Dashboard Highlights

The dashboard includes:

- **Top KPI cards**: Total employees, attrition count, attrition rate, average age, average salary, average years  
- **Charts & visuals**:
  - Attrition by education level (donut/pie chart)
  - Attrition by age groups (bar chart)
  - Attrition by job role (bar chart)
  - Attrition by salary slab (bar chart)
  - Attrition by years at company (line/area chart)
  - Attrition count by gender (card or small bar)
  - Job role breakdown table  
- **Slicers/filters** to segment data by department and other attributes  
*(As seen in the project screenshot.)*

---

## 📁 Files in This Repository

📦 hr-analytics-powerbi

┣ 📁 data

┃ ┗ (HR_Analytics.csv)

┣ 📁 images

┃ ┗ HR Analytics.png

┣ 📄 HR Analytics Dashboard.pbix

┣ 📄 README.md



---

## ▶️ How to Use

1. **Clone the repository:**
   ```bash
   git clone https://https://github.com/pritithokal02-netizen/Power-BI-HR-Analytics-Dashboard
Open Power BI Desktop

Load the dataset from the data

Open HR‑Analytics‑Dashboard.pbix

Interact with the visuals, slicers, and filters to explore insights.

🧠 DAX Measures (Examples)

Total Employees = DISTINCTCOUNT(EmployeeData[EmployeeID])

Attrition Count =
CALCULATE(
    COUNTROWS(EmployeeData),
    EmployeeData[Attrition] = "Yes"
)

Attrition Rate % =
DIVIDE(
    [Attrition Count],
    [Total Employees],
    0
)
Add your own measures specific to your dataset.

🧰 Tools Used
Microsoft Power BI Desktop

Power Query for data transformation

DAX for custom calculations

Interactive visuals (bar, donut, line, matrix)

--- 
## 📥 Download

You can download the Power BI report file here:

👉 [HR Analytics Dashboard PBIX File](https://github.com/pritithokal02-netizen/Power-BI-HR-Analytics-Dashboard)

---

🚀 Future Improvements

✔️ Publish to Power BI Service

✔️ Add auto refresh capabilities

✔️ Integrate with live HR data source

✔️ Add more demographic analysis

---

🙌 Contributions

Contributions are welcome!

Create issues or pull requests to improve this project.









