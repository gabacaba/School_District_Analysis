# School_District_Analysis
## Overview of the school district analysis 

The purpose of this analysis is to help the school board with a case of academic dishonesty. High school students from the same scool district performed a standarized test for math and reading. It seems that the ninth graders from Thomas High School were academically dishonest. Now the school board needs an updated school district analysis. It needs to replace the math and reading scores for Thomas High School 9th graders with NaNs while keeping the rest of the data intact. 
The following analysis is an updated version of the original school district analysis. It shows how the changes affected the overall analysis and describes the parameters that were affected. 

## Results:
Below you can find a comparison between the original school district analysis and the updated version (THS 9th grader's math and reading scores removed). The relative paths show the location of the pictures that are refered to in each bullet point. 

- How is the district summary affected?
        - %Passing_Math decreased by 0.1% 
        - %Passing_Reading decreased by 0.1%
        - %Overall_Passing decreased by 0.2%
[District Summary for original analysis](resources/district_summary_1.png)
[District Summary for challenge analysis](resources/district_summary_2.png)


- How is the school summary affected?
        -The average math score decresed but the average reading score increased
        -The %passing math, %passing reading and %overall passing decreased by around 0.2%

[School Summary for original analysis](resources/PEr_School_summary_1.png)
[School Summary for challenge analysis](resources/Per_School_summary_2.png)


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
        - Though the %Overall_Passing decreased from 90.94 to 90.63, Thomas High School continues to be the second best school in the district.

[Top_Schools for original analysis](resources/Top_Schools_1.png)
[Top_Schools for challenge analysis](resources/Top_Schools_2.png)

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
        - The 9th grade math and reading scores are not available. They are shown as NaN. The rest of the values remain the same. 
        [MAth scores for original analysis](resources/Average_MAth_1.png)
        [Math scores for challenge analysis](resources/Average_Math_2.png)
        [Reading scores for original analysis](resources/Average_Reading_1.png)
        [Reading scores for challenge analysis](resources/Average_Reading_2.png)
    
    - Scores by school spending
        - Thomas High School is in the $630-$644 bin and it shows no difference in the data
    [Average Scores by Spending for original analysis](resources/Scores_By_Spending_1.png)
    [Average Scores by Spending for challenge analysis](resources/Scores_By_Spending_2.png)
    
    - Scores by school size
        - Thomas High School is a medium size school and shows no difference in the data. 
     [Average Scores by Size for original analysis](resources/Scores_By_Size_1.png)
    [Average Scores by Size for challenge analysis](resources/Scores_By_Size_2.png)
    
    - Scores by school type
        - Thomas High School is a charter school and shows no difference in the data. 
         [Average Scores by School Type for original analysis](resources/Scores_By_Type_1.png)
         [Average Scores by School Type for challenge analysis](resources/Scores_By_Type_2.png)
         
## Summary

The results above demonstrate that there were some changes to the data.

-In the district summary the overall passing percentage decreased. 
-In the school summary the results for Thomas High School decreased. 
-In the top schools analysis Thomas High School continued in second place even if the overall percentage decreased. 
-There was no change to the data related to the "Math and reading scores by grade". In this case it was because the results were NaN.
-There was no change in scores by school spending. However for this analysis I didn't know whether I should eliminate the 9th grade students from the "Total amount of THS students" or not. I didn't do it because 9th graders do study at THS independently of academic dishonesty. So I thought it was best to leave the total amount of THS students intact. This means that there was no change in school spending per student.
