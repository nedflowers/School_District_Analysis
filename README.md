# School_District_Analysis

## Overview of Project
Ninth-grade test scores at Thomas High School appear to have been altered, pointing to academic dishonesty. The school board would like to uphold testing standards while omitting any data that may be compromised. In order to do so, Thomas High School’s reading and math grades for the ninth-grade class must be replaced with NaNs. Once the data edit is completed, gather total number of students, schools, and budget for each school in the district. Then, calculate the average math, reading scores and passing percentage for each school and the overall district. Finally, analyze the results to determine how the grade-change affected the existing results.

 
## School Analysis and Outcome

### Analysis Results

#### District Summary

- The district summary saw a slight decline of in average math scores, passing percentages, and overall passing percentages. However, average reading scores remained the same, as did the budget.

    * Average math scores lost 0.1 of a point, going from 79 to 78.9
    * Passing math percentages fell 0.2 points, from 75% to 74.8% for Thomas High School.
    * Passing reading percentage dropped from 86% to 85.7% (0.3%)
    * Overall passing went from 65% to 64.9% (0.1%) for Thomas High School.

![district_v_district](https://user-images.githubusercontent.com/95272294/150265289-0e237570-e16c-4dba-9ac4-9591b7b21aa4.png)

#### School Summary

- An updated school summary shows Thomas High School dropped in scoring for most categories, except for Avg. Reading score.

  * Overall passing percentage declined 0.32% (90.95% to 90.63%)
  * Passing reading percentage dropped 0.29% (97.31% to 97.02%
  * Passing math percentage fell by 0.08% (93.27% to 93.19%)
  * Average reading score increased by 0.05 points (83.85 to 83.9)
  * Math scores dropped by 0.07 of a point (83.42 to 83.35)
  * Per student budget and total school budget remained the same, as can be seen in the example below:
  
![schoolsummary_v_schoolsummary](https://user-images.githubusercontent.com/95272294/150266576-5c22a996-9d47-460b-a92d-99953b0b8fb6.png)


- Replacing the ninth graders’ math and reading scores did not have a significant effect on how Thomas High School compares with other schools. 
  * Thomas High School remained the number two school in the district with and without the 9th graders’ score. 

![5v5png](https://user-images.githubusercontent.com/95272294/150267152-5a55f585-8b27-4d44-ad45-0d71bcea3184.png)


- Replacement of Thomas High School’s ninth grade reading and math scores with NaNs is reflected in the images below:


![math_v_math](https://user-images.githubusercontent.com/95272294/150267933-9017efe6-ba24-46ff-850d-cc4c25dcb80e.png)


![readvread](https://user-images.githubusercontent.com/95272294/150269137-40530da9-06b5-4db3-8925-b8c90c41914f.png)


- Scores by school spending changed less than 0.1% of a point for the $630-644 range. However, due to formatting (rounding to nearest whole number) the slight difference is not displayed in the finished data frame. 

![by_school_spending](https://user-images.githubusercontent.com/95272294/150270411-9507a86c-37f2-4d44-9a76-b55a39e2ebfc.PNG)

- Scores by school size changed (for Medium 1000-2000) less than 0.1% as well. Again, we do not see this change reflected as the formatting is set to whole numbers, and the difference is not significant. 

![by+school_sixze](https://user-images.githubusercontent.com/95272294/150269777-3d16c67b-4922-4604-9d2a-6fc23e18d72d.png)


- Scores by school type saw less than 0.1% change in “Charter” school type. The “District” school type did not change since the updated score values affect only Thomas High School, a charter school. 

![by_type](https://user-images.githubusercontent.com/95272294/150269607-ec414e2a-ee6f-46ee-a768-af6275340f04.png)


## Summary of School Analysis

The District Summary showed a decrease ---between 0.1 and 0.3 of a point--- in average math scores, passing percentages, and overall passing percentages. If the district summary values were rounded to the nearest whole number, the data frame would seem unchanged. 

In the School Summary, Thomas High School fell between 0.05 and 0.32 of a point in overall passing percentage, reading percentage, math scores and percentage. Student budget and total budget categories’ values remained the same. On the other hand, the average of THS’s reading scores increased by 0.05 of a point. Once again, when the values in the data frame are rounded to the nearest whole number, the change is imperceptible. 

During both instances, top five schools ranking remained the same. However, upon further investigation ---prior to rounding the final values to a whole number--- Thomas High’s numbers do change minimally. Most values fluctuate less than 0.1 of a point except for “% Overall Passing”, which decreased by 0.32 of a percentage. 

For scores by grade level, all scores for the ninth-grade class of Thomas High were successfully replaced with NaNs ([math_v_math] and [reading_v_reading]). The change had no effect on the other schools. If the sum or mean of the data frames were taken before and after replacing the compromised values, there would be a visible change in the data.



