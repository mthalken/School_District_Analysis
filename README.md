# School_District_Analysis

## The purpse of this analyis is to help a school board analyze the district's reading and math scores, while giving a complete picture by grade, school, school type, and school budget per student.

## Project Overview: 
1. Calculate and present a high-level snapshot of the district's key metrics.
2. Calculate and present an overview of the key metrics for each shcool.
3. Determine the top 5 and bottom 5 performing schools based on overall passing percentage. 
4. Calculate the average math and reading score by grade level and by school. 
5. Find the school performance based on budget per student, school size, and type of school. 
6. Re-analyze and summarize reading and math scores for Thomas High School 9th graders by replacing scores with "NaN". 

## Resources
- Source of data: [student_complete.csv](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/students_complete.csv) and [schools_complete.csv](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/schools_complete.csv)
- Software: Python 3.7.10, Conda 4.10.3, Jupyter Notebook 6.3.0, Visual Studio Code 1.60.2
- Please see the [PyCitySchools_Challenge.ipynb](https://github.com/mthalken/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb) to see the refactored code.  
- You can also see the peliminary code [here](https://github.com/mthalken/School_District_Analysis/blob/main/PyCitySchools.ipynb).

## Results 
### The analysis of the school district's data after inputing "NaN" for Thomas High School 9th grade shows that:
- The district summary varied by slightly decreasing the percentage of the "Average Math Score"(.01).
    - Initial Analysis
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/district_summary_1st_analysis.PNG)
    - Refactored Analysis
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/district_summary.PNG)

- The school summary was only affected for Thomas High School, based on replacing the 9th grade scores. Replacing Thomas High School 9th grade scores brings the school's scores closer to the district averages. 
- Specific changes are as follows with pre-analysis and refactored, respectfully.
    - Math and reading scores by grade: 79.0;78.9 and 81.9;81.9
    - Scores by school spending: no change
    - Scores by school size: no change
    - Scores by school type: no change

### The analysis of the school district's data:
- District Summary: 
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/district_summary.PNG)
- Top 5 Schools: 
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/high_performing_schools.PNG)
- Bottom 5 Schools: 
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/low_performing_schools.PNG)
- Math scores by grade and school: 
    
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/math_scores_by_grade_%26_school.PNG)
- Reading scores by grade and school: 
    
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/reading_scores_by_grade_%26_school.PNG)
- Scores based by school size: 
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/scores_based_by_school_size.PNG)
- Scores based by school type: 
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/scores_based_by_school_type.PNG)
- Scores based by average spending per student: 
    ![png](https://github.com/mthalken/School_District_Analysis/blob/main/Resources/scores_based_by_spending.PNG)

## Summary
In summary after changing Thomas High School's 9th grade scores to NaN it brought the scores closer to the district averages. There was change in only the "Average Math Score"(.01).

Overall, the following can be considered:
- Charter schools have an overall passing percentage of 90% compared to distict schools at 54%, with specific scores for math at 94% and 67% and reading scores at 97% and 81% respectively. 
- Also, the average spending per student in charter schools is less than the average spending for public schools yet there is no significate correlation in spending more equals higher passing percentage. 
- School size for small(less than 1000) and medium(between 1000 and 2000) schools have a 90% and 91% overall passing percentage respectively compared to the large schools(2000 to 5000 students) at 58%. 

Further analysis could look at where the funding per student is allocated, spending and cost of staffing, and number of students vs teachers. These can all be related to the data provided with the district summary. 
