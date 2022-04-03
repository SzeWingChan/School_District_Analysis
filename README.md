# School District Analysis

## Overview of the School District Analysis
After cleaning and combining two different datasets (school and students), a thorough school district analysis surrounding 15 schools has been conducted to reveal possible factors that could impact the performance of the schools.  The district officials could make use of the analysis to determine how money could be allocated to each school and the school board could set strategies and targets for the school.

The list of deliverables includes:
- a high-level school district summary,
- school summary for each school,
- a list of the top and low performing schools,
- the scores by grade for each school,
- the scores by school spending,
- the scores by school size, and
- the scores by school type.


## Results
Impacts of replacing the math and reading scores for Thomas High School as there is evidence of academic dishonesty.

- How is the district summary affected?
    - The average math score, the percentage of students passing math test, the percentage of students passing reading test and the overall passing percentage are lowered after the math and reading scores of the ninth graders of Thomas High School being removed.

    Original
    
    ![district_summary_original](https://github.com/SzeWingChan/School_District_Analysis/blob/main/Resources/district_summary_original.png)
    
    New
    
    ![district_summary_new](https://github.com/SzeWingChan/School_District_Analysis/blob/main/Resources/district_summary_new.png)


- How is the school summary affected?
    - Thomas High School is the only school being impacted as this dataset shows the data for individual schools.
    - There is no change to the data of the rest of the schools.
   

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - The average math score dropped slightly by 0.067412 but the average rading score increased by 0.047152.  
    - The passing percetage of math, passing percentage of reading and the overall passing percentage all dropped slightly.

    Original
    
    ![school_summary_original](https://github.com/SzeWingChan/School_District_Analysis/blob/main/Resources/school_summary_original.png)

    New
    
    ![school_summary_new](https://github.com/SzeWingChan/School_District_Analysis/blob/main/Resources/school_summary_new.png)

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
        - Instead of showing the average math and reading scores, the ninth graders' scores of thhe Thomas High School are being replaced by NaN (i.e. "Not A Number").  
        - There is no change to the data of other high schools.

        ![Math Scores by Grade] (https://github.com/SzeWingChan/School_District_Analysis/blob/main/math_scores_by_grade.png)

        ![Reading Scores by Grade] (https://github.com/SzeWingChan/School_District_Analysis/blob/main/reading_scores_by_grade.png)

    - Scores by school spending
        - The numbers remain the same since the impact of the Thomas High School's ninth graders is minimal compare to the vast dataset. 

        ![scores_by_school_spending](https://github.com/SzeWingChan/School_District_Analysis/blob/main/scores_by_school_spending.png)
    
    - Scores by school size
        - The numbers remain the same since the impact of the Thomas High School's ninth graders is minimal compare to the vast dataset. 

        ![scores_by_school_size](https://github.com/SzeWingChan/School_District_Analysis/blob/main/Resources/scores_by_school_size.png)


    - Scores by school type
        - The numbers remain the same since the impact of the Thomas High School's ninth graders is minimal compare to the vast dataset. 

        ![scores_by_school_size_type](https://github.com/SzeWingChan/School_District_Analysis/blob/main/Resources/scores_by_school_type.png)

## Summary
Changes in the updated district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
-   The average math score of Thomas High School is lowered.
-   The passing percentage of math is lowered.
-   The passing percentage of passing percentage of reading is lowered.
-   The percentage of overall score of Thomas High School is lowered.
