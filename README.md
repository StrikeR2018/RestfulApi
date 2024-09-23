List of Team Members

A description of the division of labor for the project between the members of your team (see below for more info about this).

```
● CharlieSay
● MingxuanLi
● GavinCorso
● JacobRedfern
```
Data Entities

●An outline of the data entities your API will store, including descriptions of the attributes you’ll store for each type of entity and of the associations that will exist between entities. You are encouraged to include an entity relationship diagram as a pictorial

●Users (Instructor/Students/Admin)

●Courses(Subject/Number/Title/Instructor)

○Students (List)

○Assignments (List)

●Assignments (course, title, due date)

○Student Submissions (List)

●Submissions (assignment, student, timestamp, content/filestatus, grade)



```
● Users(Instructor/Students/Admin)
● Courses(Subject/Number/Title/Instructor)
○ Students(List)
○ Assignments(List)
● Assignments(course,title,duedate)
○ StudentSubmissions(List)
● Submissions(assignment,student,timestamp,content/filestatus,grade)
```
![image](https://github.com/user-attachments/assets/54888d70-ca68-4039-9e11-7c5e1c587a6a)

List Services

●Powered by MySQL

●Utilizes docker to containerize and run the MySQL server.

●GitHub and GIt will be used for version control and workflow management.

●Redis & possibly Cloudflare to block IP addresses for rate limiting

●The API will be written in JavaScript

○Hosted on Node.js in an express server.

○Will interface with MySQL using Sequelize.

Division of Labor	
●  Create MySQL Docker container	- Gavin Corso
●	Create API Entities	- Gavin Corso
●	Implement API Actions	- Jacob Redfern
●	Implement API Pagination	- Gavin Corso
●	Implement API Authorization	- Charlie Say
●  Implement API Rate Limiting	- Charlie Say
●	Manage GitHub Repo	- Mingxuan Li
●Implement API File Upload/Storage - Mingxuan Li

●	Generate API tests	- Write tests for your own endpoints


