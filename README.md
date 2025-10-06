
# Project Portfolio Analysis

This repository contains a synthetic dataset and analysis for demonstrating data analytics and project management insights. The goal is to showcase skills relevant to business analysts, program managers, and data analysts.

## Contents

- **dataset.csv** – A synthetic dataset representing 200 projects with attributes such as start and end dates, budget, actual spending, team size, scope changes, client satisfaction, and a success indicator.
- **analysis.ipynb** – A Jupyter notebook that performs exploratory data analysis, visualizes key relationships, and builds a logistic regression model to predict project success.
- **requirements.txt** – List of Python libraries used.

## Objective

This repository demonstrates analytical skills by generating a synthetic portfolio dataset, performing exploratory data analysis, and building predictive models. It's tailored for showcasing capabilities relevant to business analysts, program managers, and data analysts roles.

## Synthetic Dataset

The dataset includes the following columns:

| Column | Description |
|-------|------------|
| `Project_ID` | Unique identifier for each project |
| `Start_Date` | Project start date |
| `End_Date` | Project end date |
| `Duration_Days` | Duration of the project in days |
| `Budget` | Budget allocated for the project |
| `Actual_Spent` | Actual expenditure |
| `Team_Size` | Number of team members |
| `Scope_Change` | Number of scope changes |
| `Client_Satisfaction` | Client satisfaction rating (1–5) |
| `Success` | Binary indicator of project success (1=success, 0=failure) |

## Getting Started

To run the analysis notebook locally:

1. Clone this repository:

```bash
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>
```

2. Install the required packages using `pip`:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebook:

```bash
jupyter notebook analysis.ipynb
```

The notebook will load `dataset.csv`, perform exploratory data analysis with visualizations, and train a logistic regression model to predict project success.

## Applications

This project demonstrates:

- **Data collection & preprocessing** – Generating and handling synthetic project data.
- **Exploratory data analysis** – Uncovering patterns and relationships with visualizations.
- **Predictive modeling** – Building a logistic regression model to identify factors contributing to project success.

## License

This project is provided for educational purposes.
