# School_District_Analysis

## Overview of the school district analysis
*   The purpose of this analysis is to statistically define which schools are performing better in math and reading test scores and whether or not budgets, school type, or school size plays a role in outcome of students' test scores.
*   

- Results: Using bulleted lists and images of DataFrames as support, address the following questions.

* How is the district summary affected?
  * By excluding the ninth grade student of Thomas High School, there was a slight decrease in scores district math and reading averages for both math and reading. Listed below is first the new statistics that exclude scores from ninth graders with the second table including the ninth graders. 
![district summary new](https://user-images.githubusercontent.com/95305584/154546690-ec3d075a-61d2-4b4a-acb1-48698a5a7516.png)
![district summary old](https://user-images.githubusercontent.com/95305584/154547688-04c1e4a2-6524-498e-ad6a-9755c6e3ec5d.png)
Interestingly, while there was a drop in the % passing reading section, there was no drop in the actual reading score average itself.

* How is the school summary affected?
  * By sorting by school in the school summary, the only affected row is data for Thomas High School. The budget, total number of schools, and per student budget was unchanged but the scores each took a slight drop. The percentage of students passing both reading and math was 90.948% including ninth grade students and fell 0.318% to 90.62%. The two tables below are the top 5 schools sorted by percent of overall passing with the first table excluding the ninth grade students.
![school summary old (top5)](https://user-images.githubusercontent.com/95305584/154548999-ec4996d2-e0a1-47a4-820d-f7907fa3c47c.png)
![school summary new (top5)](https://user-images.githubusercontent.com/95305584/154549006-c15851a7-5b6c-4bb6-8cdb-ae0c671e1ade.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * There is not a big difference in the scores when the ninth grade students of Thomas High School was removed and therefore their pvearll passing percentage is still second best. However, it is worth noting that their average math score and percent passing reading results dropped below Griffin High School which has the third best OVerall Passing Percentage.

* How does replacing the ninth-grade scores affect the following:
  
* Math and reading scores by grade
  * When looking at reading and math scores by grade by school, there is no change as each schools' students in each grade has scores independent of any other grade or school. The only difference is the lost data from Thomas High School's ninth grade class for both reading and math. When you average ALL ninth graders across all schools, there is little to no difference beacuse the excluded students scored near the average. 
  
* Scores by school spending
  *

* Scores by school size

* Scores by school type

* Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

