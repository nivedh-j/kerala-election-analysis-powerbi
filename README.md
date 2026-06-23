# 👆 Kerala Election Analytics Dashboard

> A comprehensive Power BI dashboard built to analyze Kerala Election results through district-level drill-downs, alliance-wise vote share analysis, constituency performance tracking, and election reporting. The project transforms raw election data into actionable insights using Power BI, DAX, and interactive visualizations.

---

# 📌 Business Problem

Election data contains large volumes of information across districts, constituencies, parties, alliances, and candidates.

Decision-makers, analysts, journalists, and researchers require a centralized reporting system to:

* Track vote distribution across districts
* Compare alliance performance
* Analyze constituency-level results
* Identify winning candidates and parties
* Understand regional voting behavior

The objective of this project is to build an interactive election intelligence dashboard that enables users to explore election results efficiently and uncover meaningful voting patterns.

---

# 📂 Dataset Information

### Dataset Overview

| Attribute         | Details                             |
| ----------------- | ----------------------------------- |
| Domain            | Election Analytics                  |
| State             | Kerala                              |
| Districts         | 14                                  |
| Constituencies    | 140                                 |
| Political Parties | 42                                  |
| Analysis Type     | Descriptive & Comparative Analytics |
| Tool              | Power BI                            |

---

### Dataset Features

| Feature           | Description                |
| ----------------- | -------------------------- |
| District          | District Name              |
| Constituency      | Constituency Name          |
| Candidate         | Candidate Name             |
| Party             | Political Party            |
| Alliance          | UDF / LDF / NDA / Other    |
| EVM Votes         | Votes recorded through EVM |
| Postal Votes      | Postal Ballot Votes        |
| Total Votes       | Total Votes Received       |
| Winning Candidate | Election Winner            |

---

# 🔍 Data Preparation

### Data Cleaning

* Missing value verification
* Data type correction
* Duplicate record validation
* Category standardization

### Data Modeling

* Relationship creation
* Hierarchical filtering
* Interactive drill-down design

### DAX Measures

Custom measures were created for:

* Total Votes
* Postal Votes
* Total Constituencies
* Total Parties
* Alliance Vote Share
* Vote Percentage Calculations

---

# 📊 Dashboard Features

### Kerala Election Overview

Provides a state-wide summary including:

✔ Total Votes

✔ Total Postal Votes

✔ Total Constituencies

✔ Total Districts

✔ Party-wise Vote Distribution

✔ District-wise Vote Analysis

---

### District-Level Analysis

Dedicated dashboards for:

* Palakkad
* Ernakulam
* Thiruvananthapuram

Each dashboard includes:

✔ Constituency Vote Distribution

✔ Alliance Performance

✔ Winning Party Analysis

✔ District-Level KPIs

---

### Alliance Analysis

The dashboard compares:

* UDF
* LDF
* NDA
* Other Parties

through:

✔ Vote Share Analysis

✔ Alliance Performance Comparison

✔ Party Contribution Analysis

✔ District-Level Alliance Distribution

---

# 📈 Key Insights

### 1. UDF Secured the Highest Vote Share

Alliance-level analysis shows UDF emerged as the leading alliance across Kerala with the highest overall vote count.

---

### 2. LDF Remained the Strongest Competitor

LDF consistently maintained a strong voter base and remained the primary challenger across major districts.

---

### 3. Regional Voting Patterns Vary

District-level analysis revealed significant differences in voting behavior across Kerala.

Some districts showed strong UDF dominance while others remained highly competitive.

---

### 4. Postal Voting Had Limited Impact

Postal votes represented only a small percentage of total votes compared with EVM votes.

Most election outcomes were driven by direct voter participation through EVM voting.

---

### 5. Constituency-Level Competition Was Intense

Several constituencies recorded closely contested results, highlighting the competitive nature of Kerala elections.

---

# 📊 Dashboard Pages

### Page 1 — Kerala Election Overview

* State-Level Performance
* Party Vote Distribution
* District Vote Analysis

### Page 2 — Palakkad Election Report

* Constituency Analysis
* Alliance Vote Distribution
* Winning Party Summary

### Page 3 — Ernakulam Election Report

* Constituency Performance
* Vote Distribution
* District KPIs

### Page 4 — Thiruvananthapuram Election Report

* Alliance Comparison
* Constituency Insights
* Candidate Analysis

### Page 5 — Alliance Analysis Dashboard

* Alliance Vote Share
* Comparative Performance
* Regional Analysis

### Page 6 — Party Contribution Dashboard

* Party Contribution within Alliances
* Vote Share Breakdown
* Treemap Analysis

---

# ⚙️ Technologies Used

### Business Intelligence

* Power BI Desktop
* Power Query
* DAX

### Data Analysis

* Data Modeling
* Interactive Reporting
* Dashboard Design

---

# 🎯 Skills Demonstrated

✔ Data Cleaning

✔ Data Modeling

✔ DAX Calculations

✔ Election Data Analytics

✔ Dashboard Development

✔ KPI Design

✔ Interactive Reporting

✔ Drill-Down Analysis

✔ Data Visualization

✔ Business Intelligence

---

# 📈 Business Value

This dashboard helps stakeholders:

* Monitor election performance
* Compare alliance strength
* Analyze constituency-level results
* Identify regional voting trends
* Improve election reporting efficiency

---

# 🗂 Repository Structure

```text
kerala-election-powerbi-dashboard/
│
├── Kerala_Election_Dashboard.pbix
├── README.md
│
├── Images/
│   ├── kerala_overview.png
│   ├── palakkad_report.png
│   ├── ernakulam_report.png
│   ├── trivandrum_report.png
│   ├── alliance_analysis.png
│   └── party_contribution.png
│
└── Dataset/
    └── election_data.csv
```

---

# 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/nivedh-j/kerala-election-powerbi-dashboard.git
```

### Open Dashboard

```text
Open Kerala_Election_Dashboard.pbix in Power BI Desktop
```

---

# 🔮 Future Improvements

* [ ] Kerala Shape Map Visualization
* [ ] Margin of Victory Analysis
* [ ] Voter Turnout Analysis
* [ ] District Ranking Dashboard
* [ ] Advanced DAX KPIs
* [ ] Drill-Through Pages
* [ ] Tooltip Pages
* [ ] Automated Data Refresh

---

# 👤 Author

**Nivedh J**

Data Analyst | Power BI | SQL | Python

GitHub: https://github.com/nivedh-j

LinkedIn: https://www.linkedin.com/in/nivedhj/

Portfolio: https://nivedh-j.github.io

---

# 📄 License

This project is licensed under the GNU License.
