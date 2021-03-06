# Eat-Da-Burger 🍔🍟
https://pacific-anchorage-71196.herokuapp.com/

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

## Functionality 💪
#### Here's how the app works: 
1. Welcome to Bobs Burgers! 😋

    1.1 In the 'Ready to Eat' box on the left side of the page is a list of burgers waiting to be eaten. When the user clicks 'Eat me', the burger will move to the 'Already Eaten' box on the right side of the page.

    1.2 This app stores all burgers in a database and can be deleted using the delete button next to the burgers in the 'Already Eaten' box.

    1.3 At the bottom of the page is an input box where the user can type in a burger of their choice. Once they hit submit, their burger will be moved into the 'Ready to Eat' box on the left side of the page. 

## Getting Started 🏁

These instructions will get you a copy of the project up and running on your local machine for grading and testing purposes. 

1. Clone repository. Click on the clone button next to the repository (clone with SSH). 
2. Open Terminal and git clone (paste) into directory of your choice. 
3. Open folder in VS Code. 
4. The `config` folder holds the `connection.js` file with the MYSQL connection and exports it for ORM to use.
5. `orm.js` holds the logic for updating the database table using CRUD. Create, read, update and delete. 
6. The `db` folder holds the table information.
7. `models` folder holds the `burger.js` file which imports ORM and creates functions to interact with the database. 
8. `public` holds the assets, css, images and the javascript connecting to the html
9. The `views` folder has all of handlebars files, which sends data from the backend to the front
10. `server.js` connects the app to the server and the correct port. 

## Pre-Requisites ✔️

1. Node - use this site to install node into your computer: https://nodejs.org/en/download/
    *to check if node is installed type node -v into your terminal. If installed it will print the version number on the screen.
2. NPM (https://www.npmjs.com/) - Node Package Manager. Use this site to assist in downloading packages or modules. 

## Built With 🔧

* [Node](https://nodejs.org/en/download/) - As an asynchronous event driven JavaScript runtime, Node is designed to build scalable network applications. 
* [Javascript](https://www.javascript.com/) - JavaScript is the programming language of HTML and the Web
* [JSON](https://www.json.org/) - Javascript object notation, syntax for storing and exchanging information. 
* [Express](https://www.npmjs.com/package/express) - Node.js web app framework designed to make developing websites, web apps, & API's much easier.
* [MySQL](https://www.mysql.com/) - Open source relational database management system (RDBMS) based on Structured Query Language (SQL)
* [Handlebars](https://handlebarsjs.com/) - Handlebars allows you to separate the generation of HTML from the rest of your JavaScript and write cleaner code.
* [ORM](https://stackoverflow.com/questions/1279613/what-is-an-orm-how-does-it-work-and-how-should-i-use-one) - Object-Relational Mapping is a technique that lets you query and manipulate data from a database using an object-oriented paradigm.
* [MVC](https://www.geeksforgeeks.org/mvc-design-pattern/) - The Model-View-Controller is an architectural pattern that separates an application into three main logical components: the model, the view, and the controller.
 

## Author ⌨️
*** Amanda Dovel *** - [amandadovel](https://github.com/amandadovel)

## Acknowledgments 🌟

* Amber Burroughs, Tutoring badass