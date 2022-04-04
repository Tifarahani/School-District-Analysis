# The-school-analysis

## Overview of Project

The school district discovered that the standardized test scores for ninth grade students at Thomas High School were incorrect, and they requested for updated data summaries. After further discussion, it was best to only replace the ninth grade math and reading scores at Thomas High School while keeping all other data associated with this student group intact.

Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value, for 461 student records. Although this may seem like a significant number, these score replacements did not alter data summaries tremendously overall.

## Resources
* Jupyter Notebook, 
* Pandas
* Python


![4.1](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.1.PNG)


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


![4.2](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.2.PNG)


**2. The school summary DataFrame.**


![4.3](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.3.PNG)

**3. The top 5 performing schools, based on the overall passing rate.**

![4.4](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.4.PNG)


**4. The bottom 5 performing schools, based on the overall passing rate.**

![4.5](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.5.PNG)

**5. The average math score for each grade level from each school.**

![4.6](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.6.PNG)


**6. The average reading score for each grade level from each school.**

![4.7](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.7.PNG)


**7. The scores by school spending per student.**

![4.8](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.8.PNG)


**8. The scores by school size.**


![4.9](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.9.PNG)

**9. The scores by school type.**

![4.10](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.10.PNG)


## Deliverable 3: A Written Report for the School District Analysis

**BEFORE DATA CLEANUP**
- Average Math Score = **79.0**
- Average Reading Score = **81.9**
- % Passing Math **75**
- % Passing Reading **86** 
- % Overall Passing **65**

**Before Cleanup - PyCitySchools file**

![4.11](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.11.PNG)

**AFTER DATA CLEANUP**

- Average Math Score = **78.9**
- Average Reading Score = **81.9**
- % Passing Math **74.8**
- % Passing Reading **85.7** 
- % Overall Passing **64.9**

**After Cleanup - PyCitySchools_Challenge file**


![4.12](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.12.PNG)

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

![4.15](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.15.PNG)

* Scores by school size

   - Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket.
   - Removing Students from Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644"
    - Thomas High School is allocated on Spending Bin "$630-644" 
        
 **School Size"**
     
 ![4.16](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.16.PNG)
    
  **THS Spending Bin "$630-644"**
     
 ![4.17](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources.PNG)
 
 ![4.18](https://github.com/Tifarahani/School-District-Analysis_Challange/blob/main/Resources/4.18.PNG)
     
3. **Summary:** 
Overall Passing marks changes and difference for each students funding is ~ $200). 
Updated School_District_Analysis Reading and Math Scores from Thomas High School 9th Grade have been replaced with NaNs.
In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.

