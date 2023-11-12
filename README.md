# Object-Relational Mapping (ORM): E-commerce Back End

## Contents
[Description](#description)

[User Story](#user-story)

[Acceptance Criteria](#acceptance-criteria)

[Installation](#installation)

[Usage](#usage)

## Description 
This application serves as the server-side foundation for an e-commerce website. It includes initial code that needs to be developed into a fully functional Express.js API. The primary objective is to set up this API so it can communicate effectively with a MySQL database using Sequelize, which is an ORM (Object-Relational Mapping) tool. By doing so, the app will be able to handle data for products, orders, users, and other e-commerce functionalities, allowing for operations such as adding new products, updating existing ones, processing orders, and managing user accounts. The end result will be a backend system capable of supporting the various transactions and interactions an online marketplace requires.
GitHub repo URL: https://github.com/Sarkissian321/ORM-back-end

### User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria 
```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation
To run this application:

1. Clone this repository
2. Run ```npm i``` to install all dependencies
3. Invoke app with ```node server.js``` 

## Usage
https://github.com/Sarkissian321/ORM-back-end/assets/142841411/f534b312-57dc-4021-b47f-8180277bc684



