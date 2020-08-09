# School_District_Analysis

## Overview of the school district analysis.

Maria, the chief data scientist for a city school district is responsible for analyzing data from a variety of sources and formats.  In this role she is tasked with preparing all standardized test data for analysis, reporting, and preparing presentations for insight on performance trends and paths. We are helping Maria analyze data on student funding and student standardized test scores.

### Purpose of this analysis.
The purpose of this analysis is to aggregate the data and showcase trends on school performance.  This analysis will assist the school board and superintendent in making decisions concerning the school budgets and priorities. 

The analysis focuses on the following areas:
1. The District Summary - looks at the district overall with information on total number of students, schools, budget, and math and reading standardized test scores.
2. The School Summary - look at school type, number of students per school, school budget, math and math and reading standardized test scores.
3. The Top Five and Bottom Five performing schools based on overall passing rate.
4. The average math and reading scores by grade level for each school.
5. The math and reading scores grouped by spending range per student, school size, and school type.

### Resources
- Software:
    - Jypter Notebook 6.0.3
- Environment:
  - Python 3.7
- Dependencies:
  - Pandas Library 1.0.5
  - NumPy Library 1.17.0

## Results
Originally, we ran analysis on all district school data.  Unfortunately, The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

- How is the school summary affected?
    When excluding the Thomas High School 9th graders data the following were affected:
        - The average math score dropped  
        - The passing math and reading percentages decreased
        - The overall passing percentage decreased
 <img src = "https://github.com/jennfrbrown/School_District_Analysis/blob/master/Images%20for%20ReadMe/District%20Summary.png"  >  
   
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    
    -The Overall Passing Percentage for Thomas High School changed from 91% to 65% and the school rank dropped from 2nd place to 8th place.
<img src = "https://github.com/jennfrbrown/School_District_Analysis/blob/master/Images%20for%20ReadMe/Change%20in%20Position.png" >
    
    
How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade
    - The Math and Reading Scores by grade were not greatly affected.  The only difference is that now instead of showing an average for the 9th grade is shows "nan" for 9th grade in those summary tables.
- Scores by school spending
    -  Thomas High Schools falls into the $630 - $644 spending range per student.  The Average Math and Reading Scores were unaffected.  However, the Passing Math, Passing Reading, and Overall Passing Percentages all decreased.
<img src = "https://github.com/jennfrbrown/School_District_Analysis/blob/master/Images%20for%20ReadMe/Spending%20Ranges.png">

- Scores by school size

    -  Thomas High School falls into the medium size school category.  The Average Math and Reading Scores did not change at all for the Medium Category.  However, the Passing Math, Passing Reading, and Overall Passing Percentages decreased.
<img src = "https://github.com/jennfrbrown/School_District_Analysis/blob/master/Images%20for%20ReadMe/Spending%20Ranges.png" >

- Scores by school type
    - Thomas High School is a charter school  The Average Math and Reading Scores for Chater Schools were unaffected.  However, the Passing Math, Passing Reading, and Overall Passing Percentages decreased.
<img src = "https://github.com/jennfrbrown/School_District_Analysis/blob/master/Images%20for%20ReadMe/school%20type.png"  

## Summary: 

Four of the main changes in the reports once the Thomas High School 9th grade math and reading data were replaced by NaNs are:
1. The overall passing percentage decreased from 65% to 64%.
2. The budget information didn't change, but the scores did because the 9th graders were excluded from the analysis.
3. 
