# ORM E-Commerce
This project utilizes the sequelize package in order to create a back end for an ecommerce website. It creates a database filled with seed products of various categories, products, tags, and product tags. It takes a working Express.js API and configures it to use Sequelize to interact with a MySQL database. The following routes can be completed:

* GET all categories, products, or tags
* GET ONE category, product, or tag
* CREATE a category, product, or tag
* UPDATE an existing category, product, or tag
* DELETE an existing category, product, or tag

## Built With
* Express.js
* MySQL
* Seqelize
* Javascript

## Installation
* Go to ORM-E-Commerce repo
* Clone repo onto local machine
* Run npm install on terminal
* Create .env file in root of project to store MySQL credentials

## Usage
* Startup MySQL with mysql -u root -p
* Run command source db/scehma.sql
* Quit
* Enter npm seed to seed newly created database
* Run npm start to connect to the database
* Use Insomnia or similar application to test the routes

## Demonstration
See the below links for demonstrations of the application:

MySQL setup, Seed database, GET Routes: https://watch.screencastify.com/v/tvakcXTKkHpnGDEFBrdK

POST, PUT, DELETE Routes: https://watch.screencastify.com/v/FcEwrrBer6alNxc6c3HW



