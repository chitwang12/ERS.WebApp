# ERS.WebApp
**Employee-Review-System**
A full stack, app used for reviewing employee. Hoisted Link :https://soumyasri7978-github-io-project.onrender.com/users/sign-in

**Description**
A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.

**Tech Stack**
Node , Express, Mongodb , EJS , javaScript , html, css

**How to setup the project on local system**
Clone this project
Start by installing npm if you don't have it already.
Navigate to Project Directory.
After reaching the project directory you have to run the following the command.

To run the project , follow these queries
     npm install 
     npm start || nodemon index.js

**Features**
You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;

HomePage / Admin View
Home page / Employee view
Sign-Up
Sign-In
Forget Password
Assign Task
Employee List

Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |               |--->scss  
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->employeeSection.js
    |--->controllers-->|-->home.js
    |                  |-->review.js
    |                  |-->user.js
    |
    |               |-->assignedReview.js
    |--->models---->|-->myReviews.js
    |               |-->user.js
    |
    |              
    |               |-->employeeSection.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->header.ejs
    |              |---> assignwork.ejs
    |              |---> employeeSection.ejs
    |              |---> .ejs
    |--->views---->|--->home.ejs
    |              |--->layout.ejs
    |              |--->signinPage.ejs
    |              |--->signupPage.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
