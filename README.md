# School_District_Analysis
Module 4 Python and Jupyter notebooks

### Overview

The team was asked to complete an analysis of the school district to provide a high-level snapshot of the district's key metrics, such as:
  * The top 5 and bottom 5 performing schools based on their overall passing rates. 
  * The average scores of math and reading in each grade level 
  * School performance based on the budget per student
  * School performance based on the school size
  * School performance based on the type of school

Once the analysis was complete there was evidence that some academic dishonesty was to be suspected and so the corrupted data , namely the math and reading scores of Thomas High School's ninth grade, had to be removed while keeping the rest of the data intact. Once it was removed the analysis had to be re-run in order to check in what ways it effected the overall analysis. 

### Results

#### District summary

Before removing Thomas High School Gr9:
![image](https://user-images.githubusercontent.com/100727593/161408220-c40f44fa-fc28-4766-abd6-944941c8f84e.png)

After removing Thomas High School Gr9:
![image](https://user-images.githubusercontent.com/100727593/161408262-64314f73-9ab0-4d6f-9b14-0bedfce2ab61.png)

As can be seen above, only the value of 'Average Math Score' changed at all and that was only by .1%.

#### School Summary

The overall passing percentages in Math and Reading did go down slightly after the re-analysis. For % Passing math: 93.27% to 93.19%, % Passing Reading: 97.31% to 97.02%, and Overall Passing from 90.95% to 90.63%. It's enough to make it clear the students had artificially inflated their grades but not severaly enough that it effected the schools overall ratings. Their overall grades are still very high.     

![image](https://user-images.githubusercontent.com/100727593/161408567-5847c000-99d0-44d0-b038-3cdbc85d4853.png)

![image](https://user-images.githubusercontent.com/100727593/161408572-f3ab74bc-e485-4551-a35d-8ef4eaab4b70.png)

#### School Rankings

The overall school ratings were not effected by dropped the grade 9's scores. Thomas High School remained the second best school in the district for overall passing grades. 

#### Math and Reading Scores by Grade

Removing the Grade 9 grades only effects them and no other element. 

For example the Reading Scores by grade breakdown for Thomas High School is below:

![image](https://user-images.githubusercontent.com/100727593/161408868-2fca0cae-deff-453f-976a-c7359141c6ba.png)

#### School Spending


Removing the Grade 9's from Thomas High School does not effect the results of the breakdown of schools based on per student spending ranges.

![image](https://user-images.githubusercontent.com/100727593/161408937-4125d000-8b09-492d-8ccb-53215cfe2e0e.png)

![image](https://user-images.githubusercontent.com/100727593/161408945-a9117541-2c50-4852-af9f-275ece98b4e2.png)

#### Scores by school size

Thomas High School was classified as a 'medium' sized school with 1635 students. 461 students were in Grade 9. Dropping their data does not effect the overall scores for medium sized schools. 
![image](https://user-images.githubusercontent.com/100727593/161409137-df5c0d0e-ab76-4618-b814-b2510ae3a635.png)

![image](https://user-images.githubusercontent.com/100727593/161409146-27e1775c-ca82-46e9-be14-03618415fcac.png)


#### Scores by school type

As with the above there was no effect on the overall outcome of the analysis based on school type. Thomas High School is a charter school and they typically outperform district schools. 
![image](https://user-images.githubusercontent.com/100727593/161409154-1f09ba4e-6e9f-4cea-b730-63e6cabb6c8c.png)

![image](https://user-images.githubusercontent.com/100727593/161409158-fac62ad6-fb0a-47f6-b2b9-cc72fc47b532.png)

### Summary

Dropping a small element of one school's population (461 of 39,170 students) does not greatly effect the overall analysis of the data. If this was a smaller dataset or a larger percentage had to be removed the effects would have been greater. The fact that the passing scores in reading, math, and overall were slightly lower in the second analysis does prove that the grades that were removed were higher than the average and artificially inflated the scores. This could be evidence of cheating. If the numbers in the second analysis had been higher that could indicate that there was an error as no student would purposefully lower their grades. 
