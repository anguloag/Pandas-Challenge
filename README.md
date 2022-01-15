# Py City Schools Standardized Testing Report
## Overview
The purpose of this project was to analyze Py City Schools' district-wide standardized test results and create summary tables using Python and Pandas to highlight trends in school performance. 

## Description of the Data: schools_complete and students_complete
Overall descriptive metricts for each school in Py City are contained in a csv file called "_schools_complete_". The dataset is organized into five columns: 
- **School ID** - the ID number for each school in the city
- **School Name** - the name of each school in the city
- **Type** - the school's type (either charter or district)
- **Size** - the number of students attending each school
- **Budget** - the budget for each individual school

The data for each student attending a Py City school are contained in a csv file called "_students_complete_". The dataset is organized into seven columns:
- **Student ID** - the ID number for each student in the city 
- **Student Name** - the name of each student in the city
- **Gender**- each student's gender (male or female)
- **Grade** - the grade each student is in (9th to 12th grade)
- **School Name** - the name of the school the student attends
- **Reading Score** - the student's numeric score (out of 100) on their standardized reading test
- **Math Score** - the student's numeric score (out of 100) on their standardized math test

## Analysis 
The Jupyter Notebook used for data cleaning and analysis can be found in [PyCitySchools_final.ipynb](PyCitySchools/PyCitySchools_final.ipynb). 

The data from _schools_complete_ and _students_complete_ were merged into one dataset in order to create the following summary tables:
- **District Summary** -- includes the district's key metrics - Total Schools, Total Students, Total Budget, Average Math Score, Average Reading Score, % Passing Math (the percentage of students that passed math), % Passing Reading (the percentage of students that passed reading), % Overall Passing (the percentage of students that passed both math and reading)
(![District Summary](https://user-images.githubusercontent.com/84478236/149641261-28560046-7647-4026-8ee8-43104d71faa6.jpg)

- **School Summary** -- gives an overview of key metrics about each school - School Name, School Type, Total Students, Total School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
![School Summary](https://user-images.githubusercontent.com/84478236/149641359-d8b6b352-d0b1-429a-89f7-07b2ccd087c5.jpg)

- **Top Performing Schools** -- highlights the metrics included in the School Summary for the top 5 performing schools based on % Overall Passing
![Top 5 Performing Schools by Percent Overall Passing](https://user-images.githubusercontent.com/84478236/149641364-638b6201-db54-49f9-baa8-902057094684.jpg)

- **Bottom Performing Schools** -- highlights the metrics included in the School Summary for the bottom 5 performing schools based on % Overall Passing
![Bottom 5 Performaing Schools by Percent Overall Passing](https://user-images.githubusercontent.com/84478236/149641368-3bc2599b-ed87-41d8-a199-e9016137072d.jpg)

- **Math Scores by Grade** -- lists the average math scores for students of each grade level at each school
![Math Scores by Grade](https://user-images.githubusercontent.com/84478236/149641373-26c14148-a997-47c5-9f8f-94659ec7524c.jpg)

- **Reading Scores by Grade** -- lists the average reading scores for students of each grade level at each school 
![Reading Scores by Grade](https://user-images.githubusercontent.com/84478236/149641379-5d8c2d20-a5dc-4705-ae11-2a66851c305b.jpg)

- **Scores by School Spending** -- compares school performance (Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing) based on four reasonable groupings of average spending ranges per student
![Scores by School Spending Per Student](https://user-images.githubusercontent.com/84478236/149641381-19a91a8a-4214-4082-897a-895d90a64c58.jpg)

- **Scores by School Size** -- compares school performance based on reasonable approximations of Small, Medium, and Large school size
![Scores by School Size](https://user-images.githubusercontent.com/84478236/149641382-91e28487-a5c4-4970-9e04-d0a241191f5d.jpg)

- **Scores by School Type** -- compares school performance based on school type
![Scores by School Type](https://user-images.githubusercontent.com/84478236/149641383-ba9c24ac-1fb9-45c9-be9d-fe278fd799ee.jpg)

## Results
Based on the final analysis of the Py City Schools district-wide standardized test results, some observable trends in school performance include the following: 

- **Charter schools tended to perform better than district schools.** When comparing the top and bottom 5 performing schools in the district (based on the percentage of students who passed both the math and reading standardized tests), all the top 5 performing schools are Charter schools while all the bottom 5 performing are District schools. This trend can also be seen in the table Scores by School Type; charter schools had higher math and reading test scores on average compared to district schools and had higher percentages of students who passed either of their tests, especially in math (93.62% at charter schools, versus 66.55% at district schools). Additionally, while the vast majority of charter school students passed both the reading and math tests (90.53%), only about half of the students at district schools passed both of their standardized tests (53.67%). 

- **Spending more money per student doesn’t necessarily mean students will perform better.** When comparing the top and bottom 5 performing schools in the district, the top performing schools tended to have smaller per student budgets (between $578 - 638 per student) than bottom performing schools (between $637 - 655 per student). This negative correlation is made clearer when comparing standardized test scores by spending ranges per student (displayed in Scores by School Spending Per Student); as the per student budgets increase, the percentage of students who passed their math and/or reading tests decreases. 

- **Having a smaller school size may have a more beneficial impact on student performance.** When comparing the top and bottom 5 performing schools in the district, the top performing schools tended to have smaller student bodies (between 962 - 2,283 students) than bottom performing schools (between 2,917 – 4,761). This pattern is shown also in the table Scores by School Size; as the number of students increases, the percentage of students who passed their math and/or reading tests decreases. 

## Recommendations
Future analysis should look deeper these trends to understand why charter schools tend to do better than district schools despite having lower per student budgets on average. For example, the district should examine whether a school’s average class size, and/or the ratio between the number of students to the number of teachers, influence student performance on standardized tests. 

## Contact
**Angela Angulo** -- anguloag@vcu.edu
