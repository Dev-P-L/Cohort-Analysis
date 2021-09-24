# Cohort-Analysis


## Summary

* In the project Recommendation System (see corresponding repository in this account), 
the 10-milllion-row MovieLens data set (see https://grouplens.org/datasets/movielens/ )
has been analyzed. Time impact was a predictor, rather limited though. 

* This project further elaborates on the idea of time impact by investigating 
the notion of cohort behavioral patterns. It analyzes a one-million-row extract 
from the 10-milllion-row MovieLens data set. 

* This allows to deliver additional insights about data time component and users’ behavioral patterns 
and could help to predict ratings when revisiting the Recommendation System project. 

* More explanation is provided in the final report 
70_cohort_analysis_final_report.html, 
as well of course as the insights gained from this cohort analysis. 

* Wishing to visualize 70_cohort_analysis_final_report.html?

  * You could open it in GitHub Desktop.
  
  * Alternatively, you could use the URL https://rawcdn.githack.com/Dev-P-L/Bank-Marketing/17b63a112231f23fa7729ed62b9a5998b0a1adad/Report.html which, when activated, delivers 70_cohort_analysis_final_report.html to the browser with the correct Content-Type headers and not with Content-Type of text/plain. The URL has been obtained by introducing the GitHub URL of 70_cohort_analysis_final_report.html into https://raw.githack.com/ , as suggested in https://stackoverflow.com/questions/6551446/can-i-run-html-files-directly-from-github-instead-of-just-viewing-their-source .

 * Alternatively again, you could knit 69_cohort_analysis_final_report.Rmd or ask me by email for a copy of 70_cohort_analysis_final_report.html.



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

### PostgreSQL with the IDE pgAdmin and Excel
* Data import, database management and data wrangling 
have been performed in PostgreSQL with the IDE pgAdmin. 
* The database cohort-analysis has been created in PostgreSQL. 
* Cohort analysis has been conducted in PostgreSQL as well 
but also in Excel with pivot tables.
* Visualization has been performed in Excel. 

### R Markdown
The final report 70_cohort_analysis_final_report.html
has been produced in R Markdown by knitting the file 69_cohort_analysis_final_report.Rmd. 

### CSV files and LibreOffice Calc
* Input data are stored in the zipped CSV file 01_data_import_from_recommendation_project.zip. 
* Data have also been transferred in CSV format between SQL, Excel and R Markdown. 
* CSV files have been produced in Calc from LibreOffice (for technical convenience with decimal separator). 

### Graphs in PNG format
Graphs have been transferred in PNG format. 
