# 🎦 Cinema 🎦
___
## :bulb: ***Project description***

    A simple version of the cinema web-application.
    Allows to manage movies, cinema halls, movie sessions.
    Also you can create your order by adding tickets to shopping cart.

## :scroll: ***Project structure***

    The project has an N-Tier Architecture.

+ *Dao* - all the work with the database takes place at this level;
+ *Service* - is responsible for the business logic of the application;
+ *Controller* - allows to user to work with this application.

## :exclamation: ***Features***

+ *Log in / Log out*
+ *Registration*
+ *Set Admin or User roles for each user(by default User role)*
+ *User can:*
    + browse list of movies
    + browse list of cinema halls
    + browse list of movie sessions
    + put tickets to shopping cart
    + complete order
+ *Admin can also find user by email and create or delete:*
    + movies
    + cinema halls
    + movie sessions    

## :books: ***Technologies***

+ *Java 11*
+ *MySql*
+ *Maven*
+ *Tomcat*
+ *Hibernate*
+ *Spring WEB*
+ *Spring Security*
+ *REST*
+ *SOLID principles*

## :desktop_computer: ***Quickstart***

1. Fork this repository
2. Copy link of project
3. Create new project from Version Control
4. Set the necessary parameters in resources/db.properties
```java
    db.driver=YOUR_DRIVER
    db.url=YOUR_DATABASE_URL
    db.user=YOUR_LOGIN
    db.password=YOUR_PASSWORD
```

5. Install Tomcat
6. Add Tomcat server to configuration and Fix it
7. Run project

![cinema](https://user-images.githubusercontent.com/24671785/197769432-556007e9-ad27-4cb3-a7f1-fdbaba6e3e9b.gif)
