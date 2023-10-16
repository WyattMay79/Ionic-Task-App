# Ionic-Task-App
Building a simple working Task tracking app that allows you to keep your daily list in order.
***This application only works as long as the server is up and running! Data is persisted to the database, but is NOT accessible unless the server is running.*** 

This app allows you to create a list of ToDo's that are persistent and saved as long as the server is up and running. This project is a simple implementation of creating a server, database with Entity Frameworks and SQLite, and the frontend framework Ionic Angular. 

The implementation of this is easy and straightforward. 

When using this app, you need to have the lastest version of Node.JS, and .NET 7, Entity Frameworks, Angular, Ionic Angular w/ Capacitor is installed on your machine of choice. 

After that is done, you can then use this in whatever IDE you like (I use VSCode for creation and management of my applications) and run the commands ```npm restore``` in the task-client folder and ```dotnet restore``` in the task-api folder to get the updated packages for this project. This allows for the modules to be reinstalled and makes the app functional.

After that, you are able to use ```dotnet run``` to start the Kestrel server. Make sure you are in the correct directory to run this application! After the server is up and running, you can then use ```npm start``` 
 to then start the Ionic frontend application. After the terminal starts the app, you ```Ctrl + (click)``` the hyperlink in the terminal to launch the Ionic app and see the visuals in the default browser that you have. 

 The page displays a button the bottom right side of the page that allows you to add "Tasks" to the incomplete section of the page. 
 If you need to delete one of the tasks, simply swipe to the left on the task that you no longer wish to display and press the RED garbage can button and it will be deleted. 
 Once you complete the task, click on the checkbox or on the name of the task and it will automatically check the box and move the task to the completed section of the page. 
 The application also has able to update the page by pulling the page down. You will see the spinning wheel icon appear and the app will refresh, should there be any issues with tasks not changing or moving to the correct locations after deletion or completion.

 I hope this simple app helps and helps keep your days organized and productive!

 ***Without written expressed consent, this app or code is not allowed to be used in any production environment that brings about monetary gain in any way! NO EXCEPTIONS!!*** 
