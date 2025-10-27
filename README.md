# Student Performance Analysis

Type: Statistical Analysis & Data Exploration  
Tech: Python, Pandas, Seaborn, Plotly, SciPy, Statsmodels  

This project explores the factors influencing students’ academic performance using descriptive statistics, hypothesis testing, and data visualization.  
The analysis investigates how academic effort, socio-economic background, and lifestyle habits impact exam outcomes.

## Objective
To identify and quantify the most significant factors that affect student exam performance and provide data-driven insights to improve learning outcomes.

## Dataset Overview
The dataset contains 6,607 observations and 20 variables, including:
- Academic Factors: Hours_Studied, Attendance, Tutoring_Sessions, Previous_Scores  
- Socio-Economic Factors: Family_Income, Parental_Education_Level, Access_to_Resources  
- Lifestyle Factors: Sleep_Hours, Physical_Activity, Internet_Access  
- Target Variable: Exam_Score  

## Methodology

#### 1. Data Wrangling
- Imported and inspected dataset for missing values and data types  
- Handled missing data by dropping incomplete rows and resetting the index  
- Verified data integrity after cleaning  

#### 2. Descriptive Statistics
Computed key statistical metrics to understand data distribution:
- Mean, median, and standard deviation for numeric variables  
- Frequency distributions for categorical variables such as Motivation_Level, School_Type, and Parental_Involvement  
- Generated histograms, bar plots, and box plots for distribution and variability insights  

#### 3. Data Visualization
Visual analyses were conducted using Seaborn and Plotly:
- Univariate Analysis: Histograms and count plots for variable distributions  
- Bivariate Analysis: Scatterplots and boxplots showing relationships between study habits and scores  
- Multivariate Analysis: Correlation heatmap and pair plots highlighting dependencies  

Key findings included strong correlations between:
- Attendance ↔ Exam_Score  
- Sleep_Hours ↔ Exam_Score  
- Previous_Scores ↔ Exam_Score  
- Tutoring_Sessions ↔ Exam_Score  

Key Observations:
- Students with medium parental involvement and moderate motivation form the largest group  
- Public school students dominate the dataset, indicating broader representation  
- Despite studying longer hours, not all students achieve higher scores, suggesting diminishing returns beyond a certain study threshold  


### Summary
This analysis demonstrates the power of data-driven insights in educational decision-making.  
Through rigorous statistical testing and visualization, the study highlights actionable strategies to improve student outcomes.
All analyses were conducted in Python using Pandas, Seaborn, Matplotlib, Plotly, and SciPy for reproducible and transparent results.

