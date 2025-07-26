📊 IQR Method - Outlier Detection
This project demonstrates how to identify and remove outliers from a dataset using the IQR (Interquartile Range) method. The technique is applied on a placement dataset containing student information.

📁 Dataset
placement.csv

Columns:

cgpa: Cumulative Grade Point Average

placement_exam_marks: Score in placement exam

placed: Placement status (1 for placed, 0 for not placed)

🧠 What is IQR?
IQR = Q3 − Q1

Outliers are defined as:

Values < Q1 − 1.5 × IQR

Values > Q3 + 1.5 × IQR

🔍 Steps Covered
Load dataset using Pandas

Visualize distributions using Seaborn

Calculate IQR for numeric columns

Detect and remove outliers

Replot to compare data before and after cleaning

📦 Libraries Used
pandas

numpy

matplotlib

seaborn

📊 Visual Output
KDE and boxplots to visualize the effect of outlier removal
