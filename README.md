# 🗳️ 2024 India General Election Analytics Dashboard

An advanced, interactive Power BI dashboard that analyzes the 2024 Indian General Election across all 543 parliamentary constituencies. The project provides detailed insights into alliance performance, party-wise seat distribution, constituency-level results, and regional voting patterns through interactive dashboards and geospatial visualizations.

---

# 📌 Project Overview

The objective of this project is to transform raw election datasets into an interactive business intelligence solution that enables users to analyze election outcomes at both national and constituency levels. The dashboard allows users to explore party performance, alliance dominance, vote share distribution, and regional trends using dynamic filters and drill-down analysis.

---

# 📂 Dataset

**Source:** Election Commission of India (ECI)

**Coverage**
- 543 Parliamentary Constituencies
- State-wise Election Results
- Candidate Details
- Political Parties
- Alliance Information (NDA / I.N.D.I.A. / Others)
- EVM Votes
- Postal Votes
- Winning Margins

The datasets were cleaned, transformed, and modeled using Power Query before building the analytical dashboards in Power BI.

---

# 📊 Business Questions Answered

This dashboard helps answer questions such as:

- Which alliance secured the highest number of seats?
- Which political party performed best nationally?
- Which constituencies had the closest contests?
- How does vote share vary across states?
- Which candidates won with the highest margins?
- How do EVM votes compare with Postal votes?
- Which states contributed the highest number of seats to each alliance?

---

# 🚀 Key Features

- Multi-page interactive Power BI dashboard
- Advanced DAX calculations
- Power Query based ETL
- Interactive maps
- Dynamic filtering and drill-through
- Constituency search
- Coalition analysis
- Party-wise performance analysis
- Geographic visualization

---

# 📸 Dashboard Walkthrough

## 1. Interactive Navigation Portal

A centralized landing page that allows users to navigate between dashboard modules using interactive bookmarks.

![Navigation Hub](screenshots/navigation_hub.png)

---

## 2. National Overview

Displays alliance-wise seats, vote share, and party performance across India.

![National Overview](screenshots/national_overview.png)

---

## 3. State-wise & Geographic Analysis

Interactive maps highlighting regional voting patterns and alliance performance.

![Geospatial Mapping](screenshots/state_demographics.png)

---

## 4. Constituency Analysis

Provides detailed analysis of individual constituencies, candidate performance, vote distribution, and winning margins.

![Constituency Analysis](screenshots/constituency_analysis.png)

---

# 💡 Key Insights

- NDA emerged as the largest alliance based on total parliamentary seats.
- Regional voting patterns varied significantly across different states.
- Several constituencies recorded very narrow victory margins.
- EVM votes constituted the majority of votes across all constituencies.
- Interactive drill-through allows constituency-level analysis for all 543 seats.

---

# 🛠️ Tech Stack

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- ETL
- Interactive Maps
- Dashboard Design

---

# 📂 Repository Structure

```
India-General-Election-Analytics-2024/
│
├── India_Election_2024.pbix
├── README.md
├── screenshots/
└── dataset/
```

---

# ▶️ How to Run

1. Clone or download this repository.
2. Open `India_Election_2024.pbix` using Microsoft Power BI Desktop.
3. Interact with the filters, slicers, and drill-through pages.

---

# 🚀 Future Enhancements

- Live election data integration
- Historical election comparison
- Predictive analytics
- Automated data refresh
- Additional KPI dashboards
