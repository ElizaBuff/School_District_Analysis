# School District Analysis

## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with many features of Pandas in Jupyter Notebook including: replace substrings, use logical operaters to select specific data from a DataFrame column, merge DataFrames, format and reorder columns, set the index, create Series using the groupby() function, combine Series into a DataFrame, create and categorize bins and create DateFrames by group. 


### Background of Project
Following the district wide standardized math and reading exames, a school board has asked for the following list of deliverables for the analysis of the school district: 
* Math and Reading Scores by Grade
* Scores by School Spending
* Scored by School Size
* Scores by School Type 

Then, the school board is notified that there has been evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. To do this, the ninth grade math and reading scores for Thomas High School have been replaced with NaNs while keeping the rest of the data intact. 

Finally, the same school district analysis is repeated with the updated data along with a report to describe how these changes affected the overall analysis.

---
## Results
These results explain how the updated data, removing Thomas High School's nineth grade, affected the overall analysis.

**How is the district summary affected?:** Overall, the percentage of students passing math and reading exames decreased. This meant that the district has a passing percentage of 64.9%. 
* Math decreased 0.3%
* Reading decreased 0.2%
* Overall Passing decreased 0.1% 

![U_District_Summary](U_District_Summary.png)

**How is the school summary affected?:** The only change to the school summary math and reading reports is that Thomas High School 9th grade results now read *"nan"* instead of 83.% in math and 83.7% in reading. 

**Math Breakdown by School** 

![U_Math](U_Math.png)

**Reading Breakdown by School**

![U_Reading](U_Reading.png)


**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**


**How does replacing the ninth-grade scores affect the following:**
* Math and reading scores by grade
* Scores by school spending 
* Scores by school size
* Scores by school type

Original By School Size
![O_By_SchoolSize](O_By_SchoolSize.png)

Original By School Type
![O_By_SchoolType](O_By_SchoolType.png)

Original By Spending
![O_By_Spending](O_By_Spending.png)

Original Math Breakdown
![O_Math](O_Math.png)

Original Reading Breakdown
![O_Reading](O_Reading.png)

---
Updated By School Size
![U_By_SchoolSize](U_By_SchoolSize.png)

Updated By School Type
![U_By_SchoolType](U_By_SchoolType.png)

Updated By Spending
![U_By_Spending](U_By_Spending.png)

Updated Math Breakdown
![U_Math](U_Math.png)

Updated Reading Breakdown
![U_Reading](U_Reading.png)

Based on the line graph above, I had the following takeways about theather campaigns:
* May, June, and July respectively had the highest number of successful campaigns. 
* October and May respectively had the highest number of failed campaigns.
* December had about as many successful campaigns as failed ones.
* In every month there were more successful than failed campagins. Generally, the successful and failed trend lines create the same shape and are similar to each other with the exception of May, October, and December. In May, the larger than average gap between successful and failed campaigns suggests a better chance for success. In October, the smaller than average gap between successful and failed campaigns suggests a better chance for failure. 




---
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
