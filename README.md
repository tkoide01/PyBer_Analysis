# PyBer Analysis
Analyze the ride-sharing data by city type.

## Overview of the Project
Using Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Finally, summarize a written report of how the data differs by city type and how those differences can be used by decision-makers at PyBer.

Carry out the following two technical analysis and a written report to present the results.
1. A ride-sharing summary DataFrame by city type
2. A multiple-line chart of total fares for each city type
3. A written report for the PyBer analysis 

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.6.1, Jupytor Note Book

## Results
+ How is the district summary affected?
  
  Comparing the two screen shots from district summary before and after replacing the Thomas High School 9th grade students' scorres with NaN, we can observe about 0.1%-0.3% drop in "% Passing Math," "% Passing Reading," and "% Overall Passing" after the event. 
 
  **Before the replacement**
  ![](Resources/Overall_District_Summary.png)
  
  **After the replacement**
  ![](Resources/Overall_District_Summary_NaNremoved.png)
  
  Therefore, the replacement of scores to NaN did slightly negatively impact on the District Summary overall Passing percentage.
  
+ How is the school summary affected?
  
  Reviewing the below tables, we can find that "% Passing Math," "% Passing Reading," and "% Overall Passing" for Thomas High School are declined by approximately 0.3% after replacing the 9th Grade students' scores by NaN.
  
  **Before the replacement**
  ![](Resources/Top_5_Performing_Schools.png)
  
  **After the replacement**
  ![](Resources/Top_5_Performing_Schools_NaNremoved.png)

+ How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  

  
  Althouth the event affected the metrics in the previous two cases, the impact was not large enough to affect the ranking of Thomas High School relative to other schools as shown in the below two rankings.
  
  **Before the replacement**
  ![](Resources/Top_5_Performing_Schools.png)
  
  **After the replacement**
  ![](Resources/Top_5_Performing_Schools_NaNremoved.png)
  
+ How does replacing the ninth-grade scores affect the following:
  Note that I did not observe any affect from the replacement comparing the before and the after as below images for all four categories of analysis.
  
   + Math and reading scores by grade

   **Before the replacement**
   
   ![](Resources/Scores_by_grade_before.png)
  
   **After the replacement**
   
   ![](Resources/Scores_by_grade_after.png)
   
   + Scores by school spending

   **Before the replacement**
   
   ![](Resources/Scores_by_spending_before.png)
  
   **After the replacement**
   
   ![](Resources/Scores_by_spending_after.png)
   
   + Scores by school size
   
   **Before the replacement**
   
   ![](Resources/Scores_by_size_before.png)
  
   **After the replacement**
   
   ![](Resources/Scores_by_size_after.png)
   
   + Scores by school type

   **Before the replacement**
   
   ![](Resources/Scores_by_type_before.png)
  
   **After the replacement**
   
   ![](Resources/Scores_by_type_after.png)



## Summary
   Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

   In conclusion, the impact of replacing the reading and math scores with NaNs for the ninth grade at Thomas High School on the  school district analysis was minimul. Comparing each analysis result from before and the after change, we could find **0.1-0.3% decline** on "% Passing Math," "% Passing Reading," and "% Overall Passing" from the District Summary. Also, the "% Passing Math," "% Passing Reading," and "% Overall Passing" for Thomas High School are declined by approximately 0.3% after replacing the 9th Grade students' scores by NaN.
   
   However, all other measurements such as the ranking of Top and Bottom performing schools, Math and reading scores by grade, Scores by school spending, Scores by school size, and Scores by school type all did not show big differences. Therefore, the school board can make decesion on school budget without considering the impact from this event.
