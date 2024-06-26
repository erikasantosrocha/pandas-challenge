# pandas-challenge
Pandas Challenge

Background
- You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

Instructions
- Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends   based on the data.

The final report should include each of the following:

District Summary
- Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame, including:
    - Total number of unique schools
    - Total students
    - Total budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math and reading)

School Summary
- Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school, including:
    - School name
    - School type
    - Total students
    - Total school budget
    - Per student budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Lowest-Performing Schools (by % Overall Passing)
- Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Math Scores by Grade
- Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
- Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
- Create a table that breaks down school performance based on average spending ranges (per student), including:
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

Scores by School Size
- Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
- Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.