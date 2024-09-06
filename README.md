# Database Connection Project

This project is a **PHP** application that connects to multiple databases, such as **MySQL**, **PostgreSQL**, and **SQL Server**. The application allows basic CRUD (Create, Read, Update, Delete) operations on a sample table.

## Main Files

- `index.php`: Main application file.
- `mysql.php`: File for MySQL database connection and manipulation.
- `pgsql.php`: File for PostgreSQL database connection and manipulation.
- `mssql.php`: File for SQL Server database connection and manipulation.

## Prerequisites

To run this project, you will need:

- PHP 7.4 or higher
- MySQL 5.7 or higher
- PostgreSQL 12 or higher
- SQL Server 2017 or higher
- Apache or Nginx server
- Composer (if there are managed dependencies)

## Installation

1. Clone this repository:
   
   git clone https://github.com/lilicoAlmeida/database_testing_php.git
   cd database_testing_php
   
Set up your web server (Apache or Nginx) to point to the project directory.

Configure the database connection files (mysql.php, pgsql.php, mssql.php) with your credentials.

## Install the project dependencies (if any):

composer install

Create the necessary tables in the databases. An example SQL script can be found here.

## Usage

## Connecting to MySQL
To connect to MySQL, edit the settings in the mysql.php file and ensure the database is running.

## Connecting to PostgreSQL
Similarly, configure the pgsql.php file to connect to PostgreSQL.

## Connecting to SQL Server
Use the mssql.php file to connect to the SQL Server database.

## Running the Application
After setting up the connections, access index.php via the browser to start the application.

## Directory Structure

/database_testing_php

   ├── index.php 
 
   ├── mysql.php  
  
   ├── pgsql.php   
  
   ├── mssql.php   
  
   └── README.md   
  
   
## Contribution

Fork the project.

Create a new branch (git checkout -b feature/new-feature).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Open a Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

Agora o README está traduzido para o inglês e pronto para ser adicionado ao seu repositório no GitHub: [https://github.com/lilicoAlmeida/database_testing_php](https://github.com/lilicoAlmeida/database_testing_php).







