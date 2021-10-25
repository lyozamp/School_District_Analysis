# Overview of the School District Analysis
The purpose of this analysis was to evaluate the students_complete.csv file because it showed evidence of academic dishonesty at Thomas High School with a focus on 9th grade reading and math grades. While keeping the data intact we were asked to replace the math and reading scores with NaNs which is a way to represent the missing value in data and stands for “Not A Number.” After replacing the scores with NaNs, we repeated the school district analysis by recreating the following criteria:
•	The district summary

•	The school summary

•	The top 5 and bottom 5 performing schools, based on the overall passing rate

•	The average math score for each grade level from each school

•	The average reading score for each grade level from each school

•	The scores by school spending per student, by school size, and by school type 

# Results

## How is the district summary affected?

The data was adjusted to use NaNs which recalculated the percentages for the passing of math, reading and overall. Since the count of students were not adjusted to NaNs, it did not change the total count of students. The change was less than 1% from the original analysis and the challenge analysis, both would round to the same nearest whole number. 

![image](https://github.com/lyozamp/School_District_Analysis/blob/main/images/District_summary.PNG)

## How is the school summary affected?

In the original analysis, the overall passing rate for Thomas High School was concerning to the school board as being too high at a rate of 91%. After removing the 9th grade students from the data and calculating based off of the 10th-12th grade students only the overall passing rate lowered to 65%. 

![image](https://github.com/lyozamp/School_District_Analysis/blob/main/images/School_summary.PNG)

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In the original analysis, the school district was in disbelief that Thomas High School's performance put them in the ranking of 2nd in the district. After adjusting the 9th grade data to be removed, there was a drastic change in the schools ranking putting them from 8th from the bottom and moving their rank towards the middle of the ranking of all the schools.

![image](https://github.com/lyozamp/School_District_Analysis/blob/main/images/ThomasHighSchoolPerformance.PNG)

## How does replacing the ninth-grade scores affect the following:

## Math and reading scores by grade

In the original analysis, the math average was 83.6% and the reading average was 83.7% but after replacing the 9th grade scores using NaN their percentage shows up as "nan" in the code which is why it isn't shown in the chart below. 

![image](https://github.com/lyozamp/School_District_Analysis/blob/main/images/MathReadingScoresByGrade.PNG)

## Scores by school spending

Scores by school spending

Excluding the ninth graders’ math and reading scores from Thomas High School’s data stayed nearly identical because they were nullified from the data.

![image](https://github.com/lyozamp/School_District_Analysis/blob/main/images/ScoresBySchoolSpending.PNG)

## Scores by school size

The overall passing percentage did not change for the school size.

![image](https://github.com/lyozamp/School_District_Analysis/blob/main/images/ScoresBySchoolSize.PNG)

## Scores by school type

Scores by school type were not altered at all.

![image](https://github.com/lyozamp/School_District_Analysis/blob/main/images/ScoresBySchoolType.PNG) 

# Summary
The four major changes I noticed in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs were 
1. Overall Passing Rate changed from 91% to 65% for Thomas High School, which is an extreme difference of 26%. 
2. In the district of 15 campuses, Thomas High School's ranking dropped from 2nd to 8th, a difference of 6 rankings. 
3. The Campuses math and reach averages and passing percentages all had shifts in their rates. 
4. For the 9th grade students at Thomas High School the grade level data will now show "NaN" in reports. 

