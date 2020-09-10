# PyCity Schools Analysis

![Education](../Images/education.png)

In my latest role, I've become the Chief Data Scientist for my city's school district. In this capacity, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, I've been asked to analyze the district-wide standardized test results. I'll be given access to every student's math and reading scores, as well as various information on the schools they attend. My responsibility is to aggregate the data to and showcase obvious trends in school performance.

My report includes the following:

### District Summary

* Create a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### School Summary

* Create an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Top Performing Schools (By Passing Rate)

* Create a table that highlights the top 5 performing schools based on Overall Passing Rate. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Bottom Performing Schools (By Passing Rate)

* Create a table that highlights the bottom 5 performing schools based on Overall Passing Rate. Include all of the same metrics as above.

### Math Scores by Grade\*\*

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)

### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).

## What are the trends?


District Summary:
With the overall look at this district, the average reading and math scores (81 and 78) are pretty close but percentage wise it's 10% apart(85% and 74%).

School Summary:
The budget per student hovers around 580 and 655. It also appears that the school budget and student population are proportional. More students means more money. Another observation to note is that schools like Wilson High School has a lower budget per student (578) while schools like Griffin High School has a higher budget per student (625).

Top & Bottom Performing Schools:
The top performing schools have a lower student populaiton and a corresponding lower budget. Most of the students have about the same average reading and math score and most of the students pass overall with about 95%. The bottom performing schools have a higher student population, higher budget, and math scores are on a barely passing end with only 60% of the student population are passing overall. So with this in mind, it aligns with the popular notion that smaller classes could be a great benifit to students.

Math & Reading Scores by Grade:
Overall, math scores have a larger range amongst all schools. However, the scores are dignificantly more narrowed within each school. The score margin is much smaller across all schools which indicates that students have a uniform reading comprehension. In closing, there seems to be a strong link between test scores and school grades.

Scores based on Spending per Student, School Size, and School Type:
For spending and population we see here that there's a link between lower spending, lower school size, and higher test scores. The scores are also consistant with what has been seen so far in that reading scores are higher than math scores. In addition, students in charter schools have higher scores on average compared district schools.


<hr>
### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
