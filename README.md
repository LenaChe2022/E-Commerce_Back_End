
# E-Commerce_Back_End

## Description

My motivation was to try my skills in creating a back end for an e-commerce site. My aim was to configure a working Express.js API using Sequelize to interact with a MySQL database.

During this project I used **Object-relational mapping (ORM)** to interact with databases using JavaScript. We can choose from many ORM tools, but for this project I use Sequelize, which enables us to communicate with MySQL using Node.js. It also helps make relationships between the data easier to recognize and leverage. Thus, we can observe how the data interacts much better than we could with plain SQL.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Tests](#tests)
- [Questions](#questions)

## Installation

To run this app follow steps:
* clone the repo to your computer;
* for using mysql in this app, enter yor uername and password in `.env.EXAMPLE` file and rename it to `.env`
* to install all nesessary packages (MySQL2 package, Inquirer package,console.table package) enter in CLI: `npm install`
* to create Database open the db folder in your CLI and enter the following to run mySql:
* `mysql -u root -p`
* then enter your SQL password
* enter `sourse schema.sql` in mysql CLI to create working DataBase and chose working DataBase by entering `USE ecommerce_db;`; After creating the DataBase you may quit MySQL in your Command line using comand `quit` and come back to your CLI.
* Run `npm run seed` or `node seeds/index.js` to seed data to the DataBase so that you can test the routes.
* The application will be invoked by using the following command in the Command line: `node server.js` or `npm run start`. You will see "App listening on port 3001!". The server listening on http://localhost:3001/api/
* In the end of work do not forget to stop server listening by using comand "control"+"C" of your keyboard in CLI.

## Usage

The following video demonstrate:
* how to start the application’s server; 
* GET routes for all categories, all products, and all tags being tested in Insomnia;
* POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.

Link to demo video: https://drive.google.com/file/d/1vVW1oMW5eakQE1Wvsm2bYlCJuhIpqPdR/view


## Credits

The starter code repository: https://github.com/coding-boot-camp/fantastic-umbrella


## License
  
  ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
  (https://opensource.org/licenses/MIT)

## Tests

N/A

## Questions

My GitHub profile: https://github.com/LenaChe2022

With additional questions contact me by email:
lenache2022@gmail.com
