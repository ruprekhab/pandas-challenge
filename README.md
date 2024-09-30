# pandas-challenge

Overview


This assignment focuses on analyzing school performance trends using a script that generates several key DataFrames to provide insights. The following DataFrames are created:

District Summary: An overview of the entire school district, including total number of schools and students, total budget, average Math and Reading scores, percentage of students passing Math, Reading, and both subjects.

School Summary: Detailed performance metrics for each school, featuring School name and type (district, charter), total number of students and the budget, budget per student, average Math and Reading scores, percentage of students passing Math, Reading, and both subjects.

Top 5 Performing Schools: A list of the top 5 schools with the highest overall passing percentage.

Bottom 5 Performing Schools: A list of the bottom 5 schools with the lowest overall passing percentage.

Math Scores by Grade: A breakdown of average Math scores by grade (9th, 10th, 11th, and 12th) for each school.

Reading Scores by Grade: A breakdown of average Reading scores by grade (9th, 10th, 11th, and 12th) for each school.

Spending Summary: School performance analysis based on average spending per student, categorized into spending ranges.

Size Summary: Performance breakdown by school size (small, medium, large).

Type Summary: School performance categorized by the type of school (district vs. charter).

Files Included in this Repository: This repository contains the following files:

schools_complete.csv: Information about each school, including its name, type, size, and budget.

students_complete.csv: Student-level data, including name, gender, grade, school, and scores in Math and Reading.

Jupyter Notebook - PyCitySchools_starter.ipynb: The main script for running the analysis and generating the reports.

How to Run the Script:

Ensure that pandas is installed in your Python environment. Place the CSV files (schools_complete.csv and students_complete.csv) in a folder named Resources located in the same directory as PyCitySchools_starter.ipynb.
Open the Jupyter Notebook and run the cells to generate the DataFrames and insights.

Modifying the Script:
If the structure of the CSV files changes (e.g., new columns or modified headers), you will need to adjust the script to accommodate these changes.

School Performance Analysis Report:

1) Top Performing Schools (by Overall Passing Percentage):
   
Charter schools significantly outperform district schools in overall student achievement. The top 5 highest-performing schools are all charter schools. In contrast, the lowest-performing schools are district schools.

2) Impact of Spending on Academic Performance:
   
Interestingly, schools with lower per-student spending tend to achieve better academic outcomes than those with higher budgets. The spending categories analyzed are:

< $585 per student

$585 - $630 per student

$630 - $645 per student

$645 - $680 per student

Schools in the lower spending brackets (below $630 per student) report higher average scores in math and reading, along with a higher percentage of students passing both subjects, compared to schools with higher spending.

3) Performance by School Size:
   
Small (<1,000 students) and medium-sized (1,000-2,000 students) schools demonstrate better academic performance than large schools (2,000-5,000 students). 

4) Performance by School Type:
   
Charter schools, which are generally smaller or medium-sized, outperform district schools in multiple areas, including average math and reading scores, as well as the percentage of students passing both subjects.

Conclusion:

1) Charter schools outperformed district schools across multiple metrics, including overall passing rates, average math, and reading scores.
   
2)Small and medium-sized schools, predominantly charter schools, showed better performance than larger district schools, further supporting the advantage of smaller, more focused learning environments.
