<div align="center">

# 📊 Tamil Nadu Population Dashboard

### Interactive Power BI Dashboard — 2021 Census Data Analysis

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Dataset](https://img.shields.io/badge/Dataset-Census%202021-4CAF50?style=for-the-badge)](#-dataset-information)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#-license)
[![Author](https://img.shields.io/badge/Author-Methila%20M-purple?style=for-the-badge)](#-author)
[![Districts](https://img.shields.io/badge/Districts-38-orange?style=for-the-badge)](#-dataset-information)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)](#-dashboard-preview)

---

An end-to-end data analytics project visualizing **population distribution, literacy rates, sex ratio, urban-rural divide,** and **regional demographics** across all **38 districts** of Tamil Nadu using Microsoft Power BI.

[🚀 Getting Started](#-getting-started) · [📸 Dashboard Output](#-dashboard-output) · [📊 Key Insights](#-key-insights) · [📁 Repository Structure](#-repository-structure)

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Dashboard Output](#-dashboard-output)
- [Visualizations Included](#-visualizations-included)
- [Key Insights](#-key-insights)
- [Dataset Information](#-dataset-information)
- [Tools & Technologies](#-tools--technologies)
- [Getting Started](#-getting-started)
- [Repository Structure](#-repository-structure)
- [Data Dictionary](#-data-dictionary)
- [Methodology](#-methodology)
- [Author](#-author)
- [License](#-license)
- [Feedback](#-feedback)

---

## 📌 Project Overview

This project presents a **comprehensive interactive dashboard** built with Microsoft Power BI to analyze the demographic landscape of Tamil Nadu based on the **2021 Census data**. The dashboard enables stakeholders to explore population patterns, literacy trends, and urbanization metrics across all 38 districts through intuitive, interactive visualizations.

### Objectives

- Analyze **district-wise population distribution** across Tamil Nadu
- Identify **literacy rate disparities** between urban and rural regions
- Visualize the **urban-rural population split** at state and district levels
- Enable **regional filtering** for comparative analysis (North, South, East, West, Central)
- Provide **geographic context** through interactive map visualizations

---

## ✨ Key Features

| Feature | Description |
|:--------|:------------|
| 🔍 **Interactive Filtering** | Region-based slicers allow dynamic filtering across North, South, East, West, and Central Tamil Nadu |
| 📊 **KPI Cards** | At-a-glance metrics for total population, average literacy, and urbanization percentage |
| 🗺️ **Geographic Mapping** | Interactive map visualizations showing population density across districts |
| 📈 **Trend Analysis** | Area charts displaying population distribution trends |
| 🍩 **Composition Charts** | Donut charts for urban vs. rural population split |
| 🌳 **Treemap View** | Hierarchical view of district-wise population comparison |
| 📊 **Comparative Bar Charts** | Side-by-side comparison of top districts by literacy and population |
| 🎯 **Bilingual Data** | District names in both English and Tamil for accessibility |

---

## 📸 Dashboard Output

### Full Dashboard View

<div align="center">
  <img src="dashboard-output.png" alt="Tamil Nadu Population Dashboard - Full View" width="90%">
  <br>
  <em><b>Power BI Dashboard</b> — Population, Literacy, Urban-Rural Analysis Across 38 Districts</em>
</div>

<br>

### 🎬 Video Output

<div align="center">
  <a href="Video%20of%20an%20output.mp4">
    <img src="https://img.shields.io/badge/▶_Watch-Dashboard_Walkthrough-blue?style=for-the-badge&logo=github" alt="Watch Dashboard Video">
  </a>
  <br>
  <em>Click above to watch the full interactive dashboard walkthrough</em>
</div>

<br>

### 📊 Output Summary

| Output Component | Description | Status |
|:-----------------|:------------|:------:|
| 🖼️ **Dashboard Screenshot** | Full dashboard overview with all visualizations | ✅ Included |
| 🎬 **Video Walkthrough** | Interactive demo showing filters, tooltips, and drill-throughs | ✅ Included |
| 📄 **Dataset** | Raw CSV with 38 districts and 11 metrics | ✅ Included |
| 📊 **Power BI File** | Editable `.pbix` with all data models and DAX measures | ✅ Included |

### 🔍 What the Dashboard Shows

```
┌─────────────────────────────────────────────────────────────────┐
│                    DASHBOARD OUTPUT BREAKDOWN                    │
├─────────────────┬─────────────────┬─────────────────────────────┤
│  KPI Cards      │  Treemap        │  Region Slicer              │
│  • Total Pop.   │  • District     │  • North / South / East     │
│  • Avg Literacy │    comparison   │  • West / Central           │
│  • Urban %      │  • Proportional │  • Dynamic filtering        │
├─────────────────┼─────────────────┼─────────────────────────────┤
│  Bar Charts     │  Donut Chart    │  Interactive Map            │
│  • Top districts│  • Urban 30.14% │  • Geographic density       │
│    by literacy  │  • Rural 69.86% │  • District boundaries      │
│  • Top districts│  • Split view   │  • Population heatmap       │
│    by population│                 │                             │
├─────────────────┴─────────────────┴─────────────────────────────┤
│  Area Chart: Population Distribution Trend Across Districts     │
│  Data Table: Bilingual District Names (English + Tamil)         │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📈 Visualizations Included

| # | Visualization | Purpose | Insights |
|---|:--------------|:--------|:---------|
| 1 | **KPI Card** | Displays total population metric | Quick overview of filtered population |
| 2 | **Treemap** | District-wise population comparison | Proportional view of population distribution |
| 3 | **Bar Charts** | Top districts by literacy rate & population | Highlights leading and lagging districts |
| 4 | **Area Chart** | Population distribution trend | Shows density patterns across districts |
| 5 | **Donut Chart** | Urban vs. Rural percentage split | 30.14% urban vs. 69.86% rural breakdown |
| 6 | **Interactive Map** | Geographic representation | Spatial visualization of population density |
| 7 | **Region Slicer** | Filter by geographic region | Dynamic filtering for regional comparisons |
| 8 | **Data Table** | Detailed district-level metrics | Raw data view with bilingual district names |

---

## 💡 Key Insights

### Population Analysis
- **Total Population**: **79,802,111** (79.8 Million) across all 38 districts
- **Most Populated District**: **Chennai** — 4,646,732 (11.4% of state population)
- **Least Populated District**: **Perambalur** — 565,223
- **Average District Population**: ~2,100,000

### Literacy Metrics
- **State Average Literacy Rate**: **80.09%**
- **Highest Literacy**: **Kanniyakumari** — 91.75%
- **Lowest Literacy**: **Dharmapuri** — 68.54%
- **Literacy Gap**: 23.21 percentage points between highest and lowest

### Urban-Rural Distribution
| Category | Percentage | Trend |
|:---------|:-----------|:------|
| 🏙️ Urban | **30.14%** | Concentrated in Chennai, Coimbatore, Tiruppur |
| 🌾 Rural | **69.86%** | Dominant in Northern and Central districts |

### Regional Highlights

| Region | Key Districts | Notable Pattern |
|:-------|:-------------|:----------------|
| **North** | Chennai, Tiruvallur, Kancheepuram | Highest urbanization & population density |
| **South** | Madurai, Tirunelveli, Thoothukudi | Balanced urban-rural distribution |
| **East** | Thanjavur, Cuddalore, Nagapattinam | Agricultural heartland, moderate literacy |
| **West** | Coimbatore, Erode, Nilgiris | Industrial hub with high urbanization |
| **Central** | Salem, Tiruchirappalli, Namakkal | Mixed economy with growing urbanization |

### Sex Ratio Analysis
- **Highest Sex Ratio**: **Kanniyakumari** — 1037 females per 1000 males
- **Lowest Sex Ratio**: **Krishnagiri** — 968 females per 1000 males
- **State Average**: ~988 females per 1000 males

---

## 📊 Dataset Information

### Source
- **Primary**: Census of India 2021 / Census of India 2011
- **Secondary**: Tamil Nadu Government Official Records

### Coverage
- **Geographic Scope**: All 38 districts of Tamil Nadu
- **Total Records**: 38 district-level entries
- **Data Format**: CSV (`TN_Districts_Data.csv`)

### Metrics Included

| Metric | Description | Unit |
|:-------|:------------|:-----|
| `Population` | Total population of the district | Count |
| `Male_Population` | Male population | Count |
| `Female_Population` | Female population | Count |
| `Literacy_Rate` | Literacy percentage | % |
| `Sex_Ratio` | Females per 1000 males | Ratio |
| `Area_SqKm` | Geographic area | Sq. Km |
| `Density` | Population density | Per Sq. Km |
| `Urban_Percent` | Urban population share | % |
| `Rural_Percent` | Rural population share | % |
| `Region` | Geographic region classification | Category |
| `District_Tamil` | Tamil name of the district | Text |

---

## 🛠️ Tools & Technologies

| Tool | Purpose | Version |
|:-----|:--------|:--------|
| [Microsoft Power BI Desktop](https://powerbi.microsoft.com/) | Dashboard creation & visualization | Latest |
| [Power Query](https://docs.microsoft.com/en-us/power-query/) | Data transformation & cleaning | Built-in |
| [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) | Raw dataset storage | — |
| [DAX](https://docs.microsoft.com/en-us/dax/) | Calculated measures & KPIs | Built-in |

### Skills Demonstrated
- ✅ Data Modeling & Relationship Design
- ✅ DAX Calculated Measures
- ✅ Power Query ETL (Extract, Transform, Load)
- ✅ Interactive Dashboard Design
- ✅ Data Storytelling & Visualization
- ✅ Geographic & Spatial Analytics
- ✅ Bilingual Data Handling (English + Tamil)

---

## 🚀 Getting Started

### Prerequisites
1. **Microsoft Power BI Desktop** — [Free Download](https://powerbi.microsoft.com/desktop/)
   - Windows 10 or later required
   - Minimum 4 GB RAM recommended

### Installation & Usage

```bash
# 1. Clone the repository
git clone https://github.com/methila-2056/Tamil-Nadu-Dashboard-By-PowerBI.git

# 2. Navigate to the project directory
cd Tamil-Nadu-Dashboard-By-PowerBI

# 3. Open the Power BI file
# Double-click "population project pbi1.pbix" to open in Power BI Desktop
```

### Step-by-Step Guide

1. **Download** the `.pbix` file from this repository
2. **Open** Power BI Desktop (free download from Microsoft)
3. **Import** the `.pbix` file — all data and visuals are pre-loaded
4. **Explore** the dashboard using interactive filters:
   - Use the **Region Slicer** to filter by North/South/East/West/Central
   - Hover over **chart elements** for detailed tooltips
   - Click on **district segments** to cross-filter all visuals
5. **Modify** data or visuals as needed for your analysis

### Customization
- Edit `TN_Districts_Data.csv` to update or extend the dataset
- Refresh the data connection in Power BI after modifying the CSV
- Modify DAX measures in the Modeling tab for custom calculations

---

## 📁 Repository Structure

```
Tamil-Nadu-Dashboard-By-PowerBI/
│
├── 📊 population mini project by powerbi.pbix  # Main Power BI dashboard file
├── 📄 TN_Districts_Data.csv                     # Raw dataset (38 districts, 11 metrics)
├── 🖼️ dashboard-output.png                       # Dashboard screenshot/output image
├── 🎬 Video of an output.mp4                    # Dashboard walkthrough video (44 MB)
├── 📄 .gitignore                                # Git ignore rules
├── 📄 LICENSE                                   # MIT License
├── 📄 CONTRIBUTING.md                           # Contribution guidelines
└── 📄 README.md                                 # Project documentation
```

---

## 📖 Data Dictionary

### District Classifications

| Region | Districts | Characteristics |
|:-------|:----------|:----------------|
| **North** | Chennai, Chengalpattu, Kancheepuram, Tiruvallur, Vellore, Ranipet, Tiruvannamalai, Krishnagiri, Dharmapuri, Kallakurichi, Tirupathur | High urbanization, IT & industrial hubs |
| **South** | Madurai, Tirunelveli, Thoothukudi, Dindigul, Ramanathapuram, Sivagangai, Tenkasi, Theni, Virudhunagar, Kanniyakumari | Mixed economy, coastal districts |
| **East** | Thanjavur, Cuddalore, Nagapattinam, Tiruvarur, Mayiladuthurai, Viluppuram | Agricultural belt, temple towns |
| **West** | Coimbatore, Erode, Nilgiris, Tiruppur | Industrial corridor, textile hubs |
| **Central** | Salem, Tiruchirappalli, Namakkal, Karur, Perambalur, Pudukkottai, Ariyalur | Administrative centers, limestone belt |

---

## 🔬 Methodology

### Data Pipeline

```
┌─────────────┐    ┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│  Raw Data    │───▶│ Power Query  │───▶│ Data Model   │───▶│ Dashboard    │
│  (CSV)       │    │  (ETL)       │    │  (DAX)       │    │  (Visuals)   │
└─────────────┘    └──────────────┘    └──────────────┘    └──────────────┘
```

1. **Data Collection**: Compiled from Census of India and TN Government sources
2. **Data Cleaning**: Standardized district names, validated numeric fields
3. **Data Transformation**: Calculated derived metrics (Urban%, Rural%, density ratios)
4. **Data Modeling**: Established relationships between district attributes
5. **Visualization**: Created interactive charts, maps, and KPI cards
6. **Validation**: Cross-referenced figures with official government publications

---

## 👤 Author

### **Methila M**

> Data Analytics Portfolio Project — Demonstrating Power BI skills in data visualization, dashboard design, and demographic analysis.

- 🔗 **GitHub**: [methila-2056](https://github.com/methila-2056)
- 📊 **Project**: Tamil Nadu Population Dashboard

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE) for educational and portfolio purposes.

---

## 🤝 Feedback

Suggestions, feedback, and contributions are welcome!

- 🐛 **Found a bug?** — [Open an issue](https://github.com/methila-2056/Tamil-Nadu-Dashboard-By-PowerBI/issues)
- 💡 **Have suggestions?** — [Start a discussion](https://github.com/methila-2056/Tamil-Nadu-Dashboard-By-PowerBI/discussions)
- ⭐ **Like this project?** — Give it a star!

---

<div align="center">

**Made with ❤️ for Data Analytics**

*Data Source: Census of India & Tamil Nadu Government Official Records*

</div>
