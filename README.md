# School-District-Analysis

# Background
The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent of this academic dishonesty, they want to uphold the standards of state testing and have turned to you for help.

After assessing the situation with the school superintendent and Maria, you decide the best approach is to:

- Replace the ninth-grade math and reading scores from Thomas High School.
- Keep all other data associated with the ninth-grade students and Thomas High School intact.

# Resources
Data Source: missing_grades.csv, school_complete.csv, student_complete.csv
Software: Python 3.6.1, Jupyter Notebook 6.0.1

# Objectives of Module Challenge
The goals of this challenge are for you to:

- Filter DataFrames using logical operators.
- Replace the incorrect values with NaN.
- Explain how your PyCitySchools analysis changes after you handle the incorrect data.  

# Challenge Summary
## 1. District and school summary DataFrames.
### How is the district summary affected?
- Average Math Score  drops 0.1 
- Average Reading Score unchanged
- % Passing Math drops 1.1 % points
- % Passing Reading drops 1.3% points
- % Overall Passing drops 0.9% points

### How is the school summary affected?
- The same dimensions above for Thomas HS is impacted since all 9th grade math and reading scores were removed.  In summary, % of math and reading passing scores reflect significant drops, over 25% points.
- Thomas HS Average Math Score  up 0.07
- Thomas HS Average Reading Score drops 0.05
- Thomas HS % Passing Math drops 26.4 % points
- Thomas HS % Passing Reading drops 27.7% points
- Thomas HS % Overall Passing drops 25.9% points

## 2. High- and low-performing schools.
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
- Thomas HS was in the top five ranking schools with their math & reading scores.  However, with the removal of the 9th grade scores they dropped from the top 5 ranking and was replaced with Wright HS.

## 3.  Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
### How does replacing the ninth-grade scores affect the following?
- Math and Reading Scores by Grade - Thomas HS math and reading scores are removed for 9th graders so no longer can be compared.  We know the overall averages for both math & reading scores for the entire Thomas HS was minimal.
- Scores by School Spending - Thomas HS is in the $630-$644 school spending category so across the board for Math, Reading & Overall Passing grades it's lowered due to the 9th grade removal (ie % Overall Passing drops from 63% to 56%)
- Scores by School Size -  Thomas HS is in the Medium school size category so across the board for Math, Reading & Overall Passing grades it's lowered due to the 9th grade removal (ie % Overall Passing drops from 91% to 85%)
- Scores by School Type - Thomas HS is in the Charter school size category so across the board for Math, Reading & Overall Passing grades it's lowered due to the 9th grade removal (ie % Overall Passing drops from 90% to 87%)
