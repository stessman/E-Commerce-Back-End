# Unit 13 Homework : E-Commerce-Back-End
Table of Contents
- [Images](#image-examples)
- [Description](#description)
- [Installation](#installation-instructions)
- [Requirements](#requirements)
- [Usage](#usage-information)

## Image Examples
<img src="public\assets\img\E_commerce_get_all.PNG">
<img src="public\assets\img\E_commerce_get_one.PNG">
<img src="public\assets\img\E_commerce_post.PNG">
<img src="public\assets\img\E_commerce_put.PNG">
<img src="public\assets\img\E_commerce_delete.PNG">

## Description
This project was created as an example for an E-commerce back-end. This is for knowledge purposes on how to work with sequelize and routing.

## Installation Instructions
Open the Command Prompt and change your directory to the top level of this application. Once at that directory, verify that you have the package.json file. If you do not, run 'npm init -y.' Once this is completed you will need to run 'npm i'. Next you will need to navigate to the database schema(db/schema.sql) for this project and copy this code into your MySQL WorkBench to create the database. Once the database is created you will need to run 'npm run seed' at the top level of the project terminal to seed data into your database.
Once this is done you should be good to go.

## Requirements
- When the user adds their database naem, MySQL name, and MySQL password to an environment variable file, then they are able to connect to a database using Sequelize.
- When the user enters schema and seed commands, then a development database is created and is seeded with test data.
- When the user enters a command to invoke the application, then the server is started and the Sequelize models are synced to the MySQL database.
- When the user opens API GET routes in Insomnia Core for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.
- When the user tests API POST, PUT, and DELETE routes in Insomnia Core, then they are able to successfully create, update, and delete data in their database.


## Usage Information
Firstly verify that all instillation instructions are completed. Open the terminal at the top level of the project and run 'npm start' to start the server. Open Insomnia Core so that you can make requests to the server and see the responses. The base level route for this project is localhost:3001/api. From there you can add /categories, /tags, or /products and from there do GET requests to  get all of that type of request. From there you are able to GET things by id by adding another / followed by it's id number. You are also able to POST, PUT, AND DELETE routes using Insomnia Core. 

Link to app usage video: [E-Commerce Back End](https://drive.google.com/file/d/1JawjhhPOr8_rR7GIS1PjU9WSGm40IYHk/view)