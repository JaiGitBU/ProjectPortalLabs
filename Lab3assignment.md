# Lab 3
Based on your previous lab, add the following features:
## The ProjectList Screen
1. Add a ProjectList screen to list all projects in your project using RecycleView and cardview. You can just display the project title in the list as we did in the lecture example. 
2. Add the communication between the projectlist screen and your project detail screen that you completed in lab2, so that when you click on a project in the ProjectList screen, the corresponding project detail will be displayed, including project title, description, authors, links and whether you like the project.
## The AddProject Screen 
1. Add another AddProject screen to allow the user to add a new project and detailed information about that project into the system. You can implement it using either Activity or Fragment. It will be easier to implement it using Activity.
2. Connect the AddProject Screen to the Project. For example, add a "+" Button in the ProjectList Screen, when clicking on it, it goes to the AddProject screen. If you implement it using Activity, you can use a simple intent to switch to the AddProject screen. 
3. On the AddProject screen, you can use a submit button. When it is clicked, the new project should be added, and it will switch back to the ProjectList screen. (_optional_)
## The EditProject Screen (_Optional_)
1. Add Another screen EditProject using either Activity or Fragment to allow the user to edit the project information. You will need to use EditText widgets so that the project details can be edited.
2. Connect the EditProject Screen to the Project. For example, add a Edit Button in the ProjectDetail Screen, when clicking on it, it goes to the EditProject screen. Depending on whether you implement the EditProject Screen using Activity or Fragment, you will need use different methods to communicate between the ProjectDetail screen and the EditProject Screen. 
## Submission
Submit the source code and lab3report to both github and blackboard. 
