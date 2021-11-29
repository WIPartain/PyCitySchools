# PyCitySchools

## Overview
After discovering evidence of acadmic dishonesty in regards to the math and reading grades for Thomas High School's ninth grade class, we have been asked to replace their test scores with NaN while keeping the rest of the data intact. After replacing the data, we needed to run another analysis to see how those test results affected the districts test scores as a whole
## Purpose of the Analysis
This analysis is designed to help us practice our use of pandas in the Python programming language.  We also had the opportunity to demonstrate several new functions like groupby(), loc, append, sort_values, etc.
## Analysis of Metrics
  * The district summary
      After removing the Thomas High School 9th grade scores in question, we were able to determine that there was a very small impact on the math, reading, and overall passing percent of the district. All 3 categories dropped by roughly 1%.
  * The school summary
      The school summary dataframe reveals the passing math percentage and passing reading percentage both dropped dramatically for Thomas High School.  Reading dropped from 97.1% to 69.7% while math dropped from 93.3% down to 66.9%.
  * The top 5 and bottom 5 performing schools, based on the overall passing rate
      The drop in the passing reading and math percentages dropped Thomas High School from second in overall passing percentage down to eighth.  This did not affect the bottom five in either analysis.
  * The average math score for each grade level from each school
      Since the  math scores for Thomas High Schools 9th grade class were isolated using the NaN function, they did not affect the scores for the other grade levels at Thomas High School nor did it affect any grades at any of the other schools in the district.
  * The average reading score for each grade level from each school
      As with the math scores, the average reading scores for the other grades at Thomas High School were not affected nor were the other schools in the district.
  * The scores by school spending per student, by school size, and by school type
      When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, this data change did impact the spending ranges for passing percentages. According to the summary above, there was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 6% decrease in % overall passing in the $630-644 spending range.
      When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).
      In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.
## Summary
We were able to isolate the instances of academic dishonesty at Thomas High School, and they did in fact cause discrepencies in the school's and the district's overall passing rate for math and reading. This in turn affected the spending, size, and type summaries connected to the passing percentage for math and reading for Thomas High School.
