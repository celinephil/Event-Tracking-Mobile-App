# Event Tracking App :date: - Android Mobile Application	

[![Generic badge](https://img.shields.io/badge/Language-JAVA-blue.svg)](https://www.java.com/en/) [![Generic badge](https://img.shields.io/badge/Database-SQLite-green.svg)](https://sqlite.org/index.html) [![Generic badge](https://img.shields.io/badge/IDE-Android_Studio-purple.svg)](https://developer.android.com/studio/)

:warning: APP IS CURRENTLY UNDER CONSTRUCTION FOR AN ENHANCED USER EXPERIENCE :warning:

## Overview
> Applied mobile development principles and best practices to develop a mobile application using user-centered design principles and industry standards. Upon completion of a fully-functional mobile application, I conducted security, product assuredness, and compatibility checks before launching the application.

## Scenario :memo:
This application will be used to track the dates and times of upcoming events. This application must include the following:

- A database with at least two tables, one to store the event details and one to store user logins and passwords
- A screen for logging into the app. Note that this should also be used to create a login if the user has never logged in before.
- A screen, with a grid, that displays all upcoming events
- A mechanism by which the user can add and remove events from the database
- A mechanism by which the user can enter the time and general information of a specific event
- A mechanism by which the application will notify the user on the day that an event has been scheduled

## App Code Design Functionality :bulb:	

* The app should check the username and password against the database when the user attempts to log in.
* If the user has never logged into the application before, the user should be able to create a new login and password. The application needs to save these to a table in the database.

* Create: The user should be able to add items to a database.
* Delete: The user should be able to remove items from a database.
* Update: The user should be able to change the value associated with individual database items (e.g. the number of a specific item in an inventory or the date of an event).
* Read: The user should be able to view all of the database items displayed as a grid.

* If the user grants permissions, the application should send alerts to the user as SMS messages. The alerts correspond to the specific notification trigger of the application you chose (low inventory, an upcoming event, or reaching a goal weight).
* If the user denies permission, then the rest of the application should still continue to function without the SMS messaging notification feature.

* Employ industry standard best practices such as in-line comments and appropriate naming conventions to enhance readability of code.

## Reflection :pencil2:	

The goal of the event tracking app is to implement code and construct an innovative UI through the Android Studio IDE. With this app, users can track upcoming or past events. This app was designed to address users of all kinds such as students who want to track school events or wedding planners with upcoming weddings.

The screens in the app include a login, register, create, notifications, and main activity. Features include buttons, swiping methods, and create (+) or delete buttons. My UI keeps users in mind by taking into account their perspective and what they would want to see in an event tracking app.

I was able to approach the process of coding my app by utilizing readings, online resources, and tutorials. These helped me but I encountered a few roadblocks that caused me to have an unfinished application. I tested to ensure my code was functional by running test usernames and passwords in the login and register form. I also purposely didnt insert sections such as the username or re-entering the password or even leaving the field empty. This process is important because it shows the developer what went wrong and what went right. It also shows them what they need to fix in their code or layout files. I honestly had to innovate throughout most, if not the entire development process. It was actually quite fun to do because it showed me the potential I have to build a fully working mobile application. Since this was my first time laying my hands on a mobile application IDE, it was a surreal experience. 

I was particularly successful in the login and register components. I probably jumped in happiness after getting my code to run in the way that I had wanted it to. I also think the UI of most of the xml layouts came out aesthetically pleasing especially when keeping user stories in mind. The spacing with the texts and buttons shows my skill and knowledge I gained throughout this course. 

Overall, I think it was more fun than stressful! I had a great time learning something new and Android Studio really helped open that door. Since this was my first time constructing and editing elements in a mobile development, it was interesting to see how it is for many mobile app developers who had to go through the phase that I went through. We all start somewhere and I’m glad that I am slowly but surely gaining practice, insight, knowledge, and experience in the mobile app development process.  

## App Screenshots :camera_flash:

<div style="text-align: center;">
    <img src="App Screenshots/Login Screen.png" width="400px" />
    <img src="App Screenshots/Register Screen.png" width="400px" />
    <img src="App Screenshots/Main Activity Screen.png" width="400px" />
    <img src="App Screenshots/New Event Screen.png" width="400px" />
    <img src="App Screenshots/Notification Screen.png" width="400px" />
</div>

---
*[Updated May 2023 by celinephil]*
