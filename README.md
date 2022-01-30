# School_District_Analysis
Module 4
## Overview of the school district analysis

The purpose of this analysis was to use Python and Jupyter Notebook and code that we had already created to conduct an analysis on schools within a school district. We analyzed the highest and lowest performing schools within the district, the budget per student, and the math and reading grades of students. Once we ran through our code we created during the module, we started on the particular purpose of this challenge assignment. We wanted to see if there were signs of academic dishonesty, so we went to Thomas High School and exchanged the 9th grade reading and math scores for NaNs. Then we redid our analysis using these NaNs. 

## Results
* District Summary- Looking at the district summary from the original and comparing with the adjusted, the number of students, schools, and budget stayed the same. The math and reading scores dropped slightly, but the biggest change was that the overall passing % dropped a percentage point. 

* School Summary- Because the school board was concerned about Thomas High School and the scores of their 9th grade students, we conducted a test. We replaced the 9th grade math and reading scores with NaNs and redid the analysis. 
Here are the original results:
![image](https://github.com/aisligrace/School_District_Analysis/blob/main/original%20analysis.png)
As you can see, Thomas High School had an overall passing rate of 90% which was of concern to the school board. 

And here is the redone analysis:
![image](https://github.com/aisligrace/School_District_Analysis/blob/main/adjusted%20analysis.png)

As you can see, it significantly changed the overall passing % of Thomas High School.Thomas High School went from being the 2nd highest rated school in the district to 8th. 

* Reading and Math Scores- In our first analysis, Thomas High School had a reading average score and a math average score of about 83. In our new analysis, you can see what replacing the NaNs to 9th grade did here:

![image](https://github.com/aisligrace/School_District_Analysis/blob/main/9th%20grade%20NaNs.png)

* Scores by Spending- Thomas High School was in the $630-644 bin for spending. We did not see that change in the adjusted analysis. 

* Scores by Size- Thomas High School was classified as a 'medium' size school in both the original analysis and the adjusted. 

* Scores by Type- Thomas High School was classfied as a Charter school in both the original analysis and the adjusted.

## Summary
Here are the four main changes I saw between the original analysis and the NaN analysis:

1)I believe the biggest change was that the overall passing rate of THS dropped from 91% to 65%

2)Looking at the math and reading scores, the passing % of students dropped from 97% to 69% in reading and 93% to 66% in math. 

3)THS was the second rated school in the district in our original analysis and dropped to 8th out of 15 in the NaN analysis

4) The redone analysis with the NaN values affected the entire district, including dropping the overall passing rate for the district a percentage point
