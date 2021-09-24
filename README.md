# Cohort-Analysis


## Summary

In the project Recommendation System (see corresponding repository in this account), 
the 10-milllion-row MovieLens data set (see https://grouplens.org/datasets/movielens/ )
has been analyzed. Time impact was a predictor, rather limited though. 

This project further elaborates on the idea of time impact by investigating 
the notion of cohort behavioral patterns. It analyzes a one-million-row extract 
from the 10-milllion-row MovieLens data set. 

This allows to deliver additional insights about data time component and users’ behavioral patterns 
and could help to predict ratings when revisiting the Recommendation System project. 

<br>

## Files

This data analysis project is comprised of 70 files:
-	7 SQL files,
-	13 XLSX files,
-	35 CSV files,
-	13 PNG files, 
-	1 Rmd (R Markdown) file 
-	and 1 HTML file. 

<br>

## Work Organization

* PostgreSQL with the IDE pgAdmin

Data import, database management and data wrangling 
have been performed in PostgreSQL with the IDE pgAdmin. 
A database (called “cohort-analysis”) has been created in PostgreSQL. 
Cohort analysis has been conducted in PostgreSQL as well 
but also in Excel with pivot tables and graphs. 

The final HTML report (70_cohort_analysis_final_report.html) 
has been produced in R Markdown (69_cohort_analysis_final_report.Rmd). 

Input data are stored in a zipped CSV file:  
01_data_import_from_recommendation_project.zip. 

Data have also been transferred in CSV format between SQL, Excel and R Markdown. 
CSV files have been produced in Calc from LibreOffice 
(for technical convenience with decimal separator). 

Graphs have been transferred in PNG format. 

More explanation is provided in the final report 
(70_cohort_analysis_final_report.html), 
as well of course as the insights gained from this cohort analysis. 






