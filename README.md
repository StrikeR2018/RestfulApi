ListofTeamMembers
Adescriptionofthedivisionoflaborfortheprojectbetweenthemembersofyourteam(see
belowformoreinfoaboutthis).

```
● CharlieSay
● MingxuanLi
● GavinCorso
● JacobRedfern
```
DataEntities
● AnoutlineofthedataentitiesyourAPIwillstore,includingdescriptionsoftheattributes
you’llstoreforeachtypeofentityandoftheassociationsthatwillexistbetweenentities.
Youareencouragedtoincludeanentityrelationshipdiagramasapictorial

```
● Users(Instructor/Students/Admin)
● Courses(Subject/Number/Title/Instructor)
○ Students(List)
○ Assignments(List)
● Assignments(course,title,duedate)
○ StudentSubmissions(List)
● Submissions(assignment,student,timestamp,content/filestatus,grade)
```

ListServices
● PoweredbyMySQL
● UtilizesdockertocontainerizeandruntheMySQLserver.
● GitHubandGItwillbeusedforversioncontrolandworkflowmanagement.
● Redis&possiblyCloudflaretoblockIPaddressesforratelimiting
● TheAPIwillbewritteninJavaScript
○ HostedonNode.jsinanexpressserver.
○ WillinterfacewithMySQLusingSequelize.

DivisionofLabor
● CreateMySQLDockercontainer -GavinCorso
● CreateAPIEntities -GavinCorso
● ImplementAPIActions -JacobRedfern
● ImplementAPIPagination -GavinCorso
● ImplementAPIAuthorization -CharlieSay
● ImplementAPIRateLimiting -CharlieSay
● ManageGitHubRepo -MingxuanLi
● ImplementAPIFileUpload/Storage -MingxuanLi
● GenerateAPItests -Writetestsforyourownendpoints


