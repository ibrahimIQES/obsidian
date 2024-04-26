
 7/2/2024
### Deeper Flowchart
Next step i need you to do more on deep level like "Do action" or "Process action" What those real process.  
  
Example for staff claims -> import employee, how the flow will like.  
  
Sample :  
Upload the file -> get the data from excel -> verification with database -> Show error -> etc....
Do more deep level, so you will get more deeper understanding on whole system
This is testing on your Knowledge, understanding and logic
No need have any images for your flowchart, but a deep and easy understanding flowchart needed
### Backend Portal
Based on this 4 system, i believe you have the basic idea on "Backend portal"  
So another task, i need you to build a Basic Backend portal using Laravel 9.  
  
-> Administrator management  
-> Role and Permission control  
-> Audit Trail  
-> General Settings

This will start testing on your skillset on development
** the basic backend portal will be the "Template" for you to build any kind of system on top of it in future.  
  
So you must make sure this portal have the strong base structure for you to do the extend modulars on future and speed up on works
# 21/3/2024

check
>https://trello.com/b/e6y54Szz/farmeria-warehouse-production

| feature  | task                                                                             |            |
| -------- | -------------------------------------------------------------------------------- | ---------- |
| location | -for structure control<br>submenu<br>-facility/warehouse <br>-floor<br>-room<br> | **onhold** |
| product  | TBD                                                                              | **onhold** |
| customer | TBD                                                                              | **onhold** |


setup simple API , push to git 

# 24/4/2024


| task                                                  | describtion                                                                                                                                                                                                                                                                                                      | checklist |
| ----------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| building management CRUD                              | submenu:<br>- facility (building)<br>- floor <br>- room<br>(each farm has building, inside building got many floor, on each floor got multiple room). <br>use prefix for the table<br>- pivot with handheld user table,<br>- user need permission to access facility, floor, and room.<br>- add observer for log |           |
| handheld user crud                                    | for mobile user<br>- add observer for log                                                                                                                                                                                                                                                                        |           |
| check the api response, must return proper <br>format |                                                                                                                                                                                                                                                                                                                  |           |
| change the route name from 'app' => 'api'             |                                                                                                                                                                                                                                                                                                                  |           |
include authentication for APIs  & timeout 

>ask din the sourcecode for jwt 

>return method ,
header need  to check the format of returned data 
