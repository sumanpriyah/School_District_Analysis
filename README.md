# School_District_Analysis

## Overview of the school district analysis:
In this project we need to deliver below deliverables for the analysis of the school disctrict though Jupyter notebook using Python libraries such as Pandas. 
The purpose of this project is to help Maria and supervisor to find out which schools are the highest performing based on overall percentage of passing students. 
This will help the district determine how much money should be allocated to and spent on each school; this will also allow the school board to set the budget for 
the upcoming school year.
 
 ### Deliverables
1) A high-level snapshot of the district's key metrics, presented in a table format
2) An overview of the key metrics for each school, presented in a table format
3) Tables presenting each of the following metrics:
	-Top 5 and bottom 5 performing schools, based on the overall passing rate
	-The average math score received by students in each grade level at each school
	-The average reading score received by students in each grade level at each school
	-School performance based on the budget per student
	-School performance based on the school size 
	-School performance based on the type of school
	
### software used
python- 3.9.7 , conda 4.10.3, jupyter 1.0.0

## Results:
### District Summary
The approx passing percentage for Maths-75%, reading-86% and overall is 65%. The District summary did not change much after replacing 9th grade maths and reading score with "nan"

### school summary
The school summary did impact for Thomas High School after replacing 9th grade math and reading score with "nan". 
The math passing percentage went from 93.27 to 66.91
The reading passing percentage went from 97.31 to 69.66
The overall passing percentage went from 90.95 to 65.08

### Thomas High School Performance
After replacing the math and reading score with "nan" for 9th grade the overall performance of school went down if the 9th grade was included in overall performance.
Thomas high school does not comes in the top 5 schools if calculations are done with 9th grade.Where the performance is calculated only based on 10th to 12th grade then the math, reading and overall passing percentage is good as compare to including 9th grade scores.

### How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade - For 9th grade math and reading scores are "nan"
Scores by school spending - The score went down as per school spending 
Scores by school size- The score went down as per school size
Scores by school type- The overall score went down as per school type. 


## Summary:
Initially analysis was done on the data provided but later analysis was done by updating 9th grade math and reading score replaced with "nan" due to some academic dishonesty.
Prefixes and Suffixes from the student data - dataframe were removed so that they align with their school records. For analysis school_data_df was merged with student_data_df using merge method
After replacing the 9th grade score to "nan" the passing percentage for - math, reading and overall as per school type got reduced. Thomas High School 9th grade impacted overall 
charter school performance. 
The Bailey High school is largest school with Total students-4976 and gets highest budget of $3,124,928. Holden High School is the smallest school with total students- 427. 
It gets the lowest budget -$248,087. 
The per student budget for Holden High School is the lowest -$581 with overall passing percentage of 89.22 and Huang High school gets the highest per student budget of $655 with lower overall passing percentage
of 53.51
Overall lowest performing schools all are District schools - Bailey High School, Figueroa High School,Ford High School,Hernandez High School,Huang High School,Johnson High School,
Rodriguez High School even they are getting per school budget better than charter schools. All District schools are large with studnet range from 2000 to 5000 and could be reason 
for overall low performance. The Charter schools are doing better seems like school size is medium or smaller




