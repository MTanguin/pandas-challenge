#### "Exploring School Data to Drive Educational Excellence"
Pandas | Jupyter Notebook | Creating DataFrames | Data | Functions | Column Manipulation | Pandas Reading Files | loc &amp; iloc | Cleaning Data | Group By | Sorting, Merging, Binning, Mapping &amp; Debugging 

# Background

The education sector relies on data analysis to gain insights and make informed decisions. In this project, we utilize the power of Pandas and Jupyter Notebook to analyze school data and generate comprehensive reports. The dataset includes information on various metrics such as school budgets, student scores, passing rates, and school types. By leveraging data analysis techniques, we aim to provide valuable insights into school performance, spending patterns, and the impact of school size and type on academic outcomes.

# Objectives

•	Analyze the district-wide standardized test results to help make strategic decisions regarding future school budgets and priorities.
•	Aggregate the data to display obvious trends in school performance.


# Methods

1. District Summary: We calculate key metrics for the entire school district, including the total number of schools, total student count, overall budget, average math and reading scores, and the percentage of students passing math, reading, and overall.

2. School Summary: We generate a summary DataFrame that provides an overview of each school's performance. The metrics include the school name, school type, total student count, school budget, budget per student, average math and reading scores, and the percentage of students passing math, reading, and overall.

3. Highest-Performing and Lowest-Performing Schools: We identify the top five schools with the highest percentage of overall passing rates and the bottom five schools with the lowest percentage of overall passing rates, showcasing the disparities in school performance.

4. Math and Reading Scores by Grade: We create separate DataFrames to display the average math and reading scores for each grade level (9th, 10th, 11th, and 12th) at each school, providing insights into grade-level performance trends.

5. Scores by School Spending: We categorize schools based on their average spending ranges per student and analyze the corresponding average math and reading scores, percentage of students passing math and reading, and overall passing rates. This allows us to understand the relationship between school spending and academic performance.

6. Scores by School Size: We categorize schools into small, medium, and large based on their total student count. By analyzing the average math and reading scores, percentage of students passing math and reading, and overall passing rates for each school size category, we can uncover trends related to school size and academic achievement.

7. Scores by School Type: Using the school type information, we examine the average math and reading scores, percentage of students passing math and reading, and overall passing rates for each school type, providing insights into the impact of school type on academic outcomes.

By following these methods, we aim to gain a comprehensive understanding of school performance, identify trends, and provide actionable insights to improve educational outcomes.

# Analysis

1.	Based on the outcome, the highest performing school by school type is charter schools and the bottom five are district schools.

2.	School size with less than one thousand (>1000) students has the highest overall passing rate for 90.14
The school size affects the student’s performance. The bigger the class size the lower the overall passing rate.

3.	Overall, charter schools outperformed the district schools by garnering an overall passing rate of 90.56, way too above from 53.69 overall passing rate of district schools.

### Source:
https://courses.bootcampspot.com/courses/2799/assignments/42944?module_item_id=802839
