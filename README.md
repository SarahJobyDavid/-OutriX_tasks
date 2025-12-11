# Student Performance EDA

This project conducts comprehensive exploratory data analysis on student exam performance datasets to identify factors influencing academic outcomes. The Jupyter notebook examines relationships between demographics, socioeconomic factors, and scores across math, reading, and writing subjects.

## Project Overview

The notebook analyzes the "Students Performance in Exams" dataset using pandas for data manipulation and seaborn/matplotlib for visualizations. It reveals performance patterns by gender, ethnicity, parental education, lunch type, and test preparation.

## Core Analysis Workflow

The project follows a structured EDA pipeline for educational data analysis.

- Dataset loading from CSV (StudentsPerformance.csv) into pandas DataFrame with initial shape inspection (1000 rows typical).  
- Data exploration includes summary statistics, missing value checks, and categorical variable distributions.  
- Feature engineering creates total scores, pass/fail flags, and categorical groupings for deeper analysis.  

## Key Visualizations

Multiple seaborn and matplotlib plots uncover performance insights.

- Distribution plots and boxplots compare scores across gender, race/ethnicity groups, and parental education levels.  
- Heatmaps show correlations between math, reading, and writing scores.  
- Bar charts analyze pass rates by lunch type (standard vs free/reduced) and test preparation course completion.  
- Violin plots and count plots reveal score distributions and demographic breakdowns.

## Dataset Insights

Analysis typically shows reading/writing scores higher than math, females outperforming males in reading/writing, group E students leading academically, and standard lunch/test prep correlating with better outcomes. Total pass rates hover around 65-70% with clear socioeconomic and preparation impacts.

## Requirements

Python 3.6+  
Libraries: pandas, numpy, seaborn, matplotlib  
Environment: Jupyter Notebook or Google Colab.

All libraries are pre-installed in Colab and Kaggle environments.

## Usage

**Open in Jupyter/Colab:**  
- Launch Jupyter Notebook or Google Colab.  
- Upload/open `EDA-Student-Performance.ipynb`.

**Prepare Data:**  
Ensure you have the CSV file "StudentsPerformance.csv". Expected columns include:  
- `gender`: Male/Female  
- `race/ethnicity`: group A-E  
- `parental level of education`: Various education levels  
- `lunch`: standard/free/reduced  
- `test preparation course`: none/completed  
- `math score`: 0-100  
- `reading score`: 17-100  
- `writing score`: 10-100  

Example data source: Kaggle Students Performance in Exams dataset.

**Run the Notebook:**  
- Execute cells sequentially (Shift+Enter).  
- Update file path if needed for CSV loading.  
- Notebook generates comprehensive EDA plots and summary statistics.

**Expected Outputs:**  
- Console prints: Dataset shape (1000x8), score statistics (math:66±15, reading:69±15, writing:68±15), pass rates.  
- Plots:  
  - Score distributions by demographics.  
  - Correlation heatmaps.  
  - Performance comparisons across categorical variables.  
  - Pass/fail analysis by preparation and socioeconomic factors.
