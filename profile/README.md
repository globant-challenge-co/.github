# Globant Data Engineer Challenge

#High Level Architecture

<img width="1087" alt="Screenshot 2023-12-16 at 11 37 26 AM" src="https://github.com/globant-challenge-co/.github/assets/52805660/07cb67fc-8774-4e2b-b71d-1ce75bc36bbe">


This project was part of the globant challenge for data engineering, this consist in cloud architecture using AWS with an REST-API gateway connected to three lambdas:

**UploadFiles:** Let users to upload csv files to process them and upload to the posgres database.
**GetDeptJobsHiringStats21Q:** Returns an sql view that returns the number of employees hired for each job and department in 2021 divided by quarter. The table must be ordered alphabetically by department and job.
**GetTopDeptHiring21:** Returns an sql view that returns a list of ids, name and number of employees hired of each department that hired more employees than the mean of employees hired in 2021 for all the departments, ordered by the number of employees hired (descending).

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
