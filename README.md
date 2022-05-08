# School_District_Analysis

## Overview of the school district analysis

School Budget using Python and Anaconda
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards 

to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

Two technical analysis deliverables and a written report to present your results. You will submit the following:
* Replace ninth-grade reading and math scores

The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs:

student_data.png

## Results:

* Repeat the school district analysis

 A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
* The district summary
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student, by school size, and by school type

In Steps 1-4, you’ll update the district summary. For this task, you’ll recalculate the total student count by subtracting the number of ninth-grade students in Thomas High School from the total student count, then you'll recalculate the passing math and passing reading percentages, and the overall passing percentage with the recalculated total student count.

District Summary DataFrame 
total_schools.png


In Steps 5-14, you’ll execute the code from this module that creates and formats the School Summary DataFrame, then update the school summary using the 10th-12th graders from Thomas High School

metrics for Thomas High School:

ths.png


new DataFrame named per_school_summary_df. The data and columns of the DataFrame will be:
Type of school in the "School Type" column
Total students per school in the "Total Students" column
Total budget per school in the "Total School Budget" column
Total budget per student for each school in the "Per Student Budget" column
Average math score for each school in the "Average Math Score" column
Average reading score for each school in the "Average Reading Score" column
Percentage of students passing math for each school in the "% Passing Math" column
Percentage of students passing reading for each school in the "% Passing Reading" column
Overall passing percentage for each school in the "% Overall Passing" column

how does school spending per student affect the school's average scores and passing percentages?  

To create this DataFrame, we need to do the following:
Group the schools into four bins, or ranges, based on the budget per student.
For each spending range, get the following data:
Average math and reading scores
The percentage of students passing math and reading
The overall passing percentage, which is the average of the percentage of students passing math and reading

There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data:
How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.