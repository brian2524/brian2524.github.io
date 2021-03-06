[Back to Portfolio](./)

Ruby on Rails Sample App
===============

-   **Class: Human-Computer Interaction (CSCI 334)** 
-   **Grade: A**
-   **Language(s): Ruby on Rails**
-   **Source Code Repository:** [sample_app](https://github.com/brian2524/sample_app)  
    (Please [email me](mailto:BTHinkle@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th Edition)
by [Michael Hartl](https://www.michaelhartl.com/). I followed this tutorial for creating a sample website. It is built using the MVC (Model-View-Controller) architecture with Ruby on Rails. It features a sigup/loggin system that interacts with a database to store users. Users can also update their profile by visiting the "Update your profile" page (Fig 4). Here they can change any information associated with their account as well as set a profile picture. The user can also discover people who are already registered on this website by visiting the "All Users" page (Fig 5).

## How to compile / run the program

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

To visit [*follow this link*](https://whispering-beach-83643.herokuapp.com/)

![screenshot](images/SampleApp1.PNG)
Fig 1. The Home screen

![screenshot](images/SampleApp2.PNG)
Fig 2. Sign up Page

![screenshot](images/SampleApp3.PNG)
Fig 3. User Profile

![screenshot](images/UpdateProfile.png)
Fig 4. Update your profile

![screenshot](images/AllUsers.png)
Fig 5. All Users page. Displays all profiles in the database.

[Back to Portfolio](./)
