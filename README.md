
# 🎓 Analysis of THE World University Rankings (2016–2023)

![Power BI](https://img.shields.io/badge/Power%20BI-Interactive%20Dashboard-yellow)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Preparation-green)
![Project](https://img.shields.io/badge/Academic%20Project-DSC651-blue)
![Period](https://img.shields.io/badge/Analysis-2016--2023-purple)

**Nur Aina Aqiela binti Mohd Zam**  
Bachelor of Science (Hons.) Mathematics | Universiti Teknologi MARA (UiTM)

---

## 🌍 Project Introduction

Times Higher Education (THE) is a recognised source of information on global higher education, particularly through its annual World University Rankings. These rankings evaluate universities based on several performance indicators, including teaching, research, citations, industry income and international outlook.

This project analyses the **THE World University Rankings from 2016 to 2023** to explore the development of global higher education, university performance and the relationship between key performance indicators.

Using Microsoft Excel for data preparation and Power BI for data visualisation, the project transforms ranking data into interactive dashboards to communicate trends, comparisons and findings.

## 🎯 Problem Statement

The higher education landscape continues to evolve through changes in research, teaching approaches and international collaboration. However, understanding how these developments relate to university performance and global rankings requires further analysis.

This project focuses on examining university performance over eight years, exploring relationships among important performance indicators and investigating international student enrolment in relation to university rankings.

## 🎯 Project Objectives

1. To provide a comprehensive understanding of the evolution of higher education.
2. To investigate university performance over the past eight years.
3. To determine the interdependencies among key performance indicators.
4. To explore international student enrolment in relation to university rankings.

## 🔎 Project Scope

The project focuses on three main areas:

- **Higher Education Evolution:** Examining changes in global university representation and performance from 2016 to 2023.
- **University Performance Indicators:** Exploring indicators such as teaching, research, industry income and international outlook, and comparing their trends with overall ranking performance.
- **International Student Enrolment:** Investigating international student numbers and their relationship with university performance and internationalisation.

## 👥 Target Users

The dashboard is designed to provide useful information for different groups:

- **University Students:** Explore university rankings and performance trends to support higher education choices.
- **Parents:** Understand the academic reputation and performance of institutions when supporting their children's educational decisions.
- **Lecturers:** Explore global university rankings and identify potential academic and research collaborations.
- **Universities:** Benchmark their performance against other institutions and identify potential areas for improvement.

## 📊 Dataset Overview

**Dataset:** [THE World University Rankings 2011–2023 – Kaggle](https://www.kaggle.com/datasets/r1chardson/the-world-university-rankings-2011-2023)

| Dataset Information | Details |
|---|---|
| Data Source | Kaggle |
| Selected Period | 2016–2023 |
| Original Dataset Records | 11,522 instances |
| Original Dataset Attributes | 24 |
| Analysis Attributes | 31, including derived attributes |
| Main Subject | Global university rankings |

The dataset contains information on university rankings, overall scores, performance indicators, geographical locations and student statistics.

## 🔄 Methodology

The project follows the Generic Data Science Life Cycle, covering the following stages:

### 1. Problem Definition
Identified the main research questions relating to global university performance, ranking trends, key performance indicators and international student enrolment.

### 2. Data Collection
Obtained the THE World University Rankings dataset from Kaggle, focusing on the period from 2016 to 2023.

### 3. Data Preparation
Prepared and cleaned the dataset using Microsoft Excel to address data errors, inconsistencies and missing values.

Data preparation activities included:
- Correcting university name and alias inconsistencies.
- Removing invalid ranking entries and unsuitable records.
- Handling missing and `n/a` values.
- Correcting the format of the female-to-male student ratio.
- Organising and combining yearly ranking data.

### 4. Exploratory Data Analysis (EDA)
Used statistical and graphical techniques, including Excel PivotTables, to explore the dataset, identify patterns and examine trends in university rankings and performance indicators.

### 5. Data Visualisation
Developed an interactive dashboard using Microsoft Power BI to present university rankings, performance comparisons and international student trends.

### 6. Results Interpretation and Communication
Interpreted the visualisations and communicated the findings through data storytelling, a project report and presentation.

## 🧹 Data Preparation and Derived Attributes

Several additional attributes were created to support the analysis:

| Derived Attribute | Description |
|---|---|
| `year` | Identifies the year associated with each university ranking record. |
| `continent` | Groups university locations according to their respective continents. |
| `international_students` | Calculates the estimated number of international students using total student numbers and the international student percentage. |
| `female_ratio` | Extracts the female student percentage from the female-to-male ratio. |
| `male_ratio` | Extracts the male student percentage from the female-to-male ratio. |
| `total_female` | Calculates the total number of female students. |
| `total_male` | Calculates the total number of male students. |

These attributes support geographical comparisons, student demographic analysis and internationalisation analysis.

---

## 📈 Dashboard Overview

The interactive Power BI dashboard consists of four pages. Each page explores a different aspect of THE World University Rankings, providing users with a way to examine global university representation, ranking trends, performance indicators and international student growth.

### 1. 🌐 Global University Rankings Analysis

This page provides an overview of the geographical distribution of ranked universities from 2016 to 2023.

It presents the number of ranked universities by country, supported by key performance indicators, a university ranking table and a bubble chart showing the global distribution of institutions.

**Key features:**
- Total number of ranked universities and participating countries.
- Top 10 countries ranked by the number of universities.
- University names, countries and ranking positions.
- Bubble chart illustrating the geographical distribution of ranked universities.
- Year and country filters for exploring different selections.

**Key observation:** The United States has the highest number of ranked universities, followed by the United Kingdom and Japan.

![Global University Rankings Analysis](dashboard1_overview.png)

### 2. 📈 University Performance Overview

This page examines changes in university rankings and country representation over the eight-year period.

It compares the ranking trends of selected leading universities, tracks university representation across selected countries and provides a closer look at the performance of individual institutions.

**Key features:**
- Ranking trends for California Institute of Technology, Harvard University, Stanford University, University of Cambridge and University of Oxford.
- Country representation trends for Australia, Germany, the Netherlands, the United Kingdom and the United States.
- Ranking comparisons for selected universities, including Monash University, Nanyang Technological University, Technical University of Munich and Tsinghua University.

**Key observation:** Among the selected leading universities, the University of Oxford moved from second place in 2016 to first place in 2017 and maintained the top position through 2023.

![University Performance Overview](dashboard2_ranking_trend.png)

### 3. 🏛️ University Score Component Analysis

This page explores selected university performance indicators and their relationship with overall ranking positions.

The analysis focuses on Teaching, Research and Industry Income scores, allowing users to compare changes in these indicators over time alongside overall score rankings.

It also includes a gender distribution visualisation to provide additional insight into university student demographics.

**Key features:**
- Teaching scores and overall score rankings by year.
- Research scores and overall score rankings by year.
- Industry Income scores and overall score rankings by year.
- Gender distribution analysis.
- University selector for examining individual institutions.

**Key observation:** The dashboard allows users to compare changes in individual performance indicators with overall ranking positions. It also shows differences in gender distribution among selected universities, with Harvard University displaying a relatively balanced male-to-female distribution.

![University Score Component Analysis](dashboard3_score_analysis.png)

### 4. 🌏 International Student Growth

This page investigates international student enrolment and international outlook trends from 2016 to 2023.

It examines the growth in international student numbers across continents, compares universities based on their international student percentages and tracks changes in average International Outlook scores.

**Key features:**
- Total international student numbers by year.
- Continent filters covering Africa, Asia, Australia, Europe, North America and South America.
- Comparison of universities based on their international student percentages.
- Average International Outlook scores by year.

**Key observation:** The total number of international students increased from approximately 2.0 million in 2016 to 3.6 million in 2023. The average International Outlook score fluctuated throughout the period, reaching its lowest displayed value in 2022 before increasing in 2023.

![International Student Growth](dashboard4_international_growth.png)

---

## 💡 Key Insights

The analysis provides several observations about global higher education:

- **Global University Representation:** The United States, United Kingdom and Japan have the highest university representation in the updated dashboard.
- **University Ranking Trends:** The University of Oxford maintained the first position from 2017 to 2023 among the selected leading universities.
- **Performance Indicators:** Teaching, Research and Industry Income scores provide different perspectives for examining university performance and overall ranking positions.
- **International Student Enrolment:** International student numbers increased consistently from approximately 2.0 million to 3.6 million over the analysis period.
- **International Outlook:** Average International Outlook scores experienced fluctuations between 2016 and 2023, with a slight recovery in 2023 after reaching a lower value in 2022.

## 🛠️ Tools and Technical Skills

| Area | Tools / Skills |
|---|---|
| Data Preparation | Microsoft Excel |
| Data Analysis | Excel PivotTables, Exploratory Data Analysis |
| Data Transformation | Data cleaning, data organisation, derived attributes |
| Data Visualisation | Microsoft Power BI |
| Reporting | Data storytelling, visual presentation |

## 👩‍💻 My Contribution

**Role: Data Manager | Group Academic Project**

My primary responsibilities focused on data management and preparation:

- Gathered and prepared the THE World University Rankings dataset.
- Cleaned and organised the data using Microsoft Excel.
- Created derived attributes to support geographical and student demographic analysis.
- Used Excel PivotTables to summarise and explore the dataset.
- Contributed to the preparation of data for visualisation and the interpretation of findings.

## 🚀 How to Explore the Dashboard

1. Download the Power BI `.pbix` file from this repository.
2. Open the file using **Microsoft Power BI Desktop**.
3. Navigate through the four dashboard pages.
4. Use the available filters and university selectors to explore different rankings, comparisons and trends.

## 🎓 Project Information

| | |
|---|---|
| Course | Data Representation and Reporting Techniques (DSC651) |
| Programme | Bachelor of Science (Hons.) Mathematics |
| University | Universiti Teknologi MARA (UiTM) |
| Project Period | 2023–2024 |
| Project Type | Group Academic Project |
| Role | Data Manager |
| Status | Completed |

---

*This was a group academic project. My main contribution focused on data management, preparation and supporting the analysis.*
