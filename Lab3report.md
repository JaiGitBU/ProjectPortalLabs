# CS683 Lab3 Report 
### Jai K. Gurung
## Design and Implementation
I modified the layout design and the implemented the component design architecture to accomplish the data insertion, manipulation, and deletion. Data persistence Room has been implemented for storing and retrieving data. Recycler view has been used for holding list of projects and relative layout within the Card view is used for holding detail view of each project other objects. 
Setting up the layout, database, and implementing the editing functions were the three major issues I ran into.
1.	Projects UI
a.	This screen is where list of the added Projects will be displayed.
b.	Adding a Project: There must be at least one Portal existed prior to adding any Project. (+) add button is located at the bottom-right corner of the screen. This button will take user to the “Add Project” screen where user will be allowed to fill all the Project’s details. Users must assign the Project to a Portal by double clicking on “Project ID” field and selecting the desired Portal from the Portals list. Once all the required fields are filled, user can save it by clicking “Save” icon at the top right corner of the “Add Project” screen.  
c.	Deleting a Project: User can click and swipe to the left or right on the Project that needed to be deleted

d.	Deleting all Projects: “Delete All Projects” menu is located at the top right corner of the screen.  If user clicks this menu, it will delete all the list of the existing Projects permanently without warning. 
e.	Editing a Project: Each row represents a Project. It contains Project’s title, start and end date. User can click on the Project that needed to be edited. Once clicked, it will take user to the “Edit Project” page or the “Detail view” page where user can edit Project’s information. This page also displays all the Projects associated to the Project if existed. After required changes are made user can click “Save” icon at the top-right corner of the “Edit Project” page.
i.	Editing an associated Favorite: Each row represents a Favorite. User can click on the Favorite that needed to be edited. Once clicked, it will take user to the “Edit Favorite” page or the “Detail view” page where user can edit Favorite’s information. After required changes are made user can click “Save” icon at the top-right corner of the “Edit Favorite” page.
f.	Saving Changes: Once the adding and/or editing tasks are completed, user can save the changes by clicking “Save” icon at the top-right corner of the screen.



## Testing: 
Screens shots shown below 
          



