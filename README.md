
## Project description

I have discovered some potential security issues involving login attempts and employee machines at a company. I examined the organization’s data in their employees and log_in_attempts tables using SQL filters to retrieve records from different datasets and investigate the potential security issues.

# Apply filters to SQL queries




## Retrieve after hours failed login attempts

I used the SQL query below to identify any failed login attempts (success = 0) after 6:00 pm using >. 

![alt_text](https://github.com/Kusht18/Filters-SQL-Queries/blob/main/pic1)



## Retrieve login attempts on specific dates

I used SQL query below to identify any login attempts on the specific dates of 2022-05-09 and 2022-05-08 so had  to use filter OR. 


![alt_text](https://github.com/Kusht18/Filters-SQL-Queries/blob/main/pic2)



## Retrieve login attempts outside of Mexico

I used SQL query below to identify login attempts outside of Mexico. Countries including MEX and MEXICO so had to include filter LIKE ‘MEX%’. 


![alt_text](https://github.com/Kusht18/Filters-SQL-Queries/blob/main/pic3)



## Retrieve employees in Marketing

Used SQL query below to retrieve all employees in Marketing departing working in East office buildings. Had to use AND and LIKE filters because there are multiple offices in the east. Ex. East-170 and East-195.


![alt_text](https://github.com/Kusht18/Filters-SQL-Queries/blob/main/pic4)



## Retrieve employees in Finance or Sales

Used SQL query below to identify employees in either Finance or Sales department using filter OR.


![alt_text](https://github.com/Kusht18/Filters-SQL-Queries/blob/main/pic5)



## Retrieve all employees not in IT

Used SQL query below to identify all employees not belonging to the IT department using NOT fitler.

![alt_text](https://github.com/Kusht18/Filters-SQL-Queries/blob/main/pic6)



