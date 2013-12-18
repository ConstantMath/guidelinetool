# Guidelinetool

A tool for creating Online Guidelines

---

## Installation

To install the Guidelinetool on a remote server, first copy all the files on the server root or in a subfolder.

Connect to phpmyadmin and create a new db and build the tables by uploading the install.sql file.


## Configuration
Open config.php in `/application/config`

#### Set the name of the Guideline

``` php
$config['gd_name']	= 'The Guideline name';
```

Open database.php in `/application/config` and set the following variables:

The hostname of your database server (ex:localhost)  
The username used to connect to the database  
The password used to connect to the database  
The name of the database you want to connect to  
``` php
$db['default']['hostname'] = 'hostname';
$db['default']['username'] = 'username';
$db['default']['password'] = 'password';
$db['default']['database'] = 'databasename';
```
