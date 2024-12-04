# Express • [TodoMVC](http://todomvc.com)

> Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

&ndash; _[Express](https://expressjs.com/)_

## Resources

- [Website](https://expressjs.com/)
- [API Reference](https://expressjs.com/en/4x/api.html)

## Description
Taskifyer: {Your Simple and Efficient To-Do List App}

Taskifyer is a web application that helps you manage your tasks and stay organized. It provides a user-friendly interface for creating, editing, and marking tasks as completed.

>Features:
Create Tasks: Easily add new tasks to your list.
Edit Tasks: Modify existing tasks as needed.   
Mark as Done: Check off completed tasks for a sense of accomplishment.
CRUD Operations: Taskifyer utilizes CRUD (Create, Read, Update, Delete) functionality to manage your tasks effectively.

>Benefits:
Improved Productivity: Organize your tasks effectively and stay focused on what needs to be done.
Streamlined Workflow: Easily track your progress and avoid missing deadlines.
Simple and Clean Interface: User-friendly design ensures a smooth and intuitive experience.   


## Implementation

In contrast to a typical [TodoMVC](https://todomvc.com) app, this app does not
utilize a frontend JavaScript framework or make use of client-side capabilities
such as `localStorage`.  Instead, it illustrates how to build a todo app using
a backend for application logic and persistence, along with HTML forms for
interaction.

This app is built using [Node.js](https://nodejs.org/) along with the [Express](https://expressjs.com/)
web framework.  Data is persisted to a [SQLite](https://www.sqlite.org/)
database.  HTML pages are rendered using [EJS](https://ejs.co/) templates, and
are styled using vanilla CSS.  HTML forms are used to modify data, rather than a
RESTful API.  That being said, the forms serialize data in a format inspired by
[Todo-Backend](https://todobackend.com/).

To run this WebApp, clone the repository and install dependencies:

```bash
$ git clone https://github.com/markimooo/web-app.git
$ cd todos-express-sqlite
$ npm install
```

Then start the server:

```
$ npm start
```

Navigate to [`http://localhost:3000`](http://localhost:3000).

The scaffolding for this app was generated using [Express application generator](https://expressjs.com/en/starter/generator.html):

```bash
$ express -v ejs web-app
```

Created by [[Denmark Galima]]
