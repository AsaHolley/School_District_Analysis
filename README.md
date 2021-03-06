# School_District_Analysis
## Overview of the school district analysis ##

This project is based around the testing (math and reading) performance of high school students in a particular school district that looked into a number of factors that could affect the overall passing rate (>=70%) of each individual school. Factors included, size of the school, budget per student, grade level, and type of school. This project also required the removal and re-evaluation of the school district data after it was discovered that the 9th grade class at one of the high schools (Thomas High) had wide spread academic dishonestly. 

**This project used the following resources:** Pythonic code, Jupyter notebook, csv based resources, and the Pandas software library

**Raw code can be found here:** [Code in Juypter Notebook](https://github.com/AsaHolley/School_District_Analysis/blob/main/Challenge/PyCitySchools_Challenge.ipynb)


## Results ##
  **How is the district summary affected?**
  The district summary had little affect from the removal of the Thomas High School 9th graders, despite removing the scores of 461 9th graders. The overall passing   percentage for both math and reading combined went down by only 0.3% with the average reading school staying the same and the average math score only going down     by 0.1%. This is likely due to the large sixe of the school district data set and removing only a small portion of students. 

  ***How is the school summary affected?**
  The overall performance for Thomas High School dropped significantly when removing the 9th grade class. Thomas went from being a top performing school with an   overall passing rate of ~90.6% to ~65.1%. The reading and math overall percentage passing for Thomas High School faced similar drops (from 97.3% and 93.4% to    69.7% and 66.9%, respectively). 
  
  ***How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
  With the revised number from Thomas High, the school went from being a top performer to a bottom performer. Thomas went from being the second best performing school to the 3rd worst out of the 15 schools in the district. 
  
  ***How does replacing the ninth-grade scores affect the following:**
      
      * Math and reading scores by grade
      Removing the 9th graders from Thomas High School and replacing them with "NaN' does not affect the other grades scores and does not change the top or bottom performing schools 
      
      * Scores by school spending
      Removing the 9th graders from Thomas High School and replacing them with "NaN' does not affect scores by school spending.
      
      * Scores by school size
      Removing the 9th graders from Thomas High School and replacing them with "NaN' does not affect scores by school size.
      
      * Scores by school type
      Removing the 9th graders from Thomas High School and replacing them with "NaN' does not affect scores by school type.

## Summary ##
While replacing the 9th graders from Thomas High School does not affect the math and reading schools scores by school spending, scores by school size, and scores by school type it does have a significant effect on how Thomas High School performers relative to other schools. Namely it went from being a top performing school to a bottom performing school. It terms of the district wide summary the overall performance of the district does decrease slightly, but it is relatively negligible. The reason for this is likely the size of the 9th grade school being relatively small vs. the overall size of the school district.


