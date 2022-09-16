# School_District_Analysis

## Purpose 
The purpose of this analysis is to compare Thomas High School Ninth Grade Scores before and after NaNs.

## Results
### *District Summary*

The district summary was affected in these areas:
- Average Math Scores moved from 79 to 78.9 when taking out the Ninth Grade scores.
-	Average Reading Scores stayed the same.
-	Percent Passing Math moved from 75% to 74%.
-	Percent Passing Reading moved from 86% to 85%.
-	Percent Overall Passing moved from 65% to 64%.

District Summary Data Frame with Nan
![District Summary Data Frame with NaN](https://user-images.githubusercontent.com/110357810/190533549-b9ac25b9-c9b2-4a31-91b2-80c4fde37566.png)

District Summary of Data Frame original
![District Summary Data Frame](https://user-images.githubusercontent.com/110357810/190533572-fb85fd63-2f23-4907-b42d-3bd8d7a97b68.png)

### *School Summary*

Thomas High School is no longer top 10 after replacing ninth grade scores with Nan.
- Average Math decreased from 83.42 to 83.35.
- Average Reading increased a tad from 83.84 to 83.89.
- Average Percent Passing Math decreased from 93.3% to 66.9%.
- Percent Passing Reading decreased from 97.3% to 69.7%.
- Average Percent Overall passing both Math and Reading decreased from 90.9% to 65.1%.

Top 5 performing schools with NaN
![Top 5 performing schools](https://user-images.githubusercontent.com/110357810/190533858-19201ff8-5a0f-4984-8efb-a18274d29407.png)


### *Replacing the Ninth Grade scores affected the following:*

- Math and reading scores by grade.
    - Thomas High School's math scores were removed from the 9th grade and all other scores stayed the same.
- Scores by school spending.
    - The overall passing percentage decreased from 62.9% to 56.4% when the Ninth-Grade scores were removed.
- Scores by school size
    - No solid findings for school size were affected after adding the NaNs.
- Scores by school type
    - Charter school:
        - Average Math scores declined from 83.47 to 83.46.
        - Average Reading scores increased slightly 83.89 compared to 83.9.
        - Percent Passing Math declined from 93.6 to 90.3.
        - Percent Passing Reading declined from 96.6% to 93.1%.
        - Percent Overall Passing decreased from 90.4% to 87.2%.
    - District school:
        - Average math, average reading scores, percent passing math, percent passing reading, percent overall passing were not affected. Thomas High School is a Charter School.


## Summary
 Replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact affected the overall analysis. Comparing the analysis between counting and not counting Thomas High School Ninth Grade scores affected the average and scores at District Level, School Type Level and School Level.
