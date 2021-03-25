
# E-Commerce Back-end

[![GitHub License](https://img.shields.io/badge/license-MIT-green)](License.md)

## Description

An application that provides a back-end server for an E-commerce website.

By using a REST client (such as Insomnia or Postman), the user is able to Get, Post, Put, or Delete data from a MySQL database.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [Walkthrough](#walkthrough)
* [Questions](#questions)

## Installation

Run the following command to install dependencies:

```
npm i
```

## Usage

* Update .env.EXAMPLE file
    * Rename file to .env
    * Update to your MySQL username and password
* Install dependencies
* Create the database using the schema
    * Use `mysql -u root -p` in command line
    * Enter password
    * Enter `source db/schema.sql`
* Seed the database
    * Use `npm run seed`
* Start the application
    * Use `npm start`
* Use a REST client for GET/POST/PUT/DELETE
* Use CTRL+C to exit the application!

## Technologies

* MySql
* Insomnia REST client
* Node.js
    * Express.js
    * Sequelizer
    * dotenv

## Walkthrough

[LINK TO WALKTHROUGH](https://drive.google.com/file/d/1NTzUzOLza3dJAfhGVyvx2_1vebA4VTtg/view)

## License

MIT 

## Questions

For any questions, please contact me by email or through my GitHub page
* [jamis.walsh@gmail.com](mailto:jamis.walsh@gmail.com)
* [NathanJamis](https://github.com/NathanJamis)
