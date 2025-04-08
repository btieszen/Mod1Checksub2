  Mod 1 Lesson check, Todo App with AuthO
  This App has a AuthO login after login it redirects you to the Todo App
  You can add task , also there is a button to view task detail, edit and delete
  
1.  First step sign in to AuthO and create account and new project
2.  Create Application
3.  Name your App
4.  Create single page app

1. open Src Folder
2. to run app cd todo
3. npm run dev
4. Make sure the local host matches what is in The TODO folder in the AuthOProvider.Tsx

1. In the TODO app:
2. AuthOProvider.tsx containes the log in infor mation you will need to copy over from the AuthO file you created
3. The AuthenticationGuard.tsx  is used to protect the routes from unauthorized access
4. CallbackPage.tsx calls the app after successful login

In Components folder:
1. LoginButton.tsx this is the login button and redirects after login button is clicked
2.LogoutButton.tsd this logs the user out of the app
3. NavBar.tsx this sets up the navigation bar redirect
4. NavBarButtons.tsx this displays the login and log out button

In Pages Folder:
1.  Home-page.tsx this is the first page yuu see in the app that has logout to make sure the user is logged out then it give the login button
2.  PageLayout.ts this structure how the app looks

IN Todo folder there is another folder list
1.  Taskform.tsx this is the form to fill out to add task, description
2.  usinputs.ts  this save the value of the inputs
3.  TaskDiscrition.tsx  this get the info from input of the descrtiption of the task
4.  TaskList.style.ts this is the styling for the todo page
5.  TaskList.tsx this is the page set of for the todo app, it contains the task, the add task, new task,edit,view and delete
6.  Home.style.ts provides styling for the home page
7.  String.Json provides messages to ask the user if they want to delete or adds successful
8.  ToDoProvider.tsx provides the const to add or delete task
9.  Types.ts provides the typescritp information of the vlues is string,num, etc.
10.  
