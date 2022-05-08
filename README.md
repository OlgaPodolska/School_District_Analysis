# School_District_Analysis
School Budget using Python and Anaconda


* A high-level snapshot of the district's key metrics, presented in a table format
* An overview of the key metrics for each school, presented in a table format
* Tables presenting each of the following metrics:
    * Top 5 and bottom 5 performing schools, based on the overall passing rate
    * The average math score received by students in each grade level at each school
    * The average reading score received by students in each grade level at each school
    * School performance based on the budget per student
    * School performance based on the school size 
    * School performance based on the type of school

The school district summary will be a high-level snapshot of the district's key metrics:
* Total number of students
* Total number of schools
* Total budget
* Average math score
* Average reading score
* Percentage of students who passed math
* Percentage of students who passed reading
* Overall passing percentage
We'll find this information and visualize the data with a table like the following:

To get the percentage of students who passed math and reading, we will write code to:
* Determine the passing grade.
* Get the number of students who passed math and reading in separate DataFrames.
* Calculate the number of students who passed math and reading.
* Calculate the percentage of students who passed math and reading.
* To get the overall passing percentage, we will write code to:
* Get the number of students who passed both math and reading in a DataFrame.
* Calculate the number of students who passed both math and reading.
* Calculate the percentage of students who passed both math and reading.

This next project requires you to get the following key metrics for each school and place them in a school summary DataFrame. As a reminder, here are the key metrics you're working with: 
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math
% passing reading
% overall passing

 # To get the passing percentages, we need to:
 # 1. Determine what is the passing grade.
 # 2. Get the number of students who passed math and reading.
 # 3. Get the students who passed math and passed reading

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
