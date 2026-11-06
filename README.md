# Student-Performance-Analysis-EDA-Python
Exploratory data analysis of 30,000+ student records in Python, using Pandas, Seaborn and Matplotlib to uncover how parental education, sport practice and other factors relate to Math, Reading and Writing scores.

# Student Performance Analysis | Python EDA

An exploratory data analysis (EDA) project that examines which background factors
are linked to student performance in Math, Reading and Writing.

## Project Objective
Analyze a dataset of ~30,600 students to understand how gender, ethnic group,
parental education, parental marital status and sport participation relate to
test scores, and to identify where support can be targeted most effectively.

## Tools & Technologies
Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## Analysis Highlights
- Loaded, inspected and cleaned the data (dropped the index column, checked missing values)
- Aggregated average scores by category using `groupby()` and `agg()`
- Built a count plot, heatmaps, box plots and a pie chart
- Checked Math, Reading and Writing score distributions for outliers

## Key Insights
- **Parental education** shows the strongest link to scores, with a gap of roughly 10-13 points between the highest and lowest education groups
- **Parental marital status** has almost no effect (about 1 point or less)
- **Regular sport practice** is linked to modestly higher scores
- Outliers appear only at the low end of the score range
- Several columns contain missing values that still need handling

## Business Recommendations
- Target tutoring and mentoring at students from lower parental-education backgrounds
- Engage parents through workshops on supporting learning at home
- Encourage regular sport and extracurricular participation
- Identify low-scoring students early and check for data-entry errors
- Extend the analysis to study hours, test prep and lunch type

> Note: findings are correlations from averages, not proof of cause and effect.

## Repository Contents
- `Student_Performance_Analysis.ipynb` - the full notebook
- `Student_data.csv` - the dataset
- `Executive_Summary_Student_Performance.pdf` - one-page summary of findings

## Future Work
Handle missing values, analyze weekly study hours and test preparation, and apply
statistical tests or regression to find which factors matter most.
