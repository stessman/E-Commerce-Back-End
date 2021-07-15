# Unit 13 Homework : E-Commerce-Back-End
Table of Contents
- [Images](#image-examples)
- [Description](#description)
- [Installation](#installation-instructions)
- [Requirements](#requirements)
- [Usage](#usage-information)

## Image Examples
<img src="public\assets\img\Note_Taker_Landing.PNG">
////////////////////////////////////////////////////////////////

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
When on the landing page the user can click on the "Get Started" button to navigate to the note taking page. Once there, the user is able to see previously made notes in the left-hand column of the page. The user is able to click on a previous note in the left-hand column of the page to see that note fill in the right-hand side of the screen. If the user wants to create a new note, then they can click the "+" button in the navigation bar to start the process. Once that is done, the user needs to add in a title and some note text for their note. When they are done they can click the Save button in the navigation bar to save their note. They can then see their saved note in the left-hand column of the screen.
//////////////////////////
Link to app usage video: [E-Commerce Back End]()/////////////////////