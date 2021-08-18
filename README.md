# Pandas Challenge - PyCitySchools
### Objective
Develop a code using python and pandas to analyze Py City Schools' district-wide standardized test results and create summary tables to highlight trends in school performance. 

### Description of the Data: schools_complete and students_complete
Overall descriptive metricts for each school in Py City are contained in a csv file called "schools_complete". The dataset is organized into five columns: 
- School ID - the ID number for each school in the city
- School Name - the name of each school in the city
- Type - the school's type (either charter or district)
- Size - the number of students attending each school
- Budget - the budget for each individual school

The data for each student attending a Py City school are contained in a csv file called "students_complete". The dataset is organized into seven columns:
- Student ID - the ID number for each student in the city 
- Student Name - the name of each student in the city
- Gender - each student's gender (male or female)
- Grade - the grade each student is in (9th to 12th grade)
- School Name - the name of the school the student attends
- Reading Score - the student's numeric score (out of 100) on their standardized reading test
- Math Score - the student's numeric score (out of 100) on their standardized math test

### What the Code Should Do
The code should merge the data from schools_complete and students_complete into one dataset and should create the following summary tables:
- A District Summary, which includes the district's key metrics - Total Schools, Total Students, Total Budget, Average Math Score, Average Reading Score, % Passing Math (the percentage of students that passed math), % Passing Reading (the percentage of students that passed reading), % Overall Passing (the percentage of students that passed both math and reading) 
- A School Summary, which gives an overview of key metrics about each school - School Name, School Type, Total Students, Total School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing
- Top Performing Schools, which highlights the metrics included in the School Summary for the top 5 performing schools based on % Overall Passing
- Bottom Performing Schools, which highlights the metrics included in the School Summary for the bottom 5 performing schools based on % Overall Passing
- Math Scores by Grade, which lists the average math scores for students of each grade level at each school
- Reading Scores by Grade, which lists the average reading scores for students of each grade level at each school 
- Scores by School Spending, which compares school performance (Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, % Overall Passing) based on four reasonable groupings of average spending ranges per student
- Scores by School Size, which compares school performance based on reasonable approximations of Small, Medium, and Large school size
- Scores by School Type, which compares school performance based on school type
