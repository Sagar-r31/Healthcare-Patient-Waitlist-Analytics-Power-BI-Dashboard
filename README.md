**Healthcare Patient Waitlist Analytics – Power BI Dashboard**

This project presents a complete Power BI analytics solution to analyze hospital waitlists across specialties, case types, age groups, and time bands. The dashboard includes full data transformation, modeling, visualization, and interactivity to support healthcare decision-making.

---

**📌 Project Overview**

This project combines multiple raw healthcare waitlist datasets into a single, unified analytical model and an interactive Power BI dashboard.  
Key insights include:

- Monthly waitlist KPIs  
- Case-Type split across Inpatient, Day Case, and Outpatient  
- Age Profile vs Time Band analysis  
- Specialty-wise patient volume ranking  
- Multi-month trend analysis  
- Drill-through for detailed specialty-level data  

---

**📸 Dashboard Preview**

<img width="1319" height="740" alt="Summary" src="https://github.com/user-attachments/assets/8bb5a8e9-885e-48a6-bb2d-992cdc0ac45b" />

<img width="1315" height="735" alt="Detailed View" src="https://github.com/user-attachments/assets/5fb9bdb1-cb7f-4545-a24f-589c2372b982" />

**🛠️ Project Development Process**

**1. Requirement Gathering**  
Defined KPIs, visuals, slices, navigation flow, and interactions required for the dashboard.

**2. Data Collection**  
Imported raw inpatient, outpatient, and specialty mapping datasets.

**3. Data Transformation**  
Performed using Power Query:
- Cleaned raw files  
- Standardized values  
- Combined all datasets into one unified dataset  
- Added calculated columns for better analysis  

**4. Data Modeling**  
- Created a star-schema data model  
- Added a Date dimension table  
- Linked fact and dimension tables  
- Prepared the model for drill-through and slicer interactions  

**5. Theme & Layout Design**  
All theme backgrounds and UI elements were created in PowerPoint and imported into Power BI for a customized professional look.

**6. Visualization Development**  
Dashboard visuals include:
- KPI cards  
- Donut charts  
- Stacked bars  
- Line charts for monthly trends  
- Top specialties ranking  
- Detailed drill-through matrix  

**7. Interactivity & Navigation**  
- Sync slicers for consistent filtering  
- Buttons for Summary and Detailed View  
- Drill-through for deeper specialty insights  
- Hover effects for user-friendly interactions  

**8. Testing & Validation**  
Ensured correct totals, filtering behavior, trend accuracy, and formatting consistency after dataset combination.

---

**📊 Dashboard Pages**

**🔹 Summary Page**  
Includes:
- Latest month KPIs  
- Case Type Split  
- Age Profile vs Time Band  
- Top 5 Specialties  
- Monthly trend lines for each Case Type  

**🔹 Detailed View Page**  
Includes:
- Specialty → Age Profile → Time Band hierarchy  
- Case-type patient counts  
- Total waitlist summary  
- Filter panel for custom exploration  

---

**📂 Repository Structure**

Healthcare-Patient-Waitlist-Analytics/  
│  
├── Healthcare_data/  
├── Screenshots/  
│   ├── Summary.png  
│   ├── DetailedView.png  
│   └── Hover.png  
│  
├── pbix/  
│   └── Dashboard.pbix  
│  
└── README.md  

---

**📥 How to Run**

1. Clone or download the repository.  
2. Open `Dashboard.pbix` in Power BI Desktop.  
3. Use slicers to filter by Date, Case Type, Specialty, Age Profile, and Time Bands.  
4. Navigate between pages using the dashboard buttons.

---

**💡 Skills Demonstrated**

- Power Query transformations  
- Data cleaning & merging  
- Power BI data modeling  
- DAX calculations  
- Custom theme creation in PowerPoint  
- KPI and trend analysis  
- Healthcare operational reporting  

---

**📌 Notes**

This project uses sample/anonymized healthcare waitlist data for learning and demonstration purposes.
