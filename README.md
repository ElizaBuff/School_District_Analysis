# School_District_Analysis

## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with Pandas and Jupyter Notebook 

Pandas is an open-source Berkeley Software Distribution (BSD)-licensed library that provides high-performance data analysis tools for the Python programming language. The Pandas library is one of the most widely preferred tools for data analysis and carries tremendous power in handling large datasets, which can slow down Excel.

It takes a lot of coding to modify and display datasets using only Python. In Jupyter Notebook, you can use the Pandas library, where raw data can be extracted from a variety of sources, cleaned, transformed, manipulated, analyzed, and visualized, all the while leaving the original dataset intact.

Additionally, with Python, you're limited when it comes to using lists, tuples, and dictionaries to manipulate the data. However, Pandas allows Python programmers the ability to work with two data types, Series and DataFrames, which are structured lists with many built-in convenience methods that allow for quick and easy manipulation of data.
### Background of Project
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

Here is the list of deliverables for the analysis of the school district: 

A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size 
School performance based on the type of school
Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.

---
## Results
Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)

Based on the line graph above, I had the following takeways about theather campaigns:
* May, June, and July respectively had the highest number of successful campaigns. 
* October and May respectively had the highest number of failed campaigns.
* December had about as many successful campaigns as failed ones.
* In every month there were more successful than failed campagins. Generally, the successful and failed trend lines create the same shape and are similar to each other with the exception of May, October, and December. In May, the larger than average gap between successful and failed campaigns suggests a better chance for success. In October, the smaller than average gap between successful and failed campaigns suggests a better chance for failure. 


![Outcomes_vs_Goals](Outcomes_vs_Goals.png)



---
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
