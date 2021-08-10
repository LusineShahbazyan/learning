# Project with React, Express, MySQL

At first please install the  ***onlineshop***  folder in your local computer                                                  
https://github.com/NaneNare/VSU-ITC-1/tree/Lusine/project

### Mysql
Log in to MySQL by running the following command:                                                               
mysql -u root -p

Create user with username  "newuser"  and password  "$Password123"                                                
by running the following command:                                                 
CREATE USER  newuser@'localhost' IDENTIFIED BY  '$Password123';

Create database with name  "reactshop" by running the following command:                             
CREATE DATABASE reactshop;

To exit the database
ctrl+Z

To bind the database to the project
mysql -u newuser -p reactshop < /path/to/onlineshop/products.sql 

### Install dependencies for server
npm install

### Install dependencies for client
npm run client-install

### Run the client & server with concurrently
npm run dev

### Server runs on http://localhost:5000 and client on http://localhost:3000

### Functional Specification Document
Go to [FSD](https://docs.google.com/document/d/1ScTjC0TPUkKFHOnRSIoKOG10LRMOKcFBom0zeYezeqE/edit?usp=sharing)
