# React, Nodejs,MySQL CRUD Application

# Backend

> npm init -y

> npm i express mysql nodemon

* need to add this before running

  "type": "module"

* add this inside scripts

"scripts": {
    .......
    "start": "nodemon index.js"
  },

// this packege is for frontend backend CORS 

> >npm i cors

========================================================================================

# Database

SELECT * FROM sidd_crud.books;

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'SiddharthaS1995';

ALTER TABLE `sidd_crud`.`books` 
ADD COLUMN `price` INT NOT NULL AFTER `cover`;


======================================================================================

# Frontend

//If we want to create the app in the same folder
> npx create-react-app .

> npm start

> npm i react-router-dom

//Axios is for frontend backend connectivity
> npm install axios