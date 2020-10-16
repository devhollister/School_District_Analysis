# School District Analysis

## Overview 

The following is an analysis of a school district's standardized test scores to provide insights into performance trends and patterns in relation to school spending, school size, and school type. After scores belonging to the Thomas High School ninth grade were found to show evidence of academic dishonesty, the analysis was undertaken a second time with those scores affected being voided. The differences between the original analysis and the second excluding ninth grade scores from Thomas High School are discussed below. 

## Results

* On a district level, the ommision of Thomas High nineth grade scores lowers four of the five standardized testing performance measures with exception being the average reading score, which stayed roughly the same. However, the other four performance categories dropped only slightly: 0.1 point for the average math score and 0.1 - 0.3% for the percentage of students passing math, reading, and both.  This may be seen as support for the claim that the scores were artificially high.
  ##### Original District Summary
  ![](resources/DataFrame_Screenshots/district_summary.png)
  ##### Revised District Summary
  ![](resources/DataFrame_Screenshots/district_summary_revised.png)

* How is the school summary affected?
![](resources/DataFrame_Screenshots/per_school_summary.png)
![](resources/DataFrame_Screenshots/per_school_summary_revised.png)

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Top Five Schools](Resources/DataFrame_Screenshots/top_five_schools.png) ![](resources/DataFrame_Screenshots/top_five_schools_revised.png)

![](resources/DataFrame_Screenshots/bottom_five_schools.png) ![](resources/DataFrame_Screenshots/bottom_five_schools_revised.png)


How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
![](resources/DataFrame_Screenshots/math_scores_by_grade.png) ![](resources/DataFrame_Screenshots/math_averages_revised.png)

Scores by school spending
![](resources/DataFrame_Screenshots/school_spending_summary_revised.png) ![](resources/DataFrame_Screenshots/school_spending_summary.png)


Scores by school size
![](resources/DataFrame_Screenshots/school_size_summary_revised.png) ![](resourcesDataFrame_Screenshots/school_size_summary.png)


Scores by school type
![](resources/DataFrame_Screenshots/school_type_summary_revised.png) ![](resources/DataFrame_Screenshots/school_type_summary.png)

## Summary:
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
