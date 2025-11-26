# Student-Performance-Analysis
This project explores a Student Performance dataset using Python (pandas). The notebook (note.ipynb) walks through the full data-analysis workflow: cleaning, exploration, feature engineering, and insights.
🔍 Project Overview

The analysis covers:

1. Data Loading

* Reads [student_performance_updated_1000.csv](https://github.com/user-attachments/files/23771082/student_performance_updated_1000.csv)

* Displays structure, column types, and sample rows

* 2. Data Quality Checks

* Detects missing values

* Identifies duplicate rows

* Confirms data types and categorical fields

  3. Data Cleaning

* Numerical missing values → filled with mean

* Categorical missing values → filled with mode

* Drops or fixes any inconsistencies

4. Exploratory Data Analysis (EDA)

Includes:

* Grade distribution

* Study hours patterns

* Attendance analysis

* Subsetting (e.g., only low performers, only high performers)

 5. Feature Engineering

Creates a new column:

`PerformanceCategory`

* High: FinalGrade ≥ 85

* Medium: FinalGrade ≥ 70

* Low: < 70

  6. Filtering & Insights

Examples:

* Students with low attendance

*Students with high study hours

* Gender-based summaries

* Top/lowest performers

7. Grouping & Aggregations

* groupby() on gender, performance categories, study patterns

* Combined metrics using agg()

* Merging external summary data for comparison

8. Statistical Analysis

* Correlations with FinalGrade

* Summary statistics for major variables

* Quick extraction of average grades, attendance, etc.

🛠️ Tech Stack

* Python

* pandas

* NumPy

* Jupyter Notebook

🚀 How to Run This Project

```python
# Install dependencies
pip install pandas numpy

# Open the notebook
jupyter notebook Student-Performance-Analysis.ipynb
```
📂 Dataset Description

The dataset includes:

* Demographics — Name, Gender

* Academic Metrics — FinalGrade, AttendanceRate

* Behavioral Factors — StudyHoursPerWeek

* Additional Attributes — relevant performance indicators

Perfect for EDA and feature engineering practice.
