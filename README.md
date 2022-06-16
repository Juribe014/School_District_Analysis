# School_District_Analysis

# Overview of the school district analysis
For this analysis, data that is suspected of being altered will be analyzed. The suspected data will be removed to allow for accurate results of student grades. The schools will be analyzed by student grades, school funding, school size and school type.  

# Results:

## How the District Summary Affected
The school summary can be said to be impacted as it lowers the overall passing score percentage. This is not due to the student being taken into account when calculating the percentage. However, Thomas High School has overall high scores, which means that by removing the scores for ninth grade the overall passing score can be said to be lowered. Also the Total School Budget shoul be slightly lowered because the ninth graders were removed when calculating the passing percentage but that was not the case for the budget. 
![District Summary](https://user-images.githubusercontent.com/104809098/173965471-d9d888fc-3488-4e65-a376-bedacb2a0100.png)


## How the School Summary Affected
The School summary is affected with NaN entries for all the ninth graders' in Thomas High School. Which means that only Thomas High School shows the affect of removing the ninth graders' scores. All other schools are left as is. 
![School Summary](https://user-images.githubusercontent.com/104809098/173965475-f4b3e120-e9d9-460e-8129-9c89db390194.png)


## Thomas High School’s Performance Relative to Other Schools
Replacing the the ninth graders' math and reading scores affect the the school performance only when the data is taken into account. The overall passing percentage for the school is lowered to 65%. However, this also shows that the scores for this school were relative good as it only fell to the 7th place among the other schools when sorting by the overall passing scores. If ninth graders are removed from the analysis, than the school is left within the the top 5 schools. or Second place to be more accurate.    

## Replacing the ninth-grade scores affect: Math and reading scores by grade.
The only grade affected is the ninth grade. The averages can be said to be lowered as Thomas High School is a relatively high scorers.  

## Replacing the ninth-grade scores affect: Scores by school spending
Since only count was taken into account, the overall spending is skewed. This means that the analysis shows more spending per student for Thomas high school. Which would place that scool in an incorrect spending bin. 

## Replacing the ninth-grade scores affect: Scores by school size
This doesn't really affect the school designation by school size. Thomas High School stayed within the medium size schools even if the nine graders' are removed from the school count. But for that bin the scores are lower than they should be based on the scores from the other grades at Thomas High School.

## Replacing the ninth-grade scores affect:Scores by school type
If the nine graders' scores were taken into account for this analysis, it would lower all the scores for the Charter schools. 

# Summary:
The school spending analysis is skewed as the ninth grader from Thomas High School were removed but the budget was not changed to reflect that change. The overall passing scores for Thomas High School drop from a passing percentage to a failing percentage. The scores for all charter schools are lowered as Thomas High School is a high scorer and with out their scores, other schools with lower passing averages are not offset as much. There is also a negative impact on the scores for medium size schools as, Thomas High School falls witin that category.  
