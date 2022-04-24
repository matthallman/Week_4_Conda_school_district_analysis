# school district analysis
Data Resources: [schools_complete.csv](https://github.com/matthallman/Week_4_Conda_school_district_analysis/blob/main/resources/schools_complete.csv) & [students_complete.csv](https://github.com/matthallman/Week_4_Conda_school_district_analysis/blob/main/resources/students_complete.csv)
## Overview of the school district analysis: 
The purpose of the analysis is to replace the 9th grade math and reading scores from Thomas High School with NaN's while keeping the rest of the data intact. Once the scores have been replaced the school district analysis needs to be repeated and a written report with the findings has been requested.

### Deliverable 1: Replace ninth-grade reading and math scores
- How is the district summary affected?
  - Removing the 9th grade reading and math values only slightly affected the overall district numbers moving less than 0.5%
  ### District Numbers pre-removal
  ![Pre-removal](https://github.com/matthallman/Week_4_Conda_school_district_analysis/blob/main/resources/district_totals_prel.png)
  ### District Numbers post-removal
  ![Post-removal](https://github.com/matthallman/Week_4_Conda_school_district_analysis/blob/main/resources/district_totals.png)
  
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### Top Five Ranking Before Replacement of THS 9th Grade Scores to NaN
![Top 5 Ranking Before](https://github.com/matthallman/Week_4_Conda_school_district_analysis/blob/main/resources/top_5_pre.png)
- There is a significant drop in Thomas HS performance compare when the ninth grade students grades are excluded. 
- Thomas HS moved from 2nd postion to 8th in the overall passing % ranking of schools. 
- The % Overall Passing column values have changed from 90.95% to 65.08% for Thomas High School
![THS overall rank](https://github.com/matthallman/Week_4_Conda_school_district_analysis/blob/main/resources/thomas_post_top5.png)
- The % Passing Math column values have changed from 93.27% to 66.91% for Thomas High School
- The % Passing Reading column values have changed from 97.31% to 69.66% for Thomas High School
 
### How does replacing the ninth-grade scores affect the following:
- Scores by school spending
  - The schools whose per student budget ranges between $631 -645 were affected.
   - % Passing Math reduced from 73% to 67%
   - % Passing Reading reduced from 84% to 77%
   - % Overall Passing reduced from 63% to 56%
- Scores by school size
  - Only the scores for medium schools have been affected.
   - % Passing Math reduced from 94% to 88%
   - % Passing Reading reduced from 97% to 91%
   - % Overall Passing reduced from 91% to 85%
- Scores by school type
  - Only the scores at Charter level were affected.
   - %Passing Math reduced from 94% to 90%
   - % Passing reading reduced from 97% to 93%
   - % Overall Passing reduced from 90% to 87%

## Summary: 
Thomas High School's overall performance and ranking drops significantly when the 9th grade students are excluded. 
Charter and medium sized schools performance numbers are also affected. 

[Final Challenge Code](https://github.com/matthallman/Week_4_Conda_school_district_analysis/blob/main/PyCitySchools_Challenge.ipynb)


