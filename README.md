# Finnish Household Habits Analysis

## Project Overview

This project presents a comprehensive statistical analysis of Finnish household time-use survey data. The objective is to understand how individuals and households in Finland allocate their daily time across various activities, and to investigate differences between demographic groups, living environments, and days of the week.

The analysis was conducted in response to a research request from the Head of Research and is designed to be fully reproducible and understandable even for non-statistical audiences.

---

## Research Objectives

The project addresses the following key questions:

1. **Characterisation of Individuals**
   - Who are the individuals present in the dataset?
   - What are their demographic and household characteristics?

2. **Average Time Allocation**
   - How much time do Finnish households spend daily on each activity on average?

3. **Differences Across Groups**
   - Do activities differ by:
     - Living environment (e.g., urban vs rural)?
     - Day of the week (weekday vs weekend)?

4. **Associations Between Activities**
   - Which activities are statistically associated with each other?
   - Are there patterns or clusters of behaviours?

---

## Repository Structure
project
- habits.data 
- habits.txt 
- project_group_016.ipynb

project_group_016.pdf

README.md 



---

## Methodology

The analysis was conducted using Python in a Jupyter Notebook environment.

### 1️ Data Preparation

- Loaded and cleaned the dataset  
- Checked for missing values and inconsistencies  
- Converted time-use variables into meaningful units where necessary  
- Verified variable definitions using `habits.txt`  

### 2️ Descriptive Analysis

**Objective:** Characterise individuals and understand general time-use patterns.

Methods used:
- Summary statistics (mean, median, standard deviation)
- Frequency tables for categorical variables
- Visualisations (bar plots, histograms, boxplots)

### 3️ Group Comparisons

**Objective:** Determine whether time use differs across:
- Living environments
- Days of the week

Methods used:
- Independent samples t-tests
- ANOVA (where more than two groups exist)
- Assumption checks (normality, variance homogeneity)
- Grouped visualisations

### 4️ Association Analysis

**Objective:** Identify relationships between activities.

Methods used:
- Correlation matrix (Pearson correlation)
- Heatmaps
- Principal Component Analysis (PCA) or clustering (if applied)

These methods allow identification of activities that tend to occur together or substitute for each other.

---

##  Key Findings

- Finnish households spend the largest proportion of time on **[e.g., sleep, work, household tasks]**.
- Significant differences were observed between:
  - Urban and rural populations in **[e.g., commuting, leisure]**
  - Weekdays and weekends in **[e.g., work, social activities]**
- Strong positive correlations were found between:
  - **[Activity A] and [Activity B]**
- Negative associations were observed between:
  - **[Activity C] and [Activity D]**

---

## Technologies Used

- Python 3.x  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scipy  
- statsmodels  
- scikit-learn 

---

##  How to Run the Analysis

### 1. Clone the repository

```
git clone https://github.com/dieeju7/Finnish-Household-Habits-Analysis.git
```
### 2. Navigate into the project folder
```
cd project
```
### 3. Install dependencies
```
pip install -r requirements.txt
```
## 4. Launch the notebook: jupyter notebook project_group_016.ipynb

Run all cells to reproduce the analysis and results.



## Reproducibility

- All data processing, statistical analysis, and visualisation code is included in the notebook.

- Output is shown directly below each code cell.

- The report is fully reproducible.

## Interpretation Notes

- Statistical significance was evaluated at α = 0.05 unless otherwise stated.

- Where assumptions were violated, appropriate alternatives were considered.

- Correlation does not imply causation - associations are interpreted descriptively.

## Deliverable

- This repository contains:

- A complete statistical analysis

- Documented methodology

- Code and output

- Clear conclusions addressing the research questions

The final report is intended for presentation to the Board and is written to be accessible to readers without a statistical background.
