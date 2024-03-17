Step 1:

i) Set up your MySQL database
Install MySQL on your server if you haven't already.
Create a new database and a table to store your form data.

For example: 

CREATE DATABASE mydatabase;

USE mydatabase;

CREATE TABLE mytable (

    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50),
    email VARCHAR(50),
    message TEXT
);

Step 2:

Install XAMMPP server on you system if you haven't already.
Before starting Registering Details start the Apache and MYSQL on XAMMPP Control Pannel.
Lets 'see in the below image
![image](https://github.com/rupasrigithub/Connecting-HTML-Form-With-MYSQL-Database-Using-PHP/assets/140321029/9338ed8c-dfe9-40de-aee0-6dd02bf5320c)



