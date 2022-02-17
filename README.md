# School District Analysis

## Overview of the school district analysis
The purpose of this analysis is to statistically determine how the data would change by removing the ninth grade students from Thomas High School from the school district data. 


### Results: Using bulleted lists and images of DataFrames as support, address the following questions.


* By excluding the ninth grade student of Thomas High School, there was a slight decrease in scores district math and reading averages for both math and reading. Listed below is first the new statistics that exclude scores from ninth graders with the second table including the ninth graders. 
![district summary new](https://user-images.githubusercontent.com/95305584/154546690-ec3d075a-61d2-4b4a-acb1-48698a5a7516.png)
![district summary old](https://user-images.githubusercontent.com/95305584/154547688-04c1e4a2-6524-498e-ad6a-9755c6e3ec5d.png)
Interestingly, while there was a drop in the % passing reading section, there was no drop in the actual reading score average itself.


* Sorting by school in the school summary, the only affected row is data for Thomas High School. The budget, total number of schools, and per student budget was unchanged but the scores each took a slight drop. The percentage of students passing both reading and math was 90.948% including ninth grade students and fell 0.318% to 90.62%. The two tables below are the top 5 schools sorted by percent of overall passing with the first table excluding the ninth grade students.
![school summary old (top5)](https://user-images.githubusercontent.com/95305584/154548999-ec4996d2-e0a1-47a4-820d-f7907fa3c47c.png)
![school summary new (top5)](https://user-images.githubusercontent.com/95305584/154549006-c15851a7-5b6c-4bb6-8cdb-ae0c671e1ade.png)

* There is not a big difference in the scores when the ninth grade students of Thomas High School was removed and therefore their ovearll passing percentage is still second best. However, it is worth noting that their average math score and percent passing reading results dropped below Griffin High School which has the third best OVerall Passing Percentage.
  
* Math and reading scores by grade
  * When looking at reading and math scores by grade by school, there is no change as each schools' students in each grade has scores independent of any other grade or school. The only difference is the lost data from Thomas High School's ninth grade class for both reading and math. When you average ALL ninth graders across all schools, there is little to no difference beacuse the excluded students scored near the average. 
  
* Scores by school spending
  * In terms grouping the scores by school spending, there is no significant difference. The formatted table below is exactly the same regardless of the inclusion on Thomas High School ninth graders.
![scores by school spending per student (old)](https://user-images.githubusercontent.com/95305584/154577485-143040d0-25fb-4178-aa69-ce8f2995311f.png)

* Scores by school size
  * There are 1,635 students at Thomas High School. In the following table, they are placed in the "Medium (1000-2000)" bin and thus only that row of data would chage. Because there is such a small decrease in scores, the percentages and averages shown here are unchanged when rounding to the nearest 10th. 
![scores by school size (old)](https://user-images.githubusercontent.com/95305584/154578130-c47b6dff-5b9e-45a3-91ca-4422ca55a03d.png)

* Scores by school type
  * Lastly, when comparing the two types of school (district or charter), it is clear that the values for the 5 statistics shown in the previous table won't change. There is a larger number of students in either row than in any individual school. This results in a lower impact on the statistics by removing the ninth grade students' math and reading test results. The table below shows the results.
 ![scores by school type (old)](https://user-images.githubusercontent.com/95305584/154578626-150ed1c3-b0ce-494f-b9fa-a0725f51796f.png)

### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
4 changes that occured in the data are as follows:
1. The statistics for Thomas High School overall changed in a negative fashion. The average math scores and % of students passing math dropped. By default, those students who passed both math and reading tests also dropped.
2. The ninth garde average across all schools dropped, albeit minimally given the size of 15 combined 9th grade classes.
3. The scores by school spending was adjusted to be lower, meaning that at the dollar per student spent for the school's budget, a slightly lower score was associated with the per student budget. 
4. The overall district analysis showed a slight descrease in performance across the math and reading test scores and passing rates.
