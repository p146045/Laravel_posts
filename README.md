Instructions.

In order to run the project. You need to run the mysql using MAMP or XAMP. then create database of your own choice and edit the database and user credentials in composer.json.
After that ***assuming composer is already installed*** run command **composer install**. 
Then run command **php artisan migrate** in order to create necessary tables.
After that run **php artisan serve**
By default you could locate to **localhost:8000** in order to view the project
