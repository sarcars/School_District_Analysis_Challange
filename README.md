# School_District_Analysis_Challenge
Module 4 challenge

## Overview of the school district analysis

In this module, we looked at data for a school district showing some information about the 15 High Schools including the size and budget, and some information about the students including grade, name, and reading and math scores.  After initial analysis we were asked to recalculate data after removing the grades for 9th graders at Thomas High School.  This was accomplished by finding the math and reading scores for 9th grade students at Thomas High School and replacing these numbers with `NaN` and then recalculating the summaries with the modified data.

## Results

- District Summary
  The district summary is a collection of data from all schools in the district.  This summary was affected only minimally by the change of less than half a percent in some areas.  
  /Resources/district_summary.png
  
- School Summary
  Likewise, the school summary for Thomas High School was only affected minimally (differences can only be seen in fractions of 1 percent)
  /Resources/School_Summary_Comparison.png
  
- Performance Relative to other schools
  The small changes to Thomas High School's math, reading, and overall score percentages did not change Thomas High School's performance relative to other schools.  Both before and after the replacement, Thomas High School was ranked second based on `Overall Passing Percentage` 
  /Resources/Top5.png

- Replacing Thomas High School ninth graders' math and reading scores 
  Math and reading scores for ninth graders at Thomas High School were replaced in the data with `NaN` and scores were recalculated.  
  - Math and reading scores by grade
    /Resources/scores_by_grade.png

Like with the district and school summaries the changes made did not change the scores of any of the district groupings (school spending, size, or type) 
  - Scores by school spending
    /Resources/scores_by_spending.png
    
  - Scores by school size
    /Resources/scores_by_size.png

  - Scores by school type
    /Resources/scores_by_type.png


## Summary 

Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
As shown in the results section the removal of the math and reading scores for the ninth grade at Thomas High School had minimal impact on the totals for the district or the overall passing percentage ranking of schools.  However, the replacement does change the ranking of Thomas High School in some of the other measures.  
**For instance `% Passing Reading` rank falls from 1st before the replacement to 3rd without the 9th grade scores.**  
Also, while the overall summary of scores by various groupings did not change, **Thomas High School already falls into the spending "bin" ($630-$644) with the lowest overall percentage of scores.**  Even a small change in one of the top ranking schools could potentially have an impact on budgets.  
Finally, while Thomas High School remains Top 2 of schools when ranked by Overall Passing Percentage, the `% Overall Passing` is quite close for the top 5 schools with a difference of only a few hundreths of a percent.  **A dip from 90.948 to 90.630 may not seem like much, but it does put Thomas High School closer to the 3rd and 4th ranked schools (Griffin High School at 90.599 and Wilson High School at 90.583)**.
