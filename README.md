# School_District_Analysis
## Project Overview
The school board wants to determine how various factors effect the performance of students on their standardized math and reading tests. Using the **schools_complete.csv** and **students_complete.csv** datasets, I will analyse how each school's type, size, and budget effects its math, reading, and overall performance. I will also analyse the performance of each grade for the schools. However, the school board suspects that the data provided for Thomas High School's ninth graders may have been manipulated. Therefore, I will perform the analysis with and without including those math and reading scores and compare the results. This analysis will be performed using Python in Jupyter Notebook.

## Results
I merged the two datasets to create a new dataframe that better summarized the data from each school:

<img width="1009" alt="Screen Shot 2021-05-26 at 4 37 11 PM" src="https://user-images.githubusercontent.com/83552696/119744352-ac219b00-be40-11eb-8605-1a668025de3c.png">

I defined passing as scores greater than or equal to 70. Students that passed both their math and reading tests were used to determine the overall passing percentage. With this new dataframe, I peformed the following analysis.

### Top 5 Schools
The top five performing schools did not change with the exclusion of ninth graders of Thomas High School. For both analyses, Thomas High School had the second highest overall passing percentage:

![Uploading Screen Shot 2021-05-26 at 4.58.26 PM.png…]()

With the ninth graders included, the passing percentages were calculated as:

<img width="340" alt="Screen Shot 2021-05-26 at 4 51 50 PM" src="https://user-images.githubusercontent.com/83552696/119745597-539fcd00-be43-11eb-898a-c5db4ab6b960.png">


Without the ninth graders included, the passing percentages were calculated as:

<img width="444" alt="Screen Shot 2021-05-26 at 4 50 58 PM" src="https://user-images.githubusercontent.com/83552696/119745642-661a0680-be43-11eb-9cf2-3a8ec817ee98.png">

The tenth of a percent variations were not enough to effect the outcome of the analysis.



(There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data)



## Summary

(There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced )
