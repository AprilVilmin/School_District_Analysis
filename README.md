# PyCity School District Analysis with Pandas

## Overview of the school district analysis:
This project is responsible for analzing test score information for standardized tests for both charter and district schools for the PyCity School District. The request is for all levels of data analysis including reporting and presentation. The data for this project is coming from several sources. The information gathered through this project/analysis will be used by the school board and other school district leaders to make decisions on spending, staffing and more. The more information the school district has the better strategically informed decisions they can make. 

### Explain the purpose of this analysis
The PyCity School District School Board believes that the students_complete.csv file displays evidence of cheating for ninth graders at Thomas High School. The School Board does not want these scores to diminish the integrity of state standardized testing. For this reason the school board has requested that the reading and math scores for students at Thomas High School be replaced with NaNs and that the rest of the analysis be reran.

## Results: 

- ### How is the district summary affected?
At the district level the student count and the budget metrics do not change. But the the majority of metrics pertaining to the math and reading scores for the state standardized testing show slight decreases due to removing the ninth grade test scores from Thomas High School. The difference is more obvious before some of the formatting takes place. Please note that the screenshots below are formatted differently as one is formatted per the specifications in the module and one per the specifications in the challenge. This is why there is a decimal difference between the screenshots.

#### Before

![District Summary Before.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/District%20Summary%20Before.png)

### After

![District Summary After.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/District%20Summary%20After.png)

- ### How is the school summary affected?
The only changes on this were for Thomas High School which is what is expected is this was the only thing that was replaced with NaN when the new analysis was completed. The total students and school budget metrics for Thomas High School Remained the same when all of the other metrics for this high school changed on the School Summary data frame.

#### Before

![new school summary before.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/new%20school%20summary%20before.png)

#### After

![new school summary after.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/new%20school%20summary%20after.png)

- ### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Repacing the nith graders math and reading scores caused Thomas High School to drop from first place to third place for the percentage of students who passed reading metric, but they remained in seventh place for math and second place for highest overall percentagein both reading and math. Please see the screenshots below.

- ### How does replacing the ninth-grade scores affect the following:
As is shown in the screenshots below, not all schools are affected by the data for ninth graders at Thomas high school beeing updated. 
- #### Math and reading scores by grade:
##### Math

###### Before
![New Math Scores by Grade.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/New%20Math%20Scores%20by%20Grade.png)

###### After
![New After Math Score by grade.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/New%20After%20Math%20Score%20by%20grade.png)

##### Reading 

###### Before

![New Reading Scores by Grade.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/New%20Reading%20Scores%20by%20Grade.png)

###### After

![New After Reading Score by Grade.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/New%20After%20Reading%20Score%20by%20Grade.png)


- #### Scores by school spending:
##### Math & Reading

###### Before
![Spending Randges Before.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/Spending%20Ranges%20Before.png)

###### After
![Spending Ranges After.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/Spending%20Ranges%20After.png)


- #### Scores by school size:
The removal of values for ninth graders at Thomas High School does not appear to have a significant affect on the math and reading scores by school size as is illustrated in the screenshots below. The scores stay stagnant at the level shown.
##### Math & Reading

###### Before
![By School Size Before.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/By%20School%20Size%20Before.png)

###### After
![By School Size After.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/By%20School%20Size%20After.png)


- #### Scores by school type:
The removal of values for ninth graders at Thomas High School does not appear to have a significant affect on the math and reading scores by school type as is illustrated in the screenshots below. The scores stay stagnant at the level shown.

##### Math & Reading

###### Before
![By School Type Before.png](https://github.com/AprilVilmin/School_District_Analysis/blob/main/By%20School%20Type%20Before.png)

###### After
![By School Type After](https://github.com/AprilVilmin/School_District_Analysis/blob/main/By%20School%20Type%20After.png)

## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
