# School_District_Analysis

## Overview of the School District Analysis
The school board notified Maria and her supervisor that the initial analysis done shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. The school board wants to uphold state-testing standards. In order to do so we have to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once that has been done the analysis done initially is to be done again with the replaced data.

## Results

1. **How is the district summary affected?**

   There has been a slight change in Average Math Score, % Passing Math, % Passing Reading and % Overall Passing as its evident from the below images :-
   
   ***Image from PyCitySchool.ipynb***
   
   ![image](https://user-images.githubusercontent.com/80116407/118366194-b5bc2080-b56d-11eb-951a-3120a7bee23b.png)

   ***Image from PyCitySchool_Challenge.ipynb***
   
   ![District_Summary_post_THS_slicendice](https://github.com/yashodhan1202/School_District_Analysis/blob/main/District_Summary_post_THS_slicendice.png)
   
   These changes are not that significant to affect any decision.

2. **How is the school summary affected?**

   There is no change in the school summary at all once the cells have been formatted. Please refer the two images below for comparison.
   
   ***Image from PyCitySchool.ipynb***
   
   ![image](https://github.com/yashodhan1202/School_District_Analysis/blob/main/School_Summary_PreTHS.png)
   
   ***Image from PyCitySchool_Challenge.ipynb***
   
   ![image](https://github.com/yashodhan1202/School_District_Analysis/blob/main/School_Summary_PostTHS.png)
   
3. **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

   Overall it does not affect either the reading scores or math scores relative to other schools.
   
4. **How does replacing the ninth-grade scores affect the following:**
     
     - ***Math and reading scores by grade***
         
      Overall there is no change in the dataframe, except where the 9th Grade column shows "Nan" for Thomas High School as show in the below images.
     
     ![image](https://github.com/yashodhan1202/School_District_Analysis/blob/main/Maths_Score%20Comparison.png)
     
     ![Image](https://github.com/yashodhan1202/School_District_Analysis/blob/main/Reading_Score%20Comparison.png)
     
     
     - ***Scores by school spending***
       
       There is no change in the data for scores by school spending as the changes have an immaterial impact on the overall dataset. Please refer the image below for comparison:
       
       ![Image](https://github.com/yashodhan1202/School_District_Analysis/blob/main/Score_by_spending_Comparison.png)
             
     - ***Scores by school size***

       There is no change in the data for scores by school size. Please refer the below image for comparison:
       
       
Scores by school type
   
   
