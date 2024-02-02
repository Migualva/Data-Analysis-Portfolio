# Data-Analysis-Portfolio
Hello! I'm Miguel and this is my Data Analysis portfolio. This overview only provides brief descriptions of each project. For a comprehensive understanding, it is recommended to explore each project individually for more detailed insights. Thank you for reading!


## Index
- [Portfolio Projects](https://github.com/Migualva/Data-Analysis-Portfolio/blob/main/README.md#portfolio-projects)
  - [Proyect 1: Students Performance in Exams](https://github.com/Migualva/Data-Analysis-Portfolio/blob/main/README.md#proyect-1-students-perfromance-in-exams)
  - [Proyect 2: Student Stress Factors: A Comprehensive Analysis](https://github.com/Migualva/Data-Analysis-Portfolio/blob/main/README.md#proyect-2-student-stress-factors-a-comprehensive-analysis)
  - [Proyect 3: Power Bi - Flights Analysis](https://github.com/Migualva/Data-Analysis-Portfolio/blob/main/README.md#proyect-3-power-bi---flights-analysis)
## Portfolio Projects
## [Proyect 1: Students Perfromance in Exams](https://github.com/Migualva/Students-Performance-in-Exams)

**Code:**  [students-performance-in-exams.ipynb](https://github.com/Migualva/Students-Performance-in-Exams/blob/main/students-performance-in-exams.ipynb) 

**Raw data:** [StudentsPerformance.csv](https://github.com/Migualva/Students-Performance-in-Exams/blob/main/StudentsPerformance.csv)

**Description:** Beginning with a dataset that contains comprehensive information about students' performance on three exams, each covering different subjects. The aim of this analysis is to understand how students' grades can be improved by examining factors such as parental level of education or participation in a test preparation course. An introduction initiates the analysis, followed by data preparation, as some columns become handy being different data types with no loss of information on the process. Subsequently, data visualization techniques are employed to illustrate distributions, including boxplots, pie diagrams, and barplots. Some examples:

![image](https://github.com/Migualva/Data-Analysis-Portfolio/assets/95355380/8d0919cf-efe4-48a3-86de-b4b129c414ea)
![image](https://github.com/Migualva/Data-Analysis-Portfolio/assets/95355380/95de30fb-5efc-4340-b0e9-afb0d135456a)
![image](https://github.com/Migualva/Data-Analysis-Portfolio/assets/95355380/da318262-a8ed-4778-b159-438d63ebb8d7)

Finally, after a thorough analysis of all factors involved, the project ends with a correlation analysis and conclusions. 
![image](https://github.com/Migualva/Data-Analysis-Portfolio/assets/95355380/fc9c7f42-8940-4834-b7e8-6611edbd6ad7)



## [Proyect 2: Student Stress Factors - A Comprehensive Analysis](https://github.com/Migualva/Student-Stress-Factors-A-Comprehensive-Analysis)

**Code:**  [student-stress-factors-a-comprehensive-analysis.ipynb](https://github.com/Migualva/Student-Stress-Factors-A-Comprehensive-Analysis/blob/main/student-stress-factors-a-comprehensive-analysis.ipynb)

**Raw data:** [StressLevelDataset.csv](https://github.com/Migualva/Student-Stress-Factors-A-Comprehensive-Analysis/blob/main/StressLevelDataset.csv)

**Description:** This dataset contains 20 features, selected scientifically considering 5 major factors -  Psychological, Physiological, Social, Environmental, and Academic Factors. The goal of this project is to reveal how each one influences the student. Understanding its impact can be meaningful to identify key areas for interventions and psychological support. First, simple questions by the dataset creator are answered, visually on some degrees, to help showcase the differences on each feature. Some examples:

![image](https://github.com/Migualva/Data-Analysis-Portfolio/assets/95355380/a0d293e3-293e-427d-8408-7359c4420662)
![image](https://github.com/Migualva/Data-Analysis-Portfolio/assets/95355380/0f76d248-8f51-47b3-b846-84c187a1af4b)

However, as the project develops, the focus moves onto the 5 major factors, rather than only the 20 features. Therefore, questions become harder, as now we have to consider each feature, inside each factor, trying to understand which is more important or which has the higher impact on anxiety levels. In order to do this, scikit is the desired tool.

![image](https://github.com/Migualva/Data-Analysis-Portfolio/assets/95355380/674cc3fc-679b-4387-999a-a188c3c728e5)

After all of this, conclusions are drawn from results obtained on this analysis.

## [Proyect 3: Power Bi - Flights Analysis](https://github.com/Migualva/Power-BI-Flight-Analysis/tree/main)
Using data from https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018 selection year 2009 to 2011.

Before the report review, the query editor had to be used to ETL the data. As three years were used, all of the tables were anexed before this cleaning went through. This list includes a brief analysis on some steps: 
- Data types. Most columns used integer values to represent variables that would be suitable on text. Such as Cancelled Status, Arrival Status or Departure Status.
- Data cleaning. While importing the data to Power BI, some data switches from integer to decimal, gaining an additional 0 on the process (this is just one example of all this process)
- New columns. Some columns hold information valuable to divide into new columns. Date on the original file is DD/MM/YY, while a column for each value is quicker and easier to manipulate.
- Data preparation. Renaming columns to make the understanding easier, or deleting columns that now became obsolete.

This report contains two pages. The first one being a general Overview with basic and overall information (total flights, time spent on air, distance, total airports, etc). Also, it contains three buttons to switch information quicker for a deeper understanding. The first button applies filters to select years, while the second and third allow to switch from Destination information to Origin information (regarding Airports). Lastly, a top button can be pressed to switch easily to a Delay Analysis.
![image](https://github.com/Migualva/Power-BI-Flight-Analysis/assets/95355380/3a69cea5-7c0b-4456-b11e-efceb623643b)

On the second page, the delay analysis shows all the relevant information about this topic. Also, it allows to filter Airlines, years (as the previous page, with the same filter) and two buttons to switch between Arrival and Departure information aswell.

![image](https://github.com/Migualva/Power-BI-Flight-Analysis/assets/95355380/850b0774-83b1-496e-b9b8-1d75ea6ac944)
