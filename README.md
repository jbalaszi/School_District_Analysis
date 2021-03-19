# School_District_Analysis
## Background
Use Python to analysis school district performance and understanding how performance affects budget allocation. Further analysis was needed over the student data because of suspected academic dishonesty among one of the high schools. It was brought to the school boards and consulting firm's attention that students_complete.csv shows evidence of altered reading and math scores for nineth graders at Thomas High School. Our firm was hired to analyze this possible data alteration so state testing standards can remain upheld.

This analysis compares previous data analyzation over school district data to help in determining how the suspected academic dishonesty affects school performace.
The following deliverables were requested by the school board:
1. High-level snapshot of district's key metrics (table format)
2. Overview of key metrics for each high school (table format)
3. Tables presenting each of the following metrics:
  -Top and bottom 5 performing schools based on overall passing rate
  -Average Math and Reading scores received by students in each grade in each high school
  -School performance based on budget per student
  -School performance based on school size
  -School performance based on type of school
  
  Pythong and Jupyter Notebooks were used to analyze the following files given to the consulting firm by the school board:
    -schools_complete.csv
    -students_complete.csv
    
## Results
1. District Summary (view image in resources folder)


2. School Summary
(view image in resources folder)


3. Thomas High School:
Math and reading scores for ninth graders at Thomas High School (THS) were replaced with NaN so future performance calculations are not affected.
  -Average math scores for 10th, 11th, & 12th graders at THS are 83.1, 83.5, and 83.5 respectively
  Average reading scores for 10th, 11th, & 12th graders at THS are 84.3, 83.6, and 83.5 respectively
  
-Scores by School Spending:
There are 15 schools in this analyzation:
mean spending $620.07
std 28.54
min spending amount $578.00
max spending amount $655.00
quartiles:
  25% - 591.50
  50% - 628.00
  75% - 641.5
  
Schools that budgeted $551-660 per student appear to have the best-performing students in both math and reading.
(view image in resources folder)

Small- and Medium-sized school districts were very close in performance and outperformed large-sized schools.
(view image in resources folder)

Schools are classified as either district or charter. Charter schools performed better than district schools.
(view image in resources folder)

## Summary
Removing 9th grade student scores from Thomas High School affected the school performance review by:
-Average math scores dropped slightly (<1%)
-Average reading scores not affected
-Percentage of students who passed math and reading dropped slightly (-1%)
-The overall passing rate dropped (-1)

Only Thomas High School scores:
-Percentage of students passing math dropped from 93.2% to 66.9%
-Percentage of students passing reading dropped from 97.3% to 69.7%
-Overall passing rate droppped from 90.9% to 65.1%

Thomas High School rankings:
-THS was dropped from top 5 performing schools
-Wright High School moved into top 5
-Bottom 5 performing schools were unaffected
