# School_District_Analysis

## Overview of the school district analysis

The purpose of this analysis was to check evidence of academic dishonesty in the School Report using Python and Anaconda. The school board has notified  that there are evidence of academic dishonesty: reading and math grades for Thomas High School ninth graders appear to have been altered. 

For this purpose we replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. After we’ve replaced the math and reading scores, we repeated the school district analysis that we previously did and checked how these changes affected the overall analysis.

The reading and math scores for the ninth graders in Thomas High school were replaced with NaNs:

![student_data.png](/Resources/student_data.png) 

## Results:

We repeated the school district analysis, and for that overviewed of the key metrics for each school, presented in a table format.
Tables was presenting each of the following metrics:
* The district summary
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student and by school size

In Steps 1-4, we updated the district summary. For this task, we recalculated the total student count by subtracting the number of ninth-grade students in Thomas High School from the total student count, then we recalculated the passing math and passing reading percentages, and the overall passing percentage with the recalculated total student count.

We've got the District Summary DataFrame:  
![total_schools.png](/Resources/total_schools.png) 

In Steps 5-14, we executed the code that creates and formats the School Summary DataFrame, then updated the school summary using the 10th-12th graders from Thomas High School. The purpose was to discover how replacing the ninth graders’ math and reading scores affects Thomas High School’s performance.

We've got the following metrics for Thomas High School:
![ths.png](/Resources/ths.png) 

The data and columns of the DataFrame per school was following:
* Type of school in the "School Type" column
* Total students per school in the "Total Students" column
* Total budget per school in the "Total School Budget" column
* Total budget per student for each school in the "Per Student Budget" column
* Average math score for each school in the "Average Math Score" column
* Average reading score for each school in the "Average Reading Score" column
* Percentage of students passing math for each school in the "% Passing Math" column
* Percentage of students passing reading for each school in the "% Passing Reading" column
* Overall passing percentage for each school in the "% Overall Passing" column

### Affecting the District summary:

Replacing the Thomas High School’s ninth graders’ math and reading scores has an almost negligible but negative impact nonetheless on the overall district summary. The average math for eg. dropped from 78.98 to 78.90. Because the overall changes are minimal after the 9th grade scores have ben removed, it is safe to say that the overall district summary was not hugely impacted.

### Affecting the School summary:

Replacing the Thomas High School’s ninth graders’ math and reading scores caused dropping average math scores from 83.86 to 83.35, and average reading scores was inreased from 83.85 to 83.90, so we cannot consider it as big impact as well. Considering that after replasing the Thomas High School’s ninth graders’ math and reading scores with NaN rading score increased, we probably cannot see it as evidence of academic dishonesty.

### Affecting math and reading scores by grade: 

The only difference now between the scores is that under 9th graders who attended Thomas High School it shows an NaN.

### Affecting scores by school spending: 

THS is in school spending bin $631-645, the numbers stay nearly identical since the 9th graders are nullified from the statistics:
before it was 78.5	and 81.6 for math and reading score, after it appeared 79.1	and 81.9

### Affecting scores by school size:

THS is in school size bin Medium (1000-2000). Overall passing percentage does not change: before it was 83.4	and 83.9	for math and reading score, after it appeared the same, 83.4 and	83.9 for that.

### Affecting scores by school type:

Scores by school type are not altered at all.

## Summary: 

After reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs we learned that not much has changed. 
We have nullified the values that we felt would alter spending, size and types the schools.
