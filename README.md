# 🦠 Global HIV/AIDS Analytics Dashboard

> An interactive **Power BI dashboard** developed to analyze the global burden of HIV/AIDS through country-level trends, mortality statistics, treatment coverage, and regional comparisons. The dashboard transforms complex public health data into actionable insights, enabling healthcare professionals, researchers, policymakers, and public health organizations to monitor disease prevalence and evaluate treatment outcomes.

---

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Dashboard Preview](#-dashboard-preview)
- [Background](#-background)
- [Project Objectives](#-project-objectives)
- [Dataset Overview](#-dataset-overview)
- [Key Performance Indicators](#-key-performance-indicators)
- [Dashboard Features](#-dashboard-features)
- [Visualizations](#-visualizations)
- [Key Insights](#-key-insights)
- [Public Health Value](#-public-health-value)
- [Data Analysis Workflow](#-data-analysis-workflow)
- [Tools & Technologies](#-tools--technologies)
- [Repository Structure](#-repository-structure)
- [How to Use](#-how-to-use)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Improvements](#-future-improvements)
- [Disclaimer](#-disclaimer)
- [Author](#-author)
- [License](#-license)

---

# 📌 Project Overview

The **Global HIV/AIDS Analytics Dashboard** is a Business Intelligence solution built using **Microsoft Power BI** to visualize and analyze global HIV/AIDS statistics. It provides a centralized platform for monitoring disease prevalence, mortality, antiretroviral therapy (ART) coverage, and regional disparities across countries.

The dashboard combines executive-level KPIs with interactive visualizations, allowing users to identify trends, compare countries and WHO regions, and gain insights into the global HIV epidemic.

Designed with a clean and informative layout, the dashboard demonstrates how data visualization can support evidence-based public health planning and decision-making.

---

# 🖼 Dashboard Preview

![HIV-Data-Visualization](HIV%20dashboard.PNG)

---

# 🌍 Background

Human Immunodeficiency Virus (HIV) remains one of the world's most significant public health challenges. Monitoring trends in infections, mortality, and treatment access is essential for evaluating progress toward global health goals and identifying areas requiring intervention.

This dashboard provides an analytical view of HIV/AIDS data, making it easier to understand disease patterns and treatment coverage across different countries and WHO regions.

---

# 🎯 Project Objectives

The dashboard aims to:

- Monitor the global burden of HIV/AIDS.
- Compare HIV prevalence across countries.
- Analyze mortality trends.
- Evaluate access to Antiretroviral Therapy (ART).
- Compare treatment coverage across WHO regions.
- Identify countries with the highest HIV burden.
- Support evidence-based public health decisions through data visualization.

---

# 📂 Dataset Overview

The dataset contains aggregated HIV/AIDS statistics, including:

- Country
- WHO Region
- Year
- Number of People Living with HIV
- Number of Deaths
- ART Coverage
- Children Receiving ART
- Mortality Rate

The data was cleaned, transformed, and modeled using **Power Query** before analysis.

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|------|-------:|
| 👥 Total People Living with HIV | **102,742,880** |
| ⚰️ Total Recorded Deaths | **2,748,730** |
| 📉 Mortality Rate | **2.67%** |
| 💊 ART Coverage Gap | **11,078,870** |

These KPIs provide a high-level overview of the global HIV/AIDS situation and treatment landscape.

---

# 🚀 Dashboard Features

- Executive KPI Cards
- Global Geographic Analysis
- Country-Level HIV Comparison
- Mortality Analysis
- WHO Regional Comparison
- ART Coverage Monitoring
- Interactive Tables
- Time-Series Trend Analysis
- Public Health Reporting
- Executive Dashboard Design

---

# 📈 Visualizations

## 🌍 Top 10 Countries with Highest HIV-Related Deaths Over Time

A multi-line chart tracks HIV-related deaths across the highest-burden countries over multiple years, enabling users to observe long-term mortality trends and compare countries.

---

## 🗺 Global Distribution of HIV Deaths

An interactive map visualizes HIV-related deaths across countries worldwide, helping identify geographical hotspots and regional disease burden.

---

## 📊 Deaths by Country

A ranked bar chart compares countries based on total HIV-related deaths, allowing quick identification of the most affected nations.

---

## 💊 ART Coverage by WHO Region

A bar chart compares the number of people receiving **Antiretroviral Therapy (ART)** across WHO regions, highlighting differences in treatment accessibility.

---

## 👶 Children Receiving ART by WHO Region

This visualization focuses specifically on pediatric HIV treatment, comparing the number of children receiving ART across different WHO regions.

---

## 🔄 ART Coverage Comparison

A donut chart compares:

- People receiving ART
- Children receiving ART

providing an overview of treatment coverage within the dataset.

---

## 👥 People Living with HIV by Country

A ranked bar chart displays countries with the highest number of people living with HIV, enabling comparison of disease prevalence across nations.

---

## 📋 Country Summary Table

An interactive table provides detailed country-level metrics including:

- Country
- Number of People Living with HIV
- Number of Deaths
- Trend of HIV Cases

This supports deeper exploration of individual country performance.

---

# 🔍 Key Insights

The dashboard provides several important public health insights:

- More than **102 million** people are represented as living with HIV within the analyzed dataset.
- Approximately **2.75 million** HIV-related deaths have been recorded.
- The overall mortality rate is **2.67%**.
- Significant disparities exist in ART coverage across WHO regions.
- African countries contribute a substantial proportion of the global HIV burden.
- Some countries demonstrate declining mortality trends, while others continue to experience persistent disease burden.
- Treatment access varies considerably across regions, emphasizing the need for equitable healthcare interventions.

---

# 🌐 Public Health Value

This dashboard supports healthcare organizations, researchers, NGOs, and policymakers by enabling them to:

- Monitor HIV prevalence.
- Track mortality trends.
- Evaluate ART program performance.
- Identify regions requiring increased healthcare investment.
- Support evidence-based policy development.
- Measure progress toward global HIV treatment goals.
- Improve public health reporting and communication.

---

# ⚙ Data Analysis Workflow

## 1. Data Collection

Collected HIV/AIDS statistics including:

- Country Information
- WHO Region
- HIV Prevalence
- HIV Deaths
- ART Coverage
- Pediatric ART Coverage
- Mortality Indicators

---

## 2. Data Cleaning

Performed using **Power Query**:

- Removed duplicate records.
- Corrected inconsistent values.
- Standardized country names.
- Handled missing values.
- Validated numerical data.

---

## 3. Data Modeling

Built relationships between tables to support dynamic filtering and efficient analysis.

---

## 4. DAX Measures

Custom calculations include:

- Mortality Rate
- ART Coverage Gap
- Total HIV Cases
- Total Deaths
- Regional Comparisons
- Trend Analysis

---

## 5. Dashboard Development

The dashboard follows Business Intelligence best practices by emphasizing:

- Clear visual hierarchy
- Consistent color palette
- Interactive reporting
- Executive-friendly design
- Effective public health storytelling

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft Excel
- Geographic Mapping
- Business Intelligence
- Public Health Analytics

---

# 📁 Repository Structure

```text
Global-HIV-AIDS-Analytics-Dashboard/
│
├── FHIV Visualization.pbix
├── HIV dashboard.PNG
├── Dataset/
│   └── fHIV.xlsx
├── README.md
└── LICENSE
```

---

# 🚀 How to Use

### Clone the Repository

```bash
git clone https://github.com/Ita-Leonard/Global-HIV-AIDS-Analytics-Dashboard.git
```

### Open the Dashboard

1. Install **Microsoft Power BI Desktop**.
2. Open the `.pbix` file.
3. Refresh the dataset if necessary.
4. Explore the interactive visuals and use filters to analyze country- and region-specific trends.

---

# 💡 Skills Demonstrated

This project demonstrates expertise in:

- Business Intelligence
- Public Health Analytics
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- KPI Development
- Geographic Analysis
- Healthcare Data Visualization
- Time-Series Analysis
- Interactive Dashboard Design
- Data Storytelling
- Executive Reporting

---

# 📈 Future Improvements

Potential enhancements include:

- Integration of real-time HIV surveillance data.
- Gender- and age-specific analysis.
- Country-level drill-through pages.
- Predictive forecasting of HIV prevalence.
- SDG (Sustainable Development Goals) progress tracking.
- Mobile-responsive dashboard optimization.
- Deployment to Power BI Service with scheduled data refresh.
- Interactive filters for year, region, and demographic groups.

---

# 📚 Disclaimer

This dashboard was developed for **educational**, **portfolio**, and **public health analytics demonstration** purposes. The statistics shown reflect the dataset used for this project and should not be interpreted as the latest official global HIV/AIDS estimates. For current figures, consult organizations such as **UNAIDS** and the **World Health Organization (WHO)**.

---

# 👨‍💻 Author

## Leonard Ayamba Ita

**Data Analyst | Power BI Developer | Medical Laboratory Scientist**

As a Medical Laboratory Science student with a passion for data analytics, I specialize in transforming complex healthcare and business datasets into interactive dashboards that support evidence-based decision-making. My work combines Business Intelligence, healthcare analytics, and data storytelling to communicate insights that create real-world impact.

---

# 🤝 Connect With Me

- 💼 **LinkedIn:** *https://www.linkedin.com/in/leonard-ita*
- 🐙 **GitHub:** *https://github.com/Ita-Leonard*
- 📧 **Email:** *italeonard153@gmail.com*

---

# ⭐ Support

If you found this project useful or insightful, please consider giving this repository a **⭐ Star**. Your support helps showcase my work and encourages the continued development of impactful data analytics and public health projects.

---

# 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more information.

---

> *"Data has the power to save lives when transformed into actionable insight."*
