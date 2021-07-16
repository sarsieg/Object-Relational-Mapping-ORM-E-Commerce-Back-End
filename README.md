# Object-Relational-Mapping-ORM-E-Commerce-Back-End

# Table of Contents
* [Challenge](#challenge)
* [User Story](#user-story)
* [Acceptance Critiera](#acceptance-criteria)
* [Walk Through](#walk-through)
* [Installation](#installation)
* [Technologies Used](#technologies-used)
* [Usage](#usage)
* [License](#license)

### Challenge
This challenge is to build the back end for an e-commerce site. I will take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

### User Story
> AS A manager at an internet retail company\
> I WANT a back end for my e-commerce website that uses the latest technologies\
> SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria 
> GIVEN a functional Express.js API\
> WHEN I add my database name, MySQL username, and MySQL password to an environment variable file\
> THEN I am able to connect to a database using Sequelize\
> WHEN I enter schema and seed commands\
> THEN a development database is created and is seeded with test data\
> WHEN I end the command to invoke the application\
> THEN my server is started and the Sequelize models are synced to the MySQL database\
> WHEN I open API GET routes in Insomia Core for categories, products, or tags\
> THEN the data for each of these routes is displayed in a formatted JSON\
> WHEN I test API POST, PUT, and DELETE routes in Insomnia Core\
> THEN I am able to successfully create, update, and delete data in my database

## Walk Through
[Walkthrough Videos]()

## Installation
In the root directory of the project, type in the terminal command line 'npm i' to download the dependencies. Initiate the database with 'mysql -u root -p', then 'source db/schema.sql' to create the tables. Exit the mysql terminal and from bash, type 'npm run seed' to seed the data into your tables. Now you can run 'npm start' to start your server.

## Technologies Used
* inquirer
* mySQL2
* exress
* dotenv
* sequelize
* nodemon
* JavaScript

## Usage
1. install npm init -y
2. npm i
3. npm i inquirer
4. npm i mysql
5. npm i dotenv
6. npm i nodemon
7. connect mySQL workbench and your JavaScript file
8. run npm run seed
9. run start

## License 
MIT License

Copyright (c) 2021 Sarah Siegel

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
