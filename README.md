# School District Analysis
## Project Overview
In this challenge, I re-performed the school district analysis, considering the evidence of academic dishonesty at Thomas High School that jeopardized ninth-grade students' test scores. I was instructed to replace the ninth-grade math and reading scores with "NaN" while keeping the rest of the data intact. In the following section, we'll discuss how these changes affected the overall analysis.
## Results:
#### School District Summary
- The score replacement impacted the average math score by 0.1 points, while the average reading score stayed unchanged.
- Passing math and reading percentages dropped by 0.2%  and 0.1%, respectively
- The overall passing rate has decreased by 0.3% after the alteration
- The remaining key metrics were unaffected since their calculation did not include NaN values.

![school_district_summary](https://user-images.githubusercontent.com/100629325/177710597-3eb5b39e-93ec-4d99-b2bb-d7978f41ae4b.png)
#### School Summary 
In the student summary report, only records from Thomas High School were affected by the discovery of inaccurate testing scores. I removed 461 student records from the analysis, representing the ninth-grade scores in the adjusted version of the report. The calculations in the original report included the total student count at Thomas High School as 1,635. Therefore, we see a significant decrease in % passing math, % reading percentages, and the overall passing rate. Removing the ninth-grade scores did not affect the average math and reading scores as significantly.
![school_summary](https://user-images.githubusercontent.com/100629325/177875711-d073665c-6272-45fc-bf8c-5a0c9842e2e1.png)
#### Average Math and Reading Scores by Grade & School
 In the report on average math and reading scores by grade level, only records for the ninth graders' math and reading scores at Thomas High were affected. The records were replaced by "NaN," which represents a "Not-a-Number" value. Other schools' results, as well as the 10th and 12th grades at Thomas High School, remained unchanged.
 
 ![Average_Math_Scores_byGrade](https://user-images.githubusercontent.com/100629325/177880131-fc00bb2c-71ac-4148-9aa0-977ef1996578.png)
