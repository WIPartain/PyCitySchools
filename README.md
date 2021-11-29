# PyCitySchools

## Overview
After discovering evidence of acadmic dishonesty in regards to the math and reading grades for Thomas High School's ninth grade class, we have been asked to replace their test scores with NaN while keeping the rest of the data intact. After replacing the data, we needed to run another analysis to see how those test results affected the districts test scores as a whole
## Purpose of the Analysis
This analysis is designed to help us practice our use of pandas in the Python programming language.  We also had the opportunity to demonstrate several new functions like groupby(), loc, append, sort_values, etc.
## Analysis of Metrics
 
 
  * The district summary
  ![](https://github.com/WIPartain/PyCitySchools/blob/main/Resources/Module4DistSumNew.png)
      After removing the Thomas High School 9th grade scores in question, we were able to determine that there was no major impact on the districts grades as a whole.
      
  * The school summary.
  ![](https://github.com/WIPartain/PyCitySchools/blob/main/Resources/schoolsnew.png)
      The school summary dataframe reveals the passing math percentage and passing reading percentage both dropped dramatically for Thomas High School.  Reading dropped from 97.1% to 69.7% while math dropped from 93.3% down to 66.9%.
   
  * The top 5 and bottom 5 performing schools, based on the overall passing rate
      The drop in the passing reading and math percentages dropped Thomas High School from second in overall passing percentage down to eighth.  This did not affect the bottom five in either analysis.
       
  * The average math score for each grade level from each school
  ![](https://github.com/WIPartain/PyCitySchools/blob/main/Resources/avgmathnew.png)   
      Since the  math scores for Thomas High Schools 9th grade class were isolated using the NaN function, they did not affect the scores for the other grade levels at Thomas High School nor did it affect any grades at any of the other schools in the district.
  * The average reading score for each grade level from each school
  ![](https://github.com/WIPartain/PyCitySchools/blob/main/Resources/avgreadingnew.png)
      As with the math scores, the average reading scores for the other grades at Thomas High School were not affected nor were the other schools in the district.
  * The scores by school spending per student, by school size, and by school type
  ![](https://github.com/WIPartain/PyCitySchools/blob/main/Resources/spendingnew.png)
  ![](https://github.com/WIPartain/PyCitySchools/blob/main/Resources/sizenew.png)
  ![](https://github.com/WIPartain/PyCitySchools/blob/main/Resources/typenew.png)
    * When reviewing the School Spending summary, the omission of the THS ninth grade scores did not appear to cause any major changes in the data frame. 
    * In reference to spending by school size, removing the ninth grade scores did not affect the percentage passing for math, reading, and overall in differently sized schools.
    * In School Types summary dataframe was also not affected by the omission of the THS ninth grade test scores.
## Summary
We were able to isolate the instances of academic dishonesty at Thomas High School, and they did in fact cause discrepencies in the school's and the district's overall passing rate for math and reading. This in turn should have affected the spending, size, and type summaries connected to the passing percentage for math and reading for Thomas High School however my algorithm did not return any changes. 
