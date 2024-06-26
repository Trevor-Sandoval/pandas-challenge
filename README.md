# pandas-challenge


## PLEASE NOTE that my script can be found in the file entitled "Main.ipynb"


BACKGROUND: 
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities. As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.


INSTRUCTIONS: 
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.

DISTRICT SUMMARY:
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:
Total number of unique schools,
Total students,
Total budget,
Average math score,
Average reading score,
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

SCHOOL SUMMARY:
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


HIGHEST=PERFORMING SCHOOLS (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".


LOWEST-PERFORMING SCHOOLS (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".


MATH SCORES BY GRADE:
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.


READING SCORES BY GRADE:
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.


SCORES BY SCHOOL SPENDING:
Create a table that breaks down school performance based on average spending ranges (per student).
Use the code provided below to create four bins with reasonable cutoff values to group school spending
Use pd.cut to categorize spending based on the bins.
Use the following code to then calculate mean scores per spending range.


Use the scores above to create a DataFrame called spending_summary.
Include the following metrics in the table:
Average math score,
Average reading score,
% passing math (the percentage of students who passed math),
% passing reading (the percentage of students who passed reading),
% overall passing (the percentage of students who passed math AND reading)


SCORES BY SCHOOL SIZE:
Use the following code to bin the per_school_summary. Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).


SCORES BY SCHOOL TYPE:
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
This new DataFrame should show school performance based on the "School Type".


References: Please note that some portions of my code's structure were inspired by my research on the internet in addition to the hyperlinked module resources emailed to us by Melissa Conner. At the beginning of this boot camp, we were encouraged to be proactive with utilizing the internet as a resource for finding solutions to complex problems that also contributed to our edification. Thus, I was able to formulate my assignment after conducting some independent research on Stack Overflow and Google Search.
