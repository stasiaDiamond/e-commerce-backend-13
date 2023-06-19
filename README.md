# e-commerce-backend-13

ORM E-commerce backend, Challenge 13 from UW Bootcamp

## Description

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Technologies Used

MySQL2, Sequelize, ExpressJS, dotenv, and Insomnia

## Installation

1. Clone the repo

2. Open integrated terminal to install packages:

* enter: npm init -y
* enter: npm i

3. Create the database:

* log into your mysql -uroot
* SOURCE db/schema.sql;
* quit

4. Seed the app:

* enter: npm run seed

5. Start the app:

* enter: npm start

## How To

Go over to insomnia to successfully test all routes

## Visuals

![Screenshot](/assets/Screenshot%202023-06-19%20at%2012.18.14%20PM.png)
