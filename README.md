
# Student Performance: Exploratory Data Analysis

An independent data analysis project exploring relationships between student characteristics and academic performance.

## Project Overview

This project uses Python, Pandas, and Matplotlib to analyze student performance through descriptive statistics, correlation analysis, and data visualization.

## Dataset

- **Source:** UCI Student Performance Dataset
- **Subject:** Mathematics
- **Records:** 395
- **Variables:** 33
- **Final Grade (G3):** 0–20

[Original Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)

## Research Questions

1. How is study time associated with final grades?
2. Is there a relationship between absences and academic performance?
3. How strongly are previous grades associated with final grades?
4. How are final grades distributed?

## Tools and Methods

- Python
- Pandas
- Matplotlib
- Exploratory Data Analysis (EDA)
- Descriptive Statistics
- Pearson Correlation Analysis
- Data Visualization
- Sensitivity Analysis

## Key Findings

### Study Time
Students in study-time category 3 had the highest average final grade (11.40/20). However, the differences between categories were relatively small.

### Absences
The correlation between absences and final grades was very weak (r = 0.034).

After restricting the analysis to students with 20 or fewer absences, the correlation remained weak (r = 0.084).

### Previous Grades
Previous grades showed strong positive correlations with final grades:

- G1 vs G3: 0.801
- G2 vs G3: 0.905

### Grade Distribution
- Mean: 10.42
- Median: 11
- Mode: 10
- Zero grades: 38 students (9.62%)

Excluding zero grades increased the mean to 11.52, while the median remained unchanged.

## Limitations

This is an observational dataset. The findings show statistical associations rather than causal relationships.

Potential nonlinear relationships and confounding variables were not fully investigated.

## How to Run

1. Download or clone this repository.
2. Open `student_performance_analysis.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure `data/student-mat.csv` is accessible.
4. Run the notebook cells in order.

## Author

Computer Engineering Student
