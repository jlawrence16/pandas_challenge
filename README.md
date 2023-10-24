# pandas_challenge

I was asked to analyze the school's district-wide standardized test results. I was given access to every student's math and reading scores, as well as various information on the schools they attend. My task was to aggregate the data to showcase obvious trends in school performance.

District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

Total number of unique schools 
Total students
Total budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Include the following metrics in the table:

Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

Scores by School Size

Create a DataFrame that breaks down school performance based on school size (small, medium, or large).

Scores by School Type

This new DataFrame should show school performance based on the "School Type"

---------------------------------
I received hekp from TA / AskBCS with one line of code (line 79)
school_types = school_data.set_index(["school_name"])["type"]
I was trying to pull the same information of data that was alreafy grouped.
---------------------------------


