# pandas-challenge

This repository contains all data corresponding to the Data Analytics Bootcamp Python Challenge homework.

# PyCitySchools Analysis
I was tasked with aggregating a city's school district data, and analyse trends within the student populations reading and maths scores data based on school size, school budget, and school type.

* The reference .csv files can be found at: **[PyCitySchools/Resources/](https://github.com/sarahcasauria/Python-challenge/blob/main/PyCitySchools/Resources/)**

* The Python script can be found at: **[PyCitySchools/PyCitySchools_Notebook.ipynb](https://github.com/sarahcasauria/Python-challenge/blob/main/PyCitySchools/PyCitySchools_Notebook.ipynb)**

## Report Summary
### Observation 1 - School Budget Trends
To observe any relationship between student overall passing rate and spending rate per student across each school within the district, I categorised spending into four numerical ranges, and averaged the overall passing rate for each school within each range.

Based on the data output, the schools who fall into the lowest category of spending per student have a higher average overall passing rate, and we observe a downward trend as the spending budget per student for each school increases. From this data, we may assume that there is a negative correlation between a school's budget per student and the overall passing rate.

### Observation 2 - School Type Trends
To observe any relationship between student overall passing rate and school type (District or Charter), I calculated the mean of the overall passing rate for each school within each school type.

Based on the data output, Charter schools, on average, produce higher maths and reading scores compared to District schools. Charter schools also have a higher percentage of students passing maths, reading, and passing overall, compared to District Schools.