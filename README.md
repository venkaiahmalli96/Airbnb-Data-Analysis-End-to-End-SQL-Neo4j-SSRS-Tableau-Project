# Airbnb Data Analysis – End-to-End SQL, Neo4j, SSRS & Tableau Project
  This project was completed as part of the “Data Storage Solutions for Data Analytics” module at Dublin Business School (Lecturer: Dr Anesu Nyabadza)
   Developed by Venkaiah Malli.

## 📌 Project Overview 
This project showcases my skills as a **Data Analyst** by delivering a complete **end-to-end data analysis workflow** using an Airbnb dataset.  
It combines **data modeling, advanced querying, reporting, and dashboard visualization** across multiple platforms: **SQL, Neo4j, SSRS, and Tableau**.  
The goal was to transform raw Airbnb data into actionable business insights through clean design, accurate analysis, and professional reporting.

---

## 📌 Project Objectives
1. **Data Modeling & Storage**
   - Create relational (SQL) and graph (Neo4j) database models.
2. **Data Cleaning & Transformation**
   - Perform ETL from CSV into both SQL and Neo4j.
3. **Data Analysis**
   - Write advanced SQL and Cypher queries to answer business questions and track KPIs.
4. **Business Intelligence**
   - Build SSRS reports and Tableau dashboards for stakeholders.
5. **Documentation**
   - Deliver full technical and business documentation.
---
## 🛠 Tech Stack
- **Relational Database**: MySQL / Oracle (SQL DDL, DML)
- **Graph Database**: Neo4j (Cypher queries)
- **Reporting**: SQL Server Reporting Services (SSRS)
- **Data Visualization**: Tableau (TWBX)
- **Data Source**: Airbnb dataset (CSV)

---
## 📂 Repository Structure

```plaintext
airbnb-data-analysis-end-to-end
│
├── data/                          # Raw Airbnb dataset (CSV)
│   └── airbnb_data.csv
│
├── sql/                           # SQL scripts (DDL, DML, analysis queries)
│   ├── table_creation_and_insert.sql
│   └── seven_analysis_queries.sql
│
├── neo4j/                         # Graph database (Neo4j Cypher queries)
│   └── seven_analysis_queries.cql
│
├── ssrs/                          # SSRS project files and report outputs
│   ├── AIRBNB.ssmssqlproj
│   ├── SSRS_Reports_Code.txt
│   └── outputs/
│       ├── Hosts_Q1_output.csv
│       ├── Revenue_Q2_Output.csv
│       ├── Location_Q3_Output.csv
│       └── Availability_Q4_output.csv
│
├── tableau/                       # Tableau packaged dashboard
│   └── Airbnb_Tableau_Report_Dashboard.twbx
│
├── docs/                          # Reports and presentations
│   ├── Airbnb_project_VenkaiahMalli.pdf
│
│
├── README.md                      # Project overview (this file)
└── LICENSE                        # License file
```
----



---

## 📊 Key Deliverables

### **1. SQL Data Analysis**
- Designed normalized relational schema.
- Loaded Airbnb data into SQL tables.
- Analytical queries include:
  - Top-performing hosts
  - Revenue analysis by city
  - Occupancy and availability patterns
  - Review trends
- 📄 Files:  
  - `sql/table_creation_and_insert.sql`  
  - `sql/seven_analysis_queries.sql`

### **2. Neo4j Graph Analytics**
- Modeled hosts, listings, locations, and reviews as nodes.
- Created relationships: `OWNS`, `LOCATED_IN`, `HAS_REVIEW`.
- Cypher queries for:
  - Shortest path analysis
  - Relationship-based recommendations
  - Location connectivity
- 📄 File: `neo4j/seven_analysis_queries.cql`

### **3. SSRS Reporting**
- Parameterized reports to filter by host, location, and time.
- Outputs: Revenue, occupancy, availability KPIs.
- 📄 Files:
  - `ssrs/AIRBNB.ssmssqlproj`
  - `ssrs/outputs/*.csv`

### **4. Tableau Dashboard**
- Interactive dashboard with:
  - KPI cards
  - Revenue & occupancy trends
  - Geographic map of listings
- 📄 File: `tableau/Airbnb_Tableau_Report_Dashboard.twbx`

### **5. Documentation**
- `docs/Airbnb_Project_Venkaiahmalli.pdf` – Technical design & methodology complete report

---

## 🚀 How to Run

### **Relational SQL**
1. Create a database in MySQL/Oracle.
2. Run `sql/table_creation_and_insert.sql` to create tables & insert data.
3. Execute `sql/seven_analysis_queries.sql` to analyze KPIs.

### **Neo4j**
1. Launch Neo4j Desktop or Aura.
2. Load `data/airbnb_data.csv` into the database.
3. Run `neo4j/seven_analysis_queries.cql`.

### **SSRS**
1. Open `ssrs/AIRBNB.ssmssqlproj` in Visual Studio with SSRS extensions.
2. Connect to your SQL database.
3. Preview/export reports.

### **Tableau**
1. Open `tableau/Airbnb_Tableau_Report_Dashboard.twbx` in Tableau Desktop.
2. Link to `data/airbnb_data.csv` if required.

---

## 🎯 Skills Demonstrated
- **Data Modeling** (Relational & Graph)
- **ETL & Data Cleaning**
- **Analytical Querying** (SQL & Cypher)
- **Business Intelligence Reporting** (SSRS)
- **Dashboard Design** (Tableau)
- **KPI Tracking & Business Insights**
- **Stakeholder Communication** (presentations & documentation)

---

## 👤 Author
**Venkaiah Malli**  
- [LinkedIn](https://linkedin.com/in/venkaiah-malli-98aa47219)  
- [GitHub](https://github.com/venkaiahmalli96)  

