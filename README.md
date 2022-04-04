# The-school-analysis
## Overview of Project
List of deliverables for the analysis of the school district: 
* A high-level snapshot of the district's key metrics
* An overview of the key metrics for each school
* Tables presenting each of the following metrics:
    * Top 5 and bottom 5 performing schools, based on the overall passing rate
    * The average math score received by students in each grade level at each school
    * The average reading score received by students in each grade level at each school
    * School performance based on the budget per student
    * School performance based on the school size 
    * School performance based on the type of school
## Deliverable 1: Replace the reading and math scores.

## Analysis Results
![Step_2](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/Step_2.png)
![Step_3](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/Step_3.png)
![Step_4](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/Step_4.png)
![top5_low 5](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/top5_low 5.png)
## Deliverable 2 : Repeat the school district analysis


## District Summary
Since all of the ninth graders from Thomas High School had their scores replaced the particular focus of the analysis re-run was the
focus on how this adjustment affected the school district analysis was altered. Primary areas of focus were:

* Average math and reading scores at Thomas High School
* Percentage of students passing according to math scores
* Percentage of students passing according to reading scores
* Overall percentage of students who passed both math and reading
* Percentage passing math, reading, and overall by budget per student
* Percentage passing math, reading, and overall by school size
* Placement of schools overall by score values relative to each other

## School Summary

## Math and Reading Scores by Grade
# School_District_Analysis
School District Analysis using"
**"Jupyter Notebook, 
**Pandas
**Python



## Resources
* Data Source: `PyCitySchools.ipynb` file 
* Software: Python, Visual Studio Code, Anaconda, Jupyter Notebook, Pandas

## Deliverable 1: Replace Ninth-Grade Reading and Math Scores

![name-of-you-image](https://github.com/Dorislava/School_District_Analysis/blob/main/4.1.PNG)


## Deliverable 2: Repeat the School District Analysis

* The district summary 
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student, by school size, and by school type
 
### Deliverable 2 Results with detail analysis:
**1. The district summary DataFrame.**
> Image with `Python`, `Jupyter Notebook` and `Pandas` Code below.

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.2.PNG)


**2. The school summary DataFrame.**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.3.PNG)

**3. The top 5 performing schools, based on the overall passing rate.**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.4.PNG)


**4. The bottom 5 performing schools, based on the overall passing rate.**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.5.PNG)

**5. The average math score for each grade level from each school.**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.6.PNG)


**6. The average reading score for each grade level from each school.**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.7.PNG)


**7. The scores by school spending per student.**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.8.PNG)


**8. The scores by school size.**


![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.9.PNG)

**9. The scores by school type.**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.10.PNG)


## Deliverable 3: A Written Report for the School District Analysis

**BEFORE DATA CLEANUP**
- Average Math Score = **79.0**
- Average Reading Score = **81.9**
- % Passing Math **75**
- % Passing Reading **86** 
- % Overall Passing **65**

**Before Cleanup - PyCitySchools file**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.11.PNG)

**AFTER DATA CLEANUP**

- Average Math Score = **78.9**
- Average Reading Score = **81.9**
- % Passing Math **74.8**
- % Passing Reading **85.7** 
- % Overall Passing **64.9**

**After Cleanup - PyCitySchools_Challenge file**


![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.12.PNG)

### School summary 

**BEFORE DATA CLEANUP**
- Thomas High School's % Overall Passing was **91*

**AFTER DATA CLEANUP**
- Thomas High School's % Overall Passing was **65**

**OBSERVATION:** Overall order change due to Thomas High School cleanup .

* Math and reading scores by grade
        - Student count() Before THS Cleanup was: 1635
        - Student count() After THS Cleanup was: 1174
* Scores by school spending
        - Thomas HS is in the spending bucket "$630-644"
       
**After Cleanup - THS count()**

![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.15.PNG)

* Scores by school size

   - Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket.
   - Removing Students from Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644"
    - Thomas High School is allocated on Spending Bin "$630-644" 
        
 **School Size"**
     
 ![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.16.PNG)
    
  **THS Spending Bin "$630-644"**
     
 ![name-of-you-image](https://github.com/Tifarahani/School-District-Analysis_Challange/tree/main/4.17.PNG)
 
 ![name-of-you-image](https://github.com/Dorislava/School_District_Analysis/blob/main/4.18.PNG)
     
3. **Summary:** 
Overall Passing marks changes and difference for each students funding is ~ $200). 
Updated School_District_Analysis Reading and Math Scores from Thomas High School 9th Grade have been replaced with NaNs.
 

