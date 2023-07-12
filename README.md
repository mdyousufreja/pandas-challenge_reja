# pandas-challenge_reja

**Background**


You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.


**Before You Begin**

  1. Created a new repository for this project called pandas-challenge.

  2. Cloned the new repository to your computer.

  3. Inside my local Git repository, created a folder for this homework assignment and name it PyCitySchools.

  4. Added your Jupyter notebook to this folder. This is the main script to run for analysis.

  5. Pushed these changes to GitHub or GitLab.


**Files**


Downloaded the following files to get started:

Module 4 Challenge [files](https://courses.bootcampspot.com/courses/3819/assignments/56672?module_item_id=999456)


**Instructions**


Using Pandas and Jupyter Notebook, created a report that includes the following data. 
**Hint**: Check out the sample solution called PyCitySchools_starter.ipynb located in the .zip file to review the desired format for this assignment.

**District Summary**

Performed the necessary calculations and then created a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

- Total number of unique schools

- Total students

- Total budget

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)


School Summary
Performed the necessary calculations and then created a DataFrame that summarizes key metrics about each school.

Include the following:

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

**Highest-Performing Schools (by % Overall Passing)**

Sorted the schools by **% Overall Passing** in descending order and display the top 5 rows.

Saved the results in a DataFrame called "top_schools".

**Lowest-Performing Schools (by % Overall Passing)**

Sorted the schools by **% Overall Passing** in ascending order and display the top 5 rows.

Saved the results in a DataFrame called "bottom_schools".

**Math Scores by Grade**

Performed the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Reading Scores by Grade**

Created a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

**Scores by School Spending**

Created a table that breaks down school performance based on average spending ranges (per student).

Used the code provided below to create four bins with reasonable cutoff values to group school spending.

Used pd.cut to categorize spending based on the bins.

Use the following code to then calculate mean scores per spending range.

Used the scores above to create a DataFrame called **spending_summary**.

Included the following metrics in the table:

- Average math score

- Average reading score

- % passing math (the percentage of students who passed math)

- % passing reading (the percentage of students who passed reading)

- % overall passing (the percentage of students who passed math AND reading)

**Scores by School Size**

Used the following code to bin the **per_school_summary**.




