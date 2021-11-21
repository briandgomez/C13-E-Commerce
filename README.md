# E-Commerce Back End

## Description
This project involves creating the back end for an e-commerce website. Just like e-commerce websites this project involves a user requesting for a specific item and returning the appropriate response. A response could be the requested information in JSON format or an error message. The database for this project was created using MySQL where models were given associations. Using Insomnia Core the API routes were tested and performed RESTful CRUD operations. The reason for creating this is to create a minimal viable product that online retailers can use for their business.

## Successful Request Example
![image](https://user-images.githubusercontent.com/69539559/142778416-8964374f-1c4d-4500-8daa-0d3f2d6411dd.png)

## Tools
This project was created using the following:
* Sequelize 
* Express.js
* Node.js
* Javascript ES6
* MySQL

## Installation
In order to use the application users need to install Node.js, Express.js, sequelize, and MySQL. To connect to the database users must provide the information from a
.env file when running 'mysql -u root -p'. Theen to create the database users must run 'source schema.sql' while in MySQL. To seed the database run 'npm run seed'. Lastly to connect to the server run 'npm start'.

## Walkthrough Links
Create and connect to database:
https://watch.screencastify.com/v/yH1D1YqTufO3z922kt63

API Routes:
https://watch.screencastify.com/v/YZYkv9FWklMek0hSzOPc
