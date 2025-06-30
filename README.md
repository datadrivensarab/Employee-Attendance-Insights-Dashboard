# Employee Attendance & Work Preference Dashboard

This project delivers a Power BI dashboard that analyzes employee attendance patterns over the last 3 months to help HR teams make data-driven decisions on workplace preferences, engagement activities, and proactive health measures.

---

## 🎯 Project Overview

A software company's HR department provided attendance data in Excel format, spread across multiple sheets with varying column headers. The goal was to build a comprehensive dashboard to answer questions such as:

- What is each employee's working preference (Work From Home, Office, Hybrid)?
- Are employees frequently working from home on Mondays or Fridays, potentially indicating extended weekends?
- Which days have the highest on-site presence to plan team-building activities or lunches?
- What are the trends in sick leave, so HR can proactively plan precautionary measures?

---

## 🛠️ Data Preparation

**Power Query** was used to:

- Consolidate multiple Excel sheets with inconsistent headers.
- Transform and clean the data into a single, standardized table.
- Create calculated columns for attendance status (e.g., Present, WFH, Sick Leave).

---

## 📊 Metrics & Measures

Key metrics were created using **DAX**, including:

- **% Work From Home**  
  The percentage of days employees worked remotely.
- **% Sick Leave**  
  The percentage of days employees were on sick leave.
- **Presence % by Date and Day of Week**  
  To analyze trends and spot patterns in office attendance.
- **WFH % by Date and Day of Week**  
  To identify employees frequently working from home on specific weekdays.
- **SL % by Date**  
  To visualize sick leave trends over time.

---

## 🖥️ Dashboard Features

The dashboard provides:

- **Overall attendance KPIs** (Presence %, WFH %, Sick Leave %).
- **Daily trends** with line charts for each attendance type.
- **Day-of-week analysis** showing which weekdays have higher WFH or Sick Leave percentages.
- **Employee-level breakdowns** to identify individual work patterns.
- **Date filters** to select specific months or periods.

![image](https://github.com/user-attachments/assets/5022deb0-9d67-4a34-9dd9-1ef472671f3e)

---

## 🧰 Technologies Used

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Excel (data source)**

---

## 📈 Impact

This dashboard enables HR to:

- Monitor remote work adoption.
- Identify attendance trends by weekday.
- Plan engagement activities when most employees are on-site.
- Track sick leave patterns and respond proactively.

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh data to pull the latest Excel files.
3. Use filters and slicers to explore attendance metrics.
4. Export visuals or share reports as needed.

