# B-Line-Transit-Service-Optimization
## 📖 Project Overview

Public transportation agencies must balance service availability with operational efficiency while responding to changing rider demand. This project applies data science techniques to historical B-Line transit data to identify demand patterns, evaluate service utilization, and provide data-driven recommendations for service optimization.

This project was completed as part of the **Master of Science in Data Science and Analytics** program at **California State University, Chico**.

---

## 📊 Project Highlights

- 🚍 **134,548+** boarding records analyzed
- 📅 Study period: **January 2023 – March 2025**
- 🚌 **23** transit routes evaluated
- 📈 **9,469+** trips analyzed
- 🔍 Identified underutilized routes using observed-to-expected ridership ratios
- 📊 Applied ARMA, GLSAR, OLS, and Poisson regression models
- 🎓 Master's Culminating Project at California State University, Chico

---

## 🎯 Research Questions

### RQ1: Rider Demand Patterns
How does rider demand fluctuate across different times of the day, days of the week, and seasons?

### RQ2: Service Utilization
How does service utilization, measured as ridership per trip, vary across different times of day?

### RQ3: Route Efficiency
Which routes are underutilized, and how can they be identified using ridership data?

---

## Dataset

The analysis uses historical B-Line transit data provided by Butte Regional Transit (B-Line).

The project includes:

- Ridership validation records
- Fare transaction records
- Route and stop information

Data Summary
| Metric | Value |
|---------|---------|
| Boarding Records Analyzed | 134,548+ |
| Study Period | January 2023 – March 2025 |
| Routes Analyzed | 23 |
| Trip Records | 9,469+ |
| Transit System | B-Line (Butte Regional Transit) |

## 🛠 Methodology

### Data Preparation
- Data cleaning and preprocessing
- Feature engineering
- Time-based variable creation
- Dataset integration and aggregation

### Exploratory Data Analysis
- Hourly ridership trends
- Daily ridership patterns
- Monthly and seasonal analysis
- Route-level summaries

### Statistical Modeling

#### Time Series Analysis
- Augmented Dickey-Fuller (ADF) Test
- ARMA (1,1) Modeling
- GLSAR (AR1) Modeling

#### Regression Analysis
- Ordinary Least Squares (OLS)
- HC3 Robust Standard Errors
- Poisson Regression

#### Route Utilization Analysis
- Observed-to-Expected Ridership Ratios
- Underutilized Route Identification

---

## 🔑 Key Findings

### Ridership Demand
- Ridership peaks during weekday commuting hours.
- Weekend demand is substantially lower than weekday demand.
- Academic months show higher ridership than summer periods.

### Service Utilization
- Boardings per trip vary significantly across operating hours.
- Morning and afternoon periods experience the highest utilization.
- Evening service generally exhibits lower ridership.

### Underutilized Routes
Routes identified as operating below expected demand include:

- South Oroville
- Oro Dam
- Student Shuttle – Warner/Oak
- Gridley – Chico

These findings highlight opportunities for schedule adjustments, route redesign, and more efficient service allocation.

---

## 💻 Technologies Used

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

---
## 📂 Repository Structure

## 📂 Repository Structure

```text
B-Line-Transit-Service-Optimization/
│
├── notebooks/
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Initial_EDA.ipynb
│   ├── 03_Merge_Datasets.ipynb
│   ├── 04_RQ1_Demand_Fluctuations.ipynb
│   ├── 05_RQ2_Service_Utilization.ipynb
│   └── 06_RQ3_Underutilized_Routes.ipynb
│
├── reports/
│   ├── Final_Report.pdf
│   └── Project_Proposal.pdf
│
└── README.md
```


---
## 🔒 Data Availability

The datasets used in this project were provided by **Butte Regional Transit (B-Line)** for academic research purposes.

Due to data ownership and sharing restrictions, the raw datasets are not included in this repository.

This repository contains the complete analytical workflow, methodology, and documentation used to conduct the study.

---

## 👨‍💻 Author

**Zakir Sajid Elaskar**

Master of Science in Data Science and Analytics  
California State University, Chico

- LinkedIn: *Add your LinkedIn profile URL*
- GitHub: *Add your GitHub profile URL*

---

## 📄 Report

The complete project report is available in:

``` reports/Final_Report.pdf ```

