# Lab 4
Modify your lab3 to add the following features:
## Replace the static variable with a database
1. Define a database schema
2. Subclass the SQLiteOpenHelper 
3. Create your dao class and implement necessary CRUD operations.
4. Modify your previous UI code to list all projects in the database on the ProjectList screen. 
(If you do not have add project screen, you can pre-insert some records when creating the table.)
5. Modify your previous UI code to edit a project in the database and add projects into the database (optional).
6. You can also use any ORMs (such as Room Persistence Library ) if you want. 
## Show Favorite Projects
1. Add a show favorite projects only checkbox (or toggle button or switch) on the project list screen. 
2. This setting (whether it will show only favorite projects) should be stored into and received from the shared preferences so that it can be remembered across different sessions. 
3. If it is set, only list all favorite projects from the database. (_optional_)
## Submission
Submit the source code and Lab4report on both github and blackboard.
