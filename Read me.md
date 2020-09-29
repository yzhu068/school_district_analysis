# PyCitySchool Challenge

## Background: 
Maria, the chief data scientist for City School District, is responsible for performing analysis to standardized performance tests in order for the board to decide the strategic investment to each school. 

The performance of each school is judging by percentage of student passing math, reading and both subjects.

An preliminary analysis has been conducted, and it is believe that the grades for Thomas High School 9th graders are not trustworthy. 

 
### Purpose: 
My tasks includes: 
Replace Thomas High School 9th Graders' math and reading scores with "NaN", ie, exclude these scores from analysis;
Calculate the passing math percentage, passing reading percentage, and overall passing percentage for Thomas High School using only 10th, 11th, and 12th grade data;
Run the analysis and see if it makes a difference by getting rid of 9th graders data. 

## Analysis and Challenges

### Results
 How is the district summary affected?
The passing math percentage, passing reading percentage,and overall passing percentage are recalculated by " new student counts", which is total student numbers substracted by the number of Thomas High School 9th graders. the total student number are decreased. 

How is the school summary affected?
It does not affect the school summary significanly if exclude Thomas High School 9th grade students, both grades and students counts, from analysis. The average math and reading score changed a bit but not very much. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

As discussed above, it does not affact very much if student count of Thomas High Scholl is substracted from the total student count. 
However, if the 9th grader student count still counts for the total student analyzed, the average math and reading scores of Thomas High School are significantly lowered, from over 90% to around 65%.

How does replacing the ninth-grade scores affect the following:
*Math and reading scores by grade 
9th grade score for Thomas High School is showing as "NaN". 


##Summary: 
