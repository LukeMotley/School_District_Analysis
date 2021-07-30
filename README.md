# School_District_Analysis

## Overview
This analysis uses many metrics of high schools and their students to look for patterns in relation to students math and reading standardized test scores. All of the schools are a part of the same school district. These patterns are to be explored for the school board and superintendent to make better decisions for the district such as allocation of funds.

Midway through this analysis, it was made aware that a portion of the data may be incorrect due to a case of academic dishonesty. Because of this, the ninth grade class from Thomas High School have been removed from the study. 

## Results
* How is the district summary affected?: Average Math scores went down .1%, Average Reading scores did not change, % Passing Math went down .2%, % Passing Reading went down .3%, and % Overall Passing wen down .9%.
* How is the school summary affected? All metrics of measuring Math and Rading Scores went down.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? Because of the acadmeic dishonesty and all the ninth graders test scores not being factored into the schools measurements, the entire school saw a drop in scores across all metrics when compared to other schools.
* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade:  9th graders in Thomas High School received a NaN. 
  * Scores by school spending: The range $630-644 saw a decrease in passing since Thomas High School was in that category.
  * Scores by school size: Similar to spending, the "Medium (1000-2000)" category saw a decrease in passing since Thomas High School was in that category.
  * Scores by school type: Like the previous two, Thomas High School caused the "Charter" category to lower passing percentages.

### District Summary
### Old
![image](https://user-images.githubusercontent.com/85656361/127672978-0101c41a-a1db-45c0-8037-e964dcbb1c6b.png)
### New
![image](https://user-images.githubusercontent.com/85656361/127673047-9af82333-96b7-4869-8978-62e7da059bab.png)
### School Summary
### Old
![image](https://user-images.githubusercontent.com/85656361/127672776-d0d44851-5662-49f0-9ac5-c8262d73498a.png)
### New
![image](https://user-images.githubusercontent.com/85656361/127672164-71f86c07-26d6-4573-8801-ac666a47b10f.png)

## Summary
Because of the large dataset, the change of the 9th graders did not affect numbers by a large degree. The change was much greater within the school itself rather than the entire district. It effected every data frame that was created to look at Scores in relation to some other metric. Every group that Thomas High School was a part of was lowered by it being a part of the group.
