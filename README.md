# School_District_Analysis
## Project Overview
The school board wants to determine how various factors effect the performance of students on their standardized math and reading tests. Using the **schools_complete.csv** and **students_complete.csv** datasets, I will analyse how each school's type, size, and budget effects its math, reading, and overall performance. I will also analyse the performance of each grade for the schools. However, the school board suspects that the data provided for Thomas High School's ninth graders may have been manipulated. Therefore, I will perform the analysis with and without including those math and reading scores and compare the results. This analysis will be performed using Python in Jupyter Notebook.

## Results
I merged the two datasets to create a new dataframe that better summarized the data from each school:

<img width="1009" alt="Screen Shot 2021-05-26 at 4 37 11 PM" src="https://user-images.githubusercontent.com/83552696/119744352-ac219b00-be40-11eb-8605-1a668025de3c.png">

I defined passing as scores greater than or equal to 70. Students that passed both their math and reading tests were used to determine the overall passing percentage. With this new dataframe, I peformed the following analysis.

### Top 5 Schools
The top five performing schools did not change with the exclusion of ninth graders of Thomas High School. For both analyses, Thomas High School had the second highest overall passing percentage:

<img width="820" alt="Screen Shot 2021-05-26 at 4 58 26 PM" src="https://user-images.githubusercontent.com/83552696/119745786-b09b8300-be43-11eb-8f84-2054e89831b3.png">

The table above shows the results of the analysis without the ninth graders included. With the ninth graders included, the passing percentages were calculated as:

<img width="340" alt="Screen Shot 2021-05-26 at 4 51 50 PM" src="https://user-images.githubusercontent.com/83552696/119745597-539fcd00-be43-11eb-898a-c5db4ab6b960.png">


The tenth of a percent variations were not enough to effect the outcome of the analysis.

### Bottom 5 Schools

Since Thomas High School was one of the top performing schools, the change in students did not alter the results of the bottom five performing schools. For both analyses, the bottom five performing schools based on the overall passing rate were:

<img width="1006" alt="Screen Shot 2021-05-27 at 7 01 31 PM" src="https://user-images.githubusercontent.com/83552696/119918852-0e040280-bf1e-11eb-8c15-094be20a9a19.png">

### Average Math Score for each grade level

The average math score was determined for each grade in each school. For the Thomas High School ninth graders, the math scores were substituted with NaN, or not a number, values. Therefore, the other math averages were uneffected and the only change was the replacement of averages for the Thomas High School ninth graders with a NaN value. The original values are displayed below.

<img width="320" alt="Screen Shot 2021-05-27 at 7 08 59 PM" src="https://user-images.githubusercontent.com/83552696/119919313-04c76580-bf1f-11eb-99a7-66ca50455f9b.png">

### Average Reading Score for each grade level

The average reading scores for each grade in each school had the same effect as the average math scores described above. Below are the results when the scores of the Thomas High School ninth graders are changed to NaN.

<img width="346" alt="Screen Shot 2021-05-27 at 7 13 46 PM" src="https://user-images.githubusercontent.com/83552696/119919628-ad75c500-bf1f-11eb-992d-4b605817a0b2.png">

### Scores by School Spending per student

The schools were separated into four different spending ranges per student. Since the change in the Thomas High School test scores were a tenth of a percentage with and without the inclusion of the ninth graders, it did not have a noticiba

### Scores by School Size


### Scores by School Type


## Summary

(There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced )
