# Apollo Hospitals – Appointment No-Show and Patient Engagement Analysis

## Project Overview

This project focuses on analysing hospital appointment data to understand appointment attendance, no-show patterns, patient engagement, and their potential impact on healthcare operations.

The project uses Python-based analysis and visualizations to explore appointment behaviour and presents the findings through a published HTML dashboard. The objective is to make the analysis easy to understand and highlight areas where data-driven approaches may support appointment management and resource planning.

## Live Dashboard

**[View Live Apollo Hospitals Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html)**

The dashboard brings together visual analysis of appointment outcomes, no-show patterns, booking lead time, patient and specialty comparisons, and other operational indicators.

## Project Objectives

- Analyse appointment attendance and no-show patterns.
- Explore appointment trends and booking behaviour.
- Examine no-show patterns across relevant patient and service categories.
- Investigate the relationship between booking lead time and appointment attendance.
- Explore patient engagement and reminder-related patterns.
- Understand the potential operational and financial implications of missed appointments.
- Communicate findings through visualizations and an accessible dashboard.

## Tools and Technologies

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib and Seaborn** – Data visualization
- **Jupyter Notebook** – Exploratory analysis
- **HTML and CSS** – Dashboard presentation
- **GitHub** – Version control and project repository
- **GitHub Pages** – Dashboard publishing

## Project Workflow

1. **Data Loading:** Load the appointment dataset into the analysis environment.
2. **Data Inspection:** Review the dataset structure, columns, and data types.
3. **Data Preparation:** Prepare the data for analysis and check for data-quality issues as required.
4. **Exploratory Data Analysis:** Explore appointment outcomes, trends, and relevant variables.
5. **Pattern Analysis:** Compare attendance behaviour across booking characteristics and service categories.
6. **Visualization:** Present analytical patterns through charts.
7. **Dashboard Development:** Organize the visualizations into a dashboard for easier exploration.
8. **Interpretation:** Explain what the observed patterns may mean for appointment management and hospital operations.

## Dashboard Visualizations

The following graphs are included in the repository.

### Graph 1

![Appointment Analysis Graph 1](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20141823.png)

### Graph 2

![Appointment Analysis Graph 2](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142255.png)

### Graph 3

![Appointment Analysis Graph 3](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142317.png)

### Graph 4

![Appointment Analysis Graph 4](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142336.png)

### Graph 5

![Appointment Analysis Graph 5](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142353.png)

### Graph 6

![Appointment Analysis Graph 6](https://raw.githubusercontent.com/bs391095/apollo-appointment-python/main/Deshboard_Graph/Screenshot%202026-10-16%20142415.png)

For the complete dashboard experience, visit the [Live Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html).

## Repository Structure

```text
apollo-appointment-python/
│
├── Data/
│   └── Project datasets
│
├── Deshboard_Graph/
│   └── Graph screenshots
│
├── Docs/
│   └── Apollo_Hospitals_Dark_Dashboard.html
│
├── Notebook/
│   └── Project analysis notebook
│
└── README.md
```

## How to Run This Project

### 1. Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/bs391095/apollo-appointment-python.git
```

### 2. Navigate to the Project Folder

```bash
cd apollo-appointment-python
```

### 3. Create a Virtual Environment (Optional)

On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### 4. Install the Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

If the notebook imports additional libraries, install those packages as well.

### 5. Open Jupyter Notebook

```bash
jupyter notebook
```

Open the `Notebook` folder, select the relevant `.ipynb` file, and execute the cells in order.

Make sure the dataset paths used in the notebook match the actual files inside the `Data` folder.

### 6. Open the Dashboard

The published dashboard can be viewed directly in a web browser without installing Python:

**[Open Live Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html)**

## Author

**Bhoopendra Singh**

## Project Interpretations

### 1. Appointment Attendance and No-Shows

Comparing attended and missed appointments helps evaluate appointment attendance patterns. These patterns can help identify where appointment confirmation and follow-up processes may need further investigation.

### 2. Booking Lead Time

The relationship between booking lead time and no-show behaviour can help explore whether appointments scheduled further in advance have different attendance patterns. If supported by the analysis, this may inform the timing of appointment reminders.

### 3. Specialty-Level Patterns

Comparing appointment outcomes across medical specialties may reveal differences in attendance behaviour. These comparisons should consider both the number of appointments and the no-show rate to avoid misleading conclusions from smaller groups.

### 4. Patient Engagement

Reminder-related and previous appointment behaviour can help explore patient engagement patterns. Such relationships should be interpreted carefully, because the presence of a reminder or a patient's past behaviour does not guarantee a particular future outcome.

### 5. Operational Implications

Missed appointments can affect how effectively scheduled consultation capacity is used. Understanding attendance patterns may help hospital teams investigate scheduling gaps and improve appointment follow-up processes.

### 6. Financial Implications

The estimated financial impact of missed appointments can help illustrate why attendance matters to healthcare operations. However, estimated revenue exposure should not automatically be treated as confirmed revenue loss; the calculation depends on the project's assumptions and underlying data.

### Overall Interpretation

This project demonstrates how appointment data can be explored through Python, visualized through charts, and presented through a dashboard. The analysis can help identify attendance patterns and areas for further investigation in patient engagement, scheduling, and operational planning.

The findings should be interpreted as analytical observations rather than proof of cause and effect. Any operational recommendations should be validated against the underlying data and hospital requirements.
