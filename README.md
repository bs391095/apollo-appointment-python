# Apollo Hospitals – Appointment No-Show Analysis

## Project Overview

This project focuses on analysing hospital appointment data to understand appointment no-shows, patient attendance patterns, and factors that may affect hospital operations.

The goal is to explore the data, identify useful patterns, and present the analysis through Python visualizations and an interactive dashboard. The project demonstrates how data analysis can help healthcare teams understand appointment behaviour and make more informed operational decisions.

## Live Dashboard

Explore the published Apollo Hospitals dashboard:

**[View Live Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html)**

The dashboard provides a visual way to explore the project findings without needing to run the notebook locally.

## Project Objectives

- Analyse hospital appointment and attendance patterns.
- Explore appointment no-show behaviour.
- Identify patterns across relevant appointment and patient categories.
- Create visualizations to communicate findings clearly.
- Present the analysis in an accessible dashboard.
- Develop practical insights that may support better appointment management.

## Tools and Technologies

- **Python** – Data analysis and processing
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib and Seaborn** – Data visualization
- **Jupyter Notebook** – Analysis and experimentation
- **HTML, CSS and JavaScript** – Dashboard presentation, where applicable
- **GitHub and GitHub Pages** – Project hosting and portfolio presentation

## Project Workflow

1. **Data Loading:** Load the available project datasets into the analysis environment.
2. **Data Inspection:** Examine the dataset structure, columns and data types.
3. **Data Cleaning:** Check data quality and prepare the data for analysis, where required.
4. **Exploratory Data Analysis:** Explore appointment patterns and relevant variables.
5. **Data Visualization:** Use charts to present patterns and comparisons.
6. **Dashboard Development:** Organize visual information into a dashboard.
7. **Insight Generation:** Interpret the analysis and identify potential areas for improvement.

## Dashboard and Visualizations

The following graphs are part of the project's visual analysis.

### Graph 1

![Appointment Analysis Graph 1](Dashboard_Graph/Screenshot%202026-10-16%20141823.png)

### Graph 2

![Appointment Analysis Graph 2](Dashboard_Graph/Screenshot%202026-10-16%20142255.png)

### Graph 3

![Appointment Analysis Graph 3](Dashboard_Graph/Screenshot%202026-10-16%20142317.png)

### Graph 4

![Appointment Analysis Graph 4](Dashboard_Graph/Screenshot%202026-10-16%20142336.png)

### Graph 5

![Appointment Analysis Graph 5](Dashboard_Graph/Screenshot%202026-10-16%20142353.png)

### Graph 6

![Appointment Analysis Graph 6](Dashboard_Graph/Screenshot%202026-10-16%20142415.png)

To explore the dashboard in more detail, visit the [Live Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html).

## Repository Structure

```text
apollo-appointment-python/
│
├── Data/
│   └── Project datasets
│
├── Dashboard_Graph/
│   ├── Screenshot 2026-10-16 141823.png
│   ├── Screenshot 2026-10-16 142255.png
│   ├── Screenshot 2026-10-16 142317.png
│   ├── Screenshot 2026-10-16 142336.png
│   ├── Screenshot 2026-10-16 142353.png
│   └── Screenshot 2026-10-16 142415.png
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

### 2. Open the Project Folder

```bash
cd apollo-appointment-python
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install the Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Install any additional libraries imported by the notebook if required.

### 5. Open Jupyter Notebook

```bash
jupyter notebook
```

Open the `Notebook` folder, select the relevant `.ipynb` file, and run the cells in order.

Make sure the dataset file paths used in the notebook match the location of the files in the `Data` folder.

### 6. View the Dashboard

You can also explore the published dashboard directly in your browser:

[Open Apollo Hospitals Dashboard](https://bs391095.github.io/apollo-appointment-python/Docs/Apollo_Hospitals_Dark_Dashboard.html)

No local Python setup is needed to view the hosted dashboard.

## Key Learning Outcomes

Through this project, I practised:

- Working with datasets using Python.
- Exploring and preparing data for analysis.
- Creating visualizations to communicate analytical results.
- Organizing analysis into a structured workflow.
- Presenting project outputs through an interactive dashboard.
- Maintaining and documenting a project using GitHub.

## Future Improvements

- Add further analysis of appointment attendance patterns.
- Improve dashboard filtering and interactivity where appropriate.
- Expand the set of visualizations as the analysis develops.
- Refine the presentation of findings and recommendations.

## Conclusion

This project combines exploratory data analysis, data visualization, and dashboard presentation to examine appointment no-show behaviour in a hospital setting. It represents practical work in applying data analytics techniques to a healthcare-related business problem.

The notebook, graph images, and published dashboard are organized in this repository for review and further development.
