# 🎓 Student Performance Dashboard (Power BI)

This project presents a fully interactive Power BI dashboard built on a dataset that tracks students' academic performance. The analysis dives into how **demographic and educational factors** impact scores in Math, Reading, and Writing.

---

## 🎯 Objectives

- Explore the influence of **gender**, **parental education**, **lunch type**, and **test preparation** on students’ academic performance.
- Build a clear and interactive **Power BI dashboard** to visualize key patterns.
- Derive actionable **insights** to better understand the education landscape.

---

## 🔍 Dataset Overview

- **Source**: [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Records**: 1000 students
- **Attributes**: Gender, Race/ethnicity, Parental education, Lunch, Test preparation, and scores in Math, Reading, and Writing.

---

## ⚙️ Steps Performed

1. **Data Cleaning & Preprocessing**
   - Removed unnecessary spaces and renamed columns for clarity.
   - Standardized column names using lowercase and underscore conventions.

2. **Data Transformation**
   - Added calculated columns like `average_score` and categorized score levels (e.g., Low, Medium, High).
   - Converted text columns to proper case for better visual readability.

3. **Exploratory Data Analysis**
   - Visualized score distributions across gender, parental education, and other attributes.
   - Assessed correlation between test preparation and score improvements.

4. **Dashboard Development in Power BI**
   - Created slicers for gender, parental education, and lunch.
   - Built KPIs and bar/pie charts to reflect performance trends.
   - Designed a clean, intuitive layout with tooltips and titles.

---

## 📊 Dashboard Features

- **Interactive filters** for gender, parental education, lunch type.
- **Dynamic KPIs**: Average scores in Math, Reading, and Writing.
- **Visuals**:
  - Bar chart of test scores by gender and education.
  - Pie chart of performance levels.
  - Line/clustered visuals showing distribution and trends.

---

## 🔑 Key Insights

- **Test preparation** has a clear positive impact on performance.
- **Female students** excel in reading and writing; **males** slightly outperform in math.
- **Higher parental education** is associated with better scores.

---

## ✅ Conclusion

This dashboard provides a powerful view into the factors influencing student performance. By making the data interactive and visual, we can draw useful conclusions that may help educators, analysts, or policymakers make informed decisions about educational interventions and support strategies.

---

## 🚀 How to Use

1. Clone this repo or download the files.
2. Open `students-performance.pbix` in **Power BI Desktop**.
3. Explore the slicers, charts, and KPIs for insights!

---

## 📁 Project Structure

/Data
├── students-dataset.csv # Cleaned dataset
└── students-performance.pbix # Power BI dashboard

/images
└── dashboard-preview.png # Screenshot of the dashboard


---

## 📸 Dashboard Preview

![Dashboard Screenshot](assets/dashboard-preview.png)

---

## 🛠 Tools Used

- **Power BI Desktop** – for data modeling and interactive dashboard creation  
- **Power Query** – for data transformation and cleaning

---

## 👤 Author

**Iqra Izhar**  
