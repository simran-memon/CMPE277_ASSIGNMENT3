ASSIGNMENT_3:  Implicit Intent - WebLink and Phone Call App

Name: Simran Tanvir Memon
Student Id: 015950610

GitHub:  https://github.com/simran-memon/CMPE277_ASSIGNMENT3

Objective: The goal of the assignment is to apply implicit intent concepts and invoke web link & phone calls.

Implementation: Intents can be specified as asynchronous messages which allows application components such as activities, content providers, broadcast receivers, services, etc. to request functionalities from other android components.

There are two types of Intents:

1. Explicit Intent : Explicit Intent requires target’s app name or fully classified component class name to satisfy the intent.
2. Implicit Intent : Implicit Intent requires to declare a general action to perform, which will be satisfied by other components from another app.


In this assignment, we will see how implicit intents work through two examples by invoking web link and by calling a phone app.

1. This is the home screen of Android App which allows user to invoke the user entered URL and make call to the specified phone number.

![alt text](https://github.com/simran-memon/CMPE277_ASSIGNMENT3/blob/main/screenshots/homescreen.png?raw=true) 

2. If user clicks on Launch button without entering the URL, app throws a message to enter proper URL.

![alt text](?raw=true) 

3. I have used uri.parse() method to invoke the web url.

![alt text](https://github.com/simran-memon/CMPE277_ASSIGNMENT3/blob/main/screenshots/url.jpg?raw=true) 

![alt text](https://github.com/simran-memon/CMPE277_ASSIGNMENT3/blob/main/screenshots/url2.jpg?raw=true) 

![alt text](https://github.com/simran-memon/CMPE277_ASSIGNMENT3/blob/main/screenshots/urldisplay.jpg?raw=true) 

4. To make a phone call, app will ask user permission and then will direct the call to main phone app.

![alt text](https://github.com/simran-memon/CMPE277_ASSIGNMENT3/blob/main/screenshots/phone.jpg?raw=true) 

![alt text](https://github.com/simran-memon/CMPE277_ASSIGNMENT3/blob/main/screenshots/permissiontocall.jpg?raw=true) 

![alt text](https://github.com/simran-memon/CMPE277_ASSIGNMENT3/blob/main/screenshots/phonecall.jpg?raw=true)