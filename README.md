# pandas-challenge

1. Create report with at least two observable trends based on the data.

2. District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

3. School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

4. Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".

5. Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".

6. Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

7. Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

8. Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Use the code provided below to create four bins with reasonable cutoff values to group school spending.
Use pd.cut to categorize spending based on the bins.
Use the following code to then calculate mean scores per spending range.
Use the scores above to create a DataFrame called spending_summary.

9. Scores by School Size
Use the following code to bin the per_school_summary.
Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.
Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

10. Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
This new DataFrame should show school performance based on the "School Type".
