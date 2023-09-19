# E-Commerce-Back-End

## Description

This is a program built with MySQL2, Sequelize, and Express. It is a back-end application for an e-commerce site. E-commerce play sa significant role in consumerism in today's industry, so it is important to be able to build programs like this. This program retrieves information from a database and also allows the user to edit the database or delete from the database. Working on this allowed me to further my understanding of how to use api routes and seeding databases. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

- Install npm i for necessary dependencies (dotenv, express, mysql2, sequelize).
- Run schema.sql file using 'SOURCE db/schema.sql;' command in the root folder.
- Seed the database using 'node seeds/index.js' command in the root folder.
- Run the server using 'npm start' command in the root folder.
- Use Insomnia to test api routes!


## Usage

Once the user has seeded the database and started the server, they can open Insomnia and test the routes.The user can test their GET routes for categories, products, and tags using localhost:3001/api/DESIRED-ROUTE. Once this is fetched, the user should recieve the data for each route displayed in a formatted JSON. Additionally, the user can test their POST, PUT, and DELETE routes to create new data, update new data, and delete data in the database. 

[tutorial](https://drive.google.com/file/d/1uOmUQQQMWLeao8RIUPeZHOTZbl_bxYrJ/view )

## Credits

[npm sequelize](https://www.npmjs.com/package/sequelize)

## License

MIT License

Copyright (c) 2023 Caitlin Ash

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
