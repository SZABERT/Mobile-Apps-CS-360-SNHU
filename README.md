### App Requirements and Goals

The goal of this project was to create a fully functional Android application that followed user-centered design principles while demonstrating core mobile development concepts. 
I created a Weight Tracker app that allows users to log in, record their daily weight, update or delete previous entries, and receive optional SMS notifications when they reach their goal weight. 
The app was designed to give users a simple way to monitor their progress without unnecessary complexity.

### User Interface Design

The app includes a login screen, a weight tracking screen, an add/edit weight screen, as well as a notifications screen. 
I tried to keep each screen simple and easy to navigate by placing the most important actions where users would naturally expect to find them. 
Buttons are clearly labeled, information is grouped logically, and the navigation between screens is straightforward. 
Keeping the interface simple helped create a better experience for the user.

### Development Process

I approached development one feature at a time instead of trying to build the entire application at once. 
I started by creating the user interface before adding functionality such as the SQLite database, login system, CRUD operations, and SMS notifications. 
Breaking the project into smaller pieces made it much easier to troubleshoot problems and verify that each feature worked before moving on to the next. 
This is an approach I plan to continue using in future software development projects.

### Testing

I tested the application frequently using the Android Emulator after nearly every change I made. 
I verified that users could create accounts, log in successfully, add, update, and delete weight entries, and grant or deny SMS permissions without affecting the rest of the application. 
Testing throughout development helped me catch problems early and made debugging much easier than waiting until the end of the project.

### Challenges and Innovations

One of the biggest challenges was connecting all of the different parts of the application together. 
I had to make sure that activities, the SQLite database, and the user interface all worked together correctly. 
Another challenge was implementing CRUD operations and making sure edited weight entries updated existing records instead of creating duplicate ones. 
Working through those issues helped me better understand how Android applications manage data.

### Strongest Area

The part of the project I am most proud of is the database functionality. 
Successfully implementing SQLite along with complete CRUD operations gave me a much better understanding of persistent data storage in Android applications. 
By the end of the project, users could create accounts, securely log in, manage their weight entries, and have those changes saved between sessions, making the application fully functional.
