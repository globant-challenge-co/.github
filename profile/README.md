# Globant Data Engineer Challenge

## Author

**Juan Sebastian Vargas Torres**
**Systems Engineer**

# High Level Architecture

<img width="1087" alt="Screenshot 2023-12-16 at 11 37 26 AM" src="https://github.com/globant-challenge-co/.github/assets/52805660/07cb67fc-8774-4e2b-b71d-1ce75bc36bbe">


This project was part of the globant challenge for data engineering, this consist in cloud architecture using AWS with an REST-API gateway connected to three lambdas:

**UploadFiles:** Let users to upload csv files to process them and upload to the posgres database.
**GetDeptJobsHiringStats21Q:** Returns an sql view that returns the number of employees hired for each job and department in 2021 divided by quarter. The table must be ordered alphabetically by department and job.
**GetTopDeptHiring21:** Returns an sql view that returns a list of ids, name and number of employees hired of each department that hired more employees than the mean of employees hired in 2021 for all the departments, ordered by the number of employees hired (descending).

For the deployment of the lambda functions it was used AWS Container Registry to push 3 different docker containers, where each one will be permforming each of the task mentioned above.
For the database it was used posgresSQL with AWS RDS having 3 tables: Deparments, jobs, hired_employeees.

## API

The API provides an base url which with send the requests to each lambda base on the three endpoints.

Base URL: `https://8xzqdc7k4e.execute-api.us-east-1.amazonaws.com/test/`


For the documentation of each endpoint please check the .Readme of each lambda in the current organization.

## Contact

- Email: libros123bmw@gmail.com
- LinkedIn: [Juan Sebastian Vargas on LinkedIn](https://www.linkedin.com/in/juan-sebastián-vargas-torres-9b4a15189/)


Feel free to reach out if you have any questions or feedback! 
Cheers🤘🏻
