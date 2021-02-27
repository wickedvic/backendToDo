# README

Front End Repo: https://github.com/wickedvic/Frontend-toDoApp

Demo Video: https://youtu.be/6waENH5mTiA

Summary: A web app that allows for users to create/edit/delete tasks, keep track of them on a calendar, and have a fully functioning login and signup with validations
- Developed Javascript/Redux front-end and a Rails/Active-Record/Postgres back-end application 
- Authenticated users at login by encrypting identifying account information via JWT. Also used B-CRYPT to hash user passwords and created a sign up function for new users
- Implemented Date-FNS for Calendar feature and Google React Login to allow users to login/signup with gmail information 


The application’s main goal should be to hit CRUD (CREATE, READ, UPDATE, DESTROY).

1. Users will be routed to the login page when they enter locksleyr.com
2. Users are required to create an account to navigate the functionality of the app
3. Once an account is created, Users can see their Calendar
4. A user upon creating an account has a secure password (courtesy of the bcrypt gem)
5. Users can make a new task and it will update on to the weekly calendar
6. Users can interact with the mini calendar and it will dynamically render the weekly calendar as well
7. Users can edit and delete a task
8. Users can cross off a task once it is completed

*Easter Egg: When a task is completed it shoots confetti onto the page*

Calendar Image:(https://user-images.githubusercontent.com/70414907/109398435-f1e6ca00-790a-11eb-86f6-b9ad3037d373.png)

Above is a snippet of what a user will see when they first create an account and have not made any tasks yet.

We had set it up so that when any user first goes locksleyr.com they are automatically routed to the sign up page. Here, users are prompted to sign up in order to use the functionality of the application. Once a user is created, they will now have the ability create tasks and and have a personalized calendar to keep track of their day to day responsibilities. The end goal of this application is to allow a platform for users to have a virtual agenda book which they can populate with whatever activities they choose to have. Additionally, we implemented bcrypt and JWT Auths in order to secure passwords and logins. In other words, a user cannot sign into someone else’s account and see their calendar/tasks.
