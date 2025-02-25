# WebDevServerSiteLab

A simple PHP CRUD application with routing built from scratch. This project is part of the Web Development Server Side module.

## Features

- Create and read user records
- MySQL database integration using PDO
- Form input sanitization
- Template-based layout
- Basic CSS styling

## Directory Structure

```
Root_Dir
|-- config.php
|-- common.php
|-- Install.php
|-- data/
    |-- init.sql
|-- src/
    |-- DBconnect.php
|-- public/
    |-- css/
        |-- style.css
    |-- templates/
        |-- header.php
        |-- footer.php
    |-- index.php
    |-- create.php
    |-- read.php
```

## Setup Instructions

1. Clone the repository
2. Configure your database credentials in `config.php`
3. Run `Install.php` to set up the database and tables
4. Access the application through `public/index.php`

## Requirements

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx) or PHP's built-in server
