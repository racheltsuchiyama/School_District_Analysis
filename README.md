# School_District_Analysis
## Project Overview
The school board wants to determine how various factors effect the performance of students on their standardized math and reading tests. Using the **schools_complete.csv** and **students_complete.csv** datasets, I analysed how each school's type, size, and budget effected its math, reading, and overall performance. I also analysed the performance of each grade for the schools. However, the school board suspected that the data provided for Thomas High School's ninth graders may have been manipulated. Therefore, I performed the analysis with and without including those math and reading scores and compared the results. This analysis was be performed using Python 3.7.10 in Jupyter Notebook.

## Results
I merged the two datasets to create a new dataframe that better summarized the data from each school:

<img width="1009" alt="Screen Shot 2021-05-26 at 4 37 11 PM" src="https://user-images.githubusercontent.com/83552696/119744352-ac219b00-be40-11eb-8605-1a668025de3c.png">

I defined passing as scores greater than or equal to 70. Students that passed both their math and reading tests were used to determine the overall passing percentage. The data for Thomas High School had slight variations with and without the inclusion of the scores of the ninth graders. However, the other schools in the school summary dataframe remained unchanged. With this new dataframe, I peformed the following analysis.

### Top 5 Schools
The top five performing schools did not change with the exclusion of ninth graders of Thomas High School. For both analyses, Thomas High School had the second highest overall passing percentage:

<img width="820" alt="Screen Shot 2021-05-26 at 4 58 26 PM" src="https://user-images.githubusercontent.com/83552696/119745786-b09b8300-be43-11eb-8f84-2054e89831b3.png">

The table above shows the results of the analysis without the ninth graders excluded. With the ninth graders included, the passing percentages were calculated as:

<img width="340" alt="Screen Shot 2021-05-26 at 4 51 50 PM" src="https://user-images.githubusercontent.com/83552696/119745597-539fcd00-be43-11eb-898a-c5db4ab6b960.png">

The average test scores and passing percentages only had slight variations between the two tables shown above. These changes were not large enough to effect the outcome of the analysis. 

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

The schools were separated into four different spending ranges per student. The average test scores and passing percentages were calculated for the schools within each spending range. Thomas High School was in the $630-$644 range, but the exclusion of the ninth grade test scores had a negligible effect on the averages and passing percentages. The inclusion and exclusion of the ninth grade test scores both resulted in the following results.

<img width="853" alt="Screen Shot 2021-05-27 at 7 29 09 PM" src="https://user-images.githubusercontent.com/83552696/120015549-49dbae00-bf98-11eb-81c4-f7dd880ebf8d.png">

### Scores by School Size

The schools were separated into three different ranges based on the number of students they have. Thomas High School was in the medium range with 1,635 students and was still in the medium student range without the 461 ninth graders included. The average scores and passing percentages of the medium range were the same with and without the Thomas High School ninth graders.

<img width="774" alt="Screen Shot 2021-05-28 at 9 39 01 AM" src="https://user-images.githubusercontent.com/83552696/120021966-988d4600-bfa0-11eb-81ff-606b92ff7337.png">

### Scores by School Type

The schools in the dataset were either charter or district schools. Thomas High School was a charter school. The values in the table below did not change with the ninth graders excluded.

<img width="726" alt="Screen Shot 2021-05-28 at 10 39 20 AM" src="https://user-images.githubusercontent.com/83552696/120022504-587a9300-bfa1-11eb-9170-b377e00e3cd1.png">

## Summary

The school board was concerned that the test scores of the Thomas High School ninth graders were manipulated. However, after replacing those test scores with NaN values, I found a negligible change in the school district analysis. The school district metrics listed in the results were unchanged with the exclusion of the Thomas High School ninth graders. There were small changes in the district summary.

### District Summary

With ninth graders:

 <img width="932" alt="Screen Shot 2021-05-28 at 10 56 32 AM" src="https://user-images.githubusercontent.com/83552696/120028128-24a36b80-bfa9-11eb-9bb3-b00a176d3cbd.png">


Without ninth graders:

<img width="948" alt="Screen Shot 2021-05-28 at 11 33 14 AM" src="https://user-images.githubusercontent.com/83552696/120028158-2e2cd380-bfa9-11eb-9dc1-810f19d0dd2f.png">

The average math and reading scores changed by hundredths of a whole number. However, the hundredths place values do not have a significant effect on the averages. The exclusion of the Thomas High School ninth graders resulted in the average math score being one tenth of a point lower when rounded to the tenth place. The average reading scores were the same when rounded to the tenth place.

The passing percentages for math and reading varied in their tenths place. However, this is equivalent to a thousandths of a whole number and is therefore negligible in the analysis. When rounded to a whole percentage, the passing math and reading values were the same. The overall passing percentages were different with and without the ninth graders included. However, when rounded to a whole percent the overall passing percentages were the same. 

Therefore, the scores of the Thomas High School ninth graders do not appear to have been manipulated. Their exclusion

