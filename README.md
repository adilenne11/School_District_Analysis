# School_District_Analysis

## Purpose 
The school board discovered that the standardized reading and math test scores for Thomas High School ninth graders have been dishonestly altered, and they requested for updated data summaries. In order to uphold state-testing standards, only the ninth-grade math and reading scores at Thomas High School will be replaced with NaNs while keeping all other data associated with this student group intact. The purpose of this analysis is to describe how these changes affected the overall analysis.

## Results
### *District Summary*

The district summary was affected in these areas:
- 	Average Math Scores moved from 79 to 78.9. It dropped .1.
-	Average Reading Scores stayed the same.
-	Percent Passing Math moved from 75% to 74%. It dropped 1%.
-	Percent Passing Reading moved from 86% to 85%. It dropped 1%.
-	Percent Overall Passing moved from 65% to 64%. It dropped 1%

###### School District Analysis Original

![District Analysis Original](https://user-images.githubusercontent.com/110357810/190579050-6e9f1dba-a7db-41f6-be0b-504e8d86d6c5.png)

###### School District Analysis Updated

![District Analysis Updated](https://user-images.githubusercontent.com/110357810/190579256-dc94e680-24c7-4edf-8e78-745c0d759a57.png)

### *School Summary*
Thomas High School is no longer top 10 after replacing ninth-grade scores with NaNs.
- Before replacing math and reading scores with NaNs, Thomas High School ranked 2nd place in the top five performing schools with a 91% overall passing. (See photo 1A and 1B)
- After replacing math and reading scores with NaNs, Thomas High School ranked 8th place out of 15 schools with a 65% overall passing. THS is not found in the bottom 5 performing schools. (See photos 2A and 2B)

###### (1A) School Summary Original

![School Summary Original](https://user-images.githubusercontent.com/110357810/190579409-13579d3c-531f-4c02-a8f6-3eea73295e56.png)

###### (2A) School Summary Updated

![School Summary Updated](https://user-images.githubusercontent.com/110357810/190579680-60950ba6-49ba-4ce6-83a3-eca960f3d6c6.png)

###### (1B) Top 5 Performing Schools

![Top 5 Performing Schools](https://user-images.githubusercontent.com/110357810/190579856-bbfeb94c-8b59-4e49-95d6-11dd58cbcdc4.png)

###### (2B) Bottom 5 Performing Schools

![Bottom 5 Performing Schools](https://user-images.githubusercontent.com/110357810/190579964-a16d5ca1-5ce6-4a0f-b59d-68afe79121f1.png)

### *Replacing the Ninth-Grade scores affected the following:*

- Math and reading scores by grade.
    - Thomas High School's math and reading scores were removed from the 9th grade and all other scores stayed the same.
    
###### Average Math Scores by Grade and School Original

![Math Scores Original](https://user-images.githubusercontent.com/110357810/190580146-cdc91e81-2fc0-4cef-a270-9b71db015ee3.png)

###### Average Math Scores by Grade and School Updated

![Math Scores Updated](https://user-images.githubusercontent.com/110357810/190580234-8832caee-53a1-48df-9c38-2e7ddb1aa375.png)

###### Average Reading Scores by Grade and School Original

![Reading Scores Original](https://user-images.githubusercontent.com/110357810/190580359-0ef805cf-2b9e-4ae6-a787-66f71c017d9c.png)

###### Average Reading Scores by Grade and School Updated

![Reading Scores Updated](https://user-images.githubusercontent.com/110357810/190580560-e4fe324c-3fd0-42d8-ad74-ad0c17495c45.png)

- Scores by school spending.
    - There was a minor change in the scores by school spending groups scores. The $630-644 per student grouping, this is where Thomas High School is grouped, changed by less than 0.1%.
    
###### Impact on Scores by School Spending Original

![Impact on Scores by School Spending Original](https://user-images.githubusercontent.com/110357810/190581043-a4b7f7e6-1e04-4425-945e-d9d5686dc554.png)

###### Impact on Scores by School Spending Updated

![Impact on Scores by School Spending Updated](https://user-images.githubusercontent.com/110357810/190581128-4fe6be8c-b686-43ae-a38b-f6b64e21bf50.png)

- Scores by school size
    - The scores for the Medium (1000-2000) size schools changed slightly by less than 1%. 
    
###### Impact on Scores by School Size Original

![Impact on Scores by School Size Original](https://user-images.githubusercontent.com/110357810/190581259-85010b3a-19ab-4fd6-9de2-f65ff3331efe.png)

###### Impact on Scores by School Size Updated

![Impact on Scores by School Size Updated](https://user-images.githubusercontent.com/110357810/190581346-02a453bf-bdb8-4450-9ec6-3b5b35cbd3de.png)

- Scores by school type
    - Charter school:
        - The scores changed slightly by less than 1%.
        - Average Math scores declined from 83.47 to 83.46.
        - Average Reading scores increased slightly 83.89 compared to 83.9.
        - Percent Passing Math declined from 93.62% to 93.61%.
        - Percent Passing Reading declined from 96.58% to 96.55%.
        - Percent Overall Passing decreased from 90.4% to 90.39%
    - District school:
        - Average math, average reading scores, percent passing math, percent passing reading, percent overall passing were not affected. Thomas High School is a Charter School.

###### Impact on Scores by School Type Original

![Impact on Scores by School Size Original](https://user-images.githubusercontent.com/110357810/190581849-5e23a45c-8454-4e0d-8924-f435882c6cc0.png)

###### Impact on Scores by School Type Updated

![Impact on Scores by School Size Updated](https://user-images.githubusercontent.com/110357810/190581937-6fd64b75-38ec-4063-b016-6a4026844ac0.png)

## Summary

Replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact did not alter data summaries greatly overall rather in the slightest. Comparing the analysis between counting and not counting Thomas High School Ninth Grade scores affected the average and scores at District Level, School Type Level and School Level in the slightest.
