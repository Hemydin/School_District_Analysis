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
#### Math and reading scores by grade
