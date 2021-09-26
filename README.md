# School District Analysis

## Overview 
The school board has notified Maria and her supervisors about an academic dishonesty. With the help of Jupyter Notebook and Pandas we were able to analyze standardized test data for proper examination of fowl play. Analysis was conducted via multiple cross-examinations of dataframes showing school trends based on performance and spending and student population. 

## Results and Analysis
After performing the task of cleaning up the school and student scores and data, there were some changes to the previous data:
-District summary was affected  slighltly by dropping at about ~ 0.1 in the average math scores while the percentage results for both math, reading, and overall passing were lower than the stated by 0.2%, 0.3%, and 0.1%, respectively.
-Replacing the ninth graders’ math and reading scores had no effecct to Thomas High School’s performance relative to the other schools. They were still ranked 2nd in their district. Since the change in data is less than 1%, it can be concluded that the change is insignificant overall. 
-School summary amongst all the schools were relatively the same with the exception of the math and reading score averages and the percentages. From the referenced images, you can see the highlighted section where the scores that were inconsistent.

![Before Manipulation](https://user-images.githubusercontent.com/89143725/134792785-4dcee267-66f9-41b4-98cf-25c7d25c2123.png)
![After Manipulation](https://user-images.githubusercontent.com/89143725/134792786-4342ce68-6730-4231-b39c-b495ccda8176.png)
(The images reference the 3 categories before and after where the percentages dropped over 25%, after the 9th grade scores were removed from data calcultion.)

Futher analysis entailed how manipulating ninth-grade scores affected comprehension scores by grade, scores by school spending, scores by school size and type. It was observed  after removing the 9th grade scores the math and reading scores by grade does not make any change to the data, other than having no results in the 9th grade THS cell. All other scores by grade and school remained the same after data manipulation. Replacing the 9th grade results caused the scores by school spending to change the two middle bin results, $585-629 and $630-644, and brought both of the averages and all the passing percentages up. Replacing the 9th grade results made no changes to the final two dataframes, scores by school size and scores by school type. All averages and percentages were the same after the removal of 9th graders.

## Summary
There were many changes/manipulations that had to be done in this challenge. The first major change to this analysis was to replace math and reading scores for Grade 9 students at Thomas High School, but this returned many other notable scores. The district's success rate was lowered, but not significantly. School summaries were most affected as passing rates for Thomas High School were drastically reduced after recalculation and, finally, pooled scores by school fees were most affected when the mean and rate were highest. All in all these changes are quite large, mainly in Thomas High School pass rates, it is recommended to repeat these tests as the results can significantly influence budget decisions. 
