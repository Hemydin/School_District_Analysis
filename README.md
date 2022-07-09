## School District Analysis
### Project Overview
In this challenge, I re-performed the school district analysis, considering the evidence of academic dishonesty at Thomas High School that jeopardized ninth-grade students' test scores. I was instructed to replace the ninth-grade math and reading scores with "NaN" while keeping the rest of the data intact. In the following section, we'll discuss how these changes affected the overall analysis.
### Results:
#### School District Summary
- The score replacement impacted the average math score by 0.1 points, while the average reading score stayed unchanged.
- Passing math and reading percentages dropped by 0.2%  and 0.1%, respectively
- The overall passing rate has decreased by 0.3% after the alteration
- The remaining key metrics were unaffected since their calculation did not include NaN values.

![school_district_summary](https://user-images.githubusercontent.com/100629325/177710597-3eb5b39e-93ec-4d99-b2bb-d7978f41ae4b.png)
#### School Summary 
In the student summary report, only records from Thomas High School were affected by the discovery of inaccurate testing scores. I removed 461 student records from the analysis, representing the ninth-grade scores in the adjusted version of the report. The calculations in the original report included the total student count at Thomas High School as 1,635. Therefore, we see a significant decrease in % passing math, % reading percentages, and the overall passing rate. The adjustments for the ninth-grade scores only slightly affected the average math and reading scores.

![school_summary](https://user-images.githubusercontent.com/100629325/177875711-d073665c-6272-45fc-bf8c-5a0c9842e2e1.png)
#### Top 5 performing schools, based on the overall passing rate
Replacing the ninth graders’ math and reading scores dropped Thomas High School’s ranking from the second-best performing school in the school district to number eight. 
![top5_schools](https://user-images.githubusercontent.com/100629325/178117048-fd597c20-39fa-429b-a30a-3ea63200b5ac.png)
#### Average Math and Reading Scores by Grade & School
 In the report on average math and reading scores by grade level, only records for the ninth graders' math and reading scores at Thomas High were affected. The records were replaced by "NaN," which represents a "Not-a-Number" value. Other schools' results, as well as the 10th - 12th grades at Thomas High School, remained unchanged.
 
 ![Average_Math_Scores_byGrade](https://user-images.githubusercontent.com/100629325/177880131-fc00bb2c-71ac-4148-9aa0-977ef1996578.png)
#### Spending Summary
Thomas High School falls under the $631-645 spending range; therefore, we can see a decrease in % passing math, % passing reading, and overall passing rate due to adjustments for the ninth graders' math and reading scores at Thomas High School. This data change did not impact the spending ranges for either the average math scores or average reading scores.

![spending_summary](https://user-images.githubusercontent.com/100629325/178117367-9889b480-b842-4200-a6a6-f6f753a83bca.png)
#### School Size Summary
Given the data change at Thomas High School, the passing percentages for math, reading, and overall rate in the medium-sized schools (1,000-2,000) dropped by 6% each. The average math and average reading scores were not affected by the change.

![school_size_summary](https://user-images.githubusercontent.com/100629325/178117701-d3f334a0-7c67-4c11-895c-05418969ab18.png)
#### School Type Summary
Thomas High School data change has also affected the passing percentages for the charter school category but didn't affect the average math and reading scores.

![school_type_summary](https://user-images.githubusercontent.com/100629325/178118133-594818bc-742d-4bfe-baa9-4491d30611ee.png)
### Summary:
When comparing the updated analysis with the results from the module, I noticed the following changes to the school district analysis after reading and math scores adjustments:
- Removing the ninth-grade scores did not affect the average math and reading scores
- Decrease in percentage passing math
- The decline in percentage passing reading
- Reduction in the overall passing rate
- The drop in Thomas High School's ranking from second place to eighth
