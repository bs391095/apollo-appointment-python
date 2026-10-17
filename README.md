# Apollo Hospitals — Appointment No-Show Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4c72b0)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Business Objectives](#business-objectives)
- [Tools and Technologies](#tools-and-technologies)
- [Project Workflow](#project-workflow)
- [Appointment Outcome Distribution](#appointment-outcome-distribution)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Findings](#key-findings)
- [Overall Interpretation](#overall-interpretation)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Project Deliverable](#project-deliverable)
- [Skills Demonstrated](#skills-demonstrated)
- [Author](#author)

## Project Overview

Apollo Hospitals Appointment No-Show Analysis is a data analytics project focused on understanding appointment outcomes and patient attendance patterns. The project uses Python to analyse appointment data and visualise important findings.

An HTML dashboard presents the project visuals and key information in an accessible format.

**[View Live Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html)**

## Dataset Overview

The dataset contains **75,000 appointment records**. The table below summarises the distribution of appointment outcomes.

| Appointment Status | Count | % of Total |
|---|---:|---:|
| Completed | 55,275 | 73.7% |
| No-Show | 11,584 | 15.4% |
| Cancelled | 5,793 | 7.7% |
| Scheduled | 2,348 | 3.1% |
| **Total** | **75,000** | **100%** |

*Note: Individual percentages are rounded, so they add up to approximately 99.9%.*

## Business Objectives

- Analyse appointment outcomes and patient attendance.
- Understand the scale of missed appointments.
- Explore patterns in appointment data.
- Present findings through charts and an HTML dashboard.
- Identify areas for further investigation to support patient engagement and hospital resource utilisation.

## Tools and Technologies

- **Python:** Programming and data analysis
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualisation and chart creation
- **Seaborn:** Statistical data visualisation
- **Jupyter Notebook:** Running and documenting the analysis
- **HTML:** Dashboard presentation

## Project Workflow

1. **Data Preparation:** Load and prepare the appointment dataset for analysis.
2. **Exploratory Data Analysis:** Examine appointment outcomes and patterns.
3. **Visualisation:** Create charts using Matplotlib and Seaborn.
4. **Dashboard Development:** Present project visuals through an HTML dashboard.
5. **Interpretation:** Summarise key results and identify opportunities for further analysis.

## Appointment Outcome Distribution

This visualisation provides an overview of appointment outcomes and helps highlight the proportion of no-show appointments.

![Appointment Outcome Distribution](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20141823.png)

## Exploratory Data Analysis

The project includes visualisations created during the analysis to explore appointment outcomes and related patterns.

### Analysis Visualisations

**1. Appointment Analysis**

![Appointment Analysis](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142255.png)

**2. Patient Attendance Patterns**

![Patient Attendance Patterns](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142317.png)

**3. Appointment Trends**

![Appointment Trends](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142336.png)

**4. Additional Analysis**

![Additional Analysis](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142353.png)

**5. Dashboard Visualisation**

![Dashboard Visualisation](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142415.png)

## Key Findings

- **75,000** appointment records are included in the dataset.
- **55,275 appointments (73.7%)** were completed.
- **11,584 appointments (15.4%)** were marked as no-shows.
- **5,793 appointments (7.7%)** were cancelled.
- **2,348 appointments (3.1%)** remained scheduled.

These figures provide a high-level view of appointment outcomes and highlight no-shows as an important area for further analysis.

## Overall Interpretation

The analysis shows that **11,584 appointments, approximately 15.4% of the 75,000 records, were marked as no-shows**. Although most appointments were completed, missed appointments remain an important area for healthcare operations. Further investigation into factors such as appointment lead time, reminder effectiveness, and other available appointment characteristics could help identify patterns associated with missed visits. These insights can support more informed decisions about patient engagement and hospital resource utilisation.

## Project Structure

- `Data/` — Project datasets
- `Notebook/` — Jupyter Notebook analysis
- `Deshboard_Graph/` — Analysis charts and screenshots
- `Docs/` — HTML dashboard

## How to Run

1. Clone or download this repository.
2. Open the notebook in the `Notebook/` folder using Jupyter Notebook.
3. Make sure the dataset and required Python libraries are available.
4. Open the HTML dashboard using the live link provided above.

## Project Deliverable

**[Open the Apollo Hospitals HTML Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html)**

## Skills Demonstrated

Python, Pandas, NumPy, data preparation, exploratory data analysis (EDA), Matplotlib, Seaborn, data visualisation, dashboard presentation, and analytical thinking.

---

## Author

**Bhoopendra Singh**

Aspiring Data Analyst

[GitHub Profile](https://github.com/bs391095)
