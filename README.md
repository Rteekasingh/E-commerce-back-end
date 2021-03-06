# E-Commerce Back End (Object-Relational Mapping Challenge)

## Table of Contents
* [Decription](#description)
* [User Story](#userStory)
* [Acceptance Criteria](#acceptanceCriteria)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)


  

### Description
The challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

### User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria
```
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
```

### Installation
The user should should first clone the respository from GitHub, then initialize the dependencies for Node.js, Express.js, and Sequelize:
- npm install
- npm install express sequelize mysql2


### Usage
To connect to the database, run mysql -u root -p in the commandline and enter the password from the .env file.  The user will then need to source the schema.sql, source db/source.sql.  Then seed the file, npm run seed.  Finally to connect the server, type in the commandline npm run start


### License
MIT
