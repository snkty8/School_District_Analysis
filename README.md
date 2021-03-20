# School_District_Analysis

## Challenge Overview

Due to academic dishonesty, specifically reading and math grades for Thomas High School ninth graders appear to have been altered.  Allow the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turn to us for help.  We have been tasked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.


## Results

- As seen in the image below, the district as a whole has done well. The average math score is 78.9 with average percentage of students passing math is 74.8%.  Reading is also good with the average score of 81.9 and average passing score of 85.7%.  The numbers drop when including students passing both reading and math with an average percentage of 64.9%.

![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/District%20Summary.png)

- The 9th grade math and reading scores from Thomas High School were removed, this is how the score faired for the school as a whole:
        - Average Math Score: 83.3
        - Average Reading Score: 83.9
        - Passing Math Percentage: 66.9%
        - Passing Reading Percentage: 69.7%
        - Overall Passing Percentage: 65.1%

        This is also seen in the image below.  Thare are results from the school data frame after the 9th grade scores were removed from the data set at Thomas High School.
![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/School%20Summary%20Before.png)

- After replacing 9th graders scores with an average of the 10th through 12th graders score, the percentages of passing students rose significantly:
        - Average Math Score: 83.3
        - Average Reading Score: 83.9
        - Passing Math Percentage: 93.2%
        - Passing Reading Percentage: 97.0%
        - Overall Passing Percentage: 90.6%

        This is also seen in the image below.  These are the results from the school data from after the 9th grade scores were replaced with an average from the 10th through 12th graders scores.
![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/School%20Summary%20After.png)

- Using the same before and after images from above, we can compare how Thomas High School to the schools.  From the data, Thomas High School is definitely more competitive with the high scores.  Before, Thomas High School was in a lower overall grade bracket with an overall passing percentage of 65.1% and after the replacement scores it shot up to 90.6%.  The ends up putting Thomas High School in the top 5 schools.  

- Below are the math and reading data frames after replacing the scores at Thomas High School. Not only are the 9th grade math and reading scores at Thomas High School the highest amoung other 9th graders at different schools, it is also the highest for all grades in all of the schools.

        Math Sores Data Frame and code used to create
![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/Math_Scores.png)


        Reading Scores Data Frame and code used to create
![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/Reading_Scores.png)

- Replacing the 9th graders scores at Thomas High School does not look to have changed the way money is spent per student. Below is the data frame to show the bins for spending range, scores, and percentages:

![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/Spending.png)

- Replacing the 9th graders scores at Thomas High School does not look to have effect on school size. Below is the data frame to show the bins for school size, scores, and percentages:

![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/Size.png)

- Charter schools obviously have better schools and percentages of students passing in comparison to district school.  Below is the data frame to show this information.
 
![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/Type.png)


## Summary

- The 9th grade math and reading schools were suspected of academic dishonesty.  In order to up hold testing standards, the scores with replaced with NaNs, then replaced with average scores from the 10th through 12th grade scores.

        9th Grade Scores at Thomas High School Replaced with NaN
![image](https://github.com/snkty8/School_District_Analysis/blob/main/Resources/NaNs.png)


This resulted in Thomas High School rising up to one of the top 5 schools due to the rise in scores and percentage of overall passing students.  The spending budget and school size were not affected.  Although Thomas High School rose to of the tope 5 schools, it was shown in the school type data frame Charter Schools are doing much better academically than District schools.  Thomas High School is adistrict school.  It would be beneficial to know if the academic dishonesty had something to do with lower or raising the 9th graders scores and percentages.  Although we have done a good job replacing the scores, we could be making things look better than they actually are. 