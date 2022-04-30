# Campus-placement

## About :
This data set consists of Placement data of students in our campus. It includes secondary and higher secondary school percentage and specialization. It also includes degree specialization, type and Work experience and salary offers to the placed students

### Columns Details :

1.sl_no : Serial Number

2.ssc_p: Secondary Education Percentage

3.ssc_b: Board of Secondary Education

4.hsc_p: Higher Secondary Education Percentage

5.hsc_b: Board of Higher Secondary Education

6.hsc_s: Specialisation in Higher Secondary Education

7.degree_p: Degree Percentage

8.degree_t: Field of Degree Education

9.workex: Work Experience

10.etest_p: Employability Test Percentage

11.specialisation: MBA Specialisation

12.mba_p: MBA Percentage

13.status: Status of Placement


##  Data Exploration:
Looking at categorical and continuous feature summaries and making inferences about the data.
## Data Cleaning
-- No missing values in the data.
-- Delete some unuseable columns.
## Analysis In-sight :
- From 215 candidates, 148 students got placed while 67 students are not placed.
- About 70.34% students and 69.49% students got placed from commerce & management and science & technology stream respectively. Students from these two streams got placed than others.
- About 79.16% and 55.78% of students got placed from market & finance and market & HR streams respectively. From this we can conclude that students who have market & finance as their specialisation have more chance to be placed.
- 86.48% of students who have work experience got hired while only 59.57% of students with no work experience got hired. Hence work experience influence the hiring process.
- 63.16% females and 71.94% of males got placed. Males have more chance to get placed.

## Model Building
-- First use LOGISTIC REGRESSION  : Accuracy is : 0.7962962962962963
-- 
-- Second use DECISION TREE ALGORITHM : Accuracy is : 1.0
-- 
-- Third  use RANDOM FOREST CLASSIFIER : Accuracy is : 0.8148148148148148
--
-- Fourth use SUPPORT VECTOR MACHINE : Accuracy is : 0.7483443708609272
--












