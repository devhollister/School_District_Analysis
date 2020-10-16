# School District Analysis

## Overview 

The following is an analysis of a school district's standardized test scores to provide insights into performance trends and patterns in relation to school spending, school size, and school type. After scores belonging to the Thomas High School ninth grade were found to show evidence of academic dishonesty, the analysis was undertaken a second time with those scores affected being voided. The differences between the original analysis and the second excluding ninth grade scores from Thomas High School are discussed below. 

## Results

* On a district level, the omission of Thomas High ninth grade scores lowers four of the five standardized testing performance measures with exception being the average reading score, which stayed roughly the same. However, the other four performance categories dropped only slightly: 0.1 point for the average math score and 0.1 - 0.3% for the percentage of students passing math, reading, and both.  This may be seen as support for the claim that the scores were artificially high.
  ##### Original District Summary
  ![](resources/DataFrame_Screenshots/district_summary.png)
  ##### Revised District Summary
  ![](resources/DataFrame_Screenshots/district_summary_revised.png)

* In a school by school analysis, only the scores of Thomas High School are affected in the revised analysis. As shown below, all performance metrics with the exception of average reading score, which increased minutely, fell slightly when the scores in question were eliminated.
  ##### Thomas High School Summary
  ![](resources/DataFrame_Screenshots/ths.png)
  ##### Revised Thomas High School Summary
  ![](resources/DataFrame_Screenshots/ths_revised.png)
  
  The complete revised district summary by school is shown below:
  ##### Revised Disctrict Summary by School
  ![](resources/DataFrame_Screenshots/per_school_summary_revised.png)

* In both analyses, Thomas High School was within the top five highest performing schools and was second when ranked by overall percentage of students passing both math and reading. It should be noted, however, that when it comes to the other metrics, Thomas High fell from having the second highest to third highest average math scores, third highest to fourth higest average reading score, and highest to third highest percentage of students passing reading.    
  ##### Top 5 Schools
  ![](resources/DataFrame_Screenshots/top_five_schools.png)
  ##### Revised Top 5 Schools
  ![](resources/DataFrame_Screenshots/top_five_schools_revised.png)

* When math and reading averages were analyzed by grade, ninth grade scores at Thomas High School were replaced by the word "nan" for "Not a Number". The rest of the results were unaffected between the two analyses. 
  ##### Revised Math Scores by Grade
  ![](resources/DataFrame_Screenshots/math_averages_revised.png)
  ##### Revised Reading Scores by Grade
  ![](resources/DataFrame_Screenshots/reading_averages_revised.png)

* Standardized testing performance when analyzed by school spending did not significantly change when ninth grade scores from Thomas High School were omitted. The results of the revised analysis is pictured below. 
  #### Revised Performance by School Spending
  ![](resources/DataFrame_Screenshots/school_spending_summary.png)

* Standardized testing performance when analyzed by school size did not significantly change when ninth grade scores from Thomas High School were omitted. The results of the revised analysis is pictured below. 
  ##### Revised Performance by School Size
  ![](resourcesDataFrame_Screenshots/school_size_summary.png)

* Standardized testing performance when analyzed by school type (charter or district) did not significantly change when ninth grade scores from Thomas High School were omitted. The results of the revised analysis is pictured below.
  ##### Revised Performance by School Type
  ![](resources/DataFrame_Screenshots/school_type_summary.png)

## Summary:
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
