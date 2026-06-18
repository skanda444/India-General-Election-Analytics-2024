# 2024 India General Election Analytics Dashboard

An advanced, interactive multi-page Power BI solution tracking macroeconomic political trends, coalition structures, and voter behaviors across all 543 parliamentary constituencies for the 2024 Lok Sabha elections.

## 🚀 Key Insights & Architecture
* **Data Scale:** Reconciled granular, multi-tier electoral datasets down to 543 unique constituency data points.
* **Complex Data Modeling:** Built relational mapping structures linking localized independent political entities up to their overarching national alliances (NDA vs. I.N.D.I.A.).
* **Advanced DAX Metrics:** Engineered custom measures isolating absolute victory margins, relative vote share percentages, and ranking matrices evaluating the performance of Winners, 1st Runners-up, and 2nd Runners-up.
* **Geospatial Analysis:** Utilized custom interactive shape maps and point coordinates to track regional political strongholds and macro voting shifts across the subcontinent.

---

## 📸 Dashboard Walkthrough

### 1. Interactive Navigation Portal
A centralized, theme-optimized landing console allowing users to seamlessly transition between specific diagnostic modules via native canvas button bookmarks.
![Navigation Hub](screenshots/navigation_hub.jpg)

### 2. National Overview & Coalition Alliance Splits
Tracks macro-level coalition numbers, seat shares, and individual party-wise breakdowns under parent alliances.
![National Overview](screenshots/national_overview.jpg)

### 3. Regional Demographics & Geospatial Analysis
Leverages filled maps and cluster point scatter indicators to display localized victory metrics across state borders.
![Geospatial Mapping](screenshots/state_demographics.jpg)

### 4. Granular Constituency Search Interface
A dedicated lookup feature providing real-time voter pool distributions, candidate rankings, and localized metrics for a selected constituency.
![Constituency Deep Dive](screenshots/constituency_analysis.png)

---

## 🛠️ Tech Stack & Skills Utilized
* **BI Tool:** Microsoft Power BI Desktop
* **Data Transformation:** Power Query Engine (ETL Processing)
* **Analytical Calculations:** Data Analysis Expressions (Advanced DAX)
* **Visualization Modalities:** Geographic Choropleths, Donut Formats, Matrix Tables, In-line Visual Data Bars

---

## 📂 How to View the Project
1. Download the `India_Election_2024.pbix` file from this repository.
2. Open it locally using **Power BI Desktop** to interact fully with the slicers, maps, and drill-through targets.
