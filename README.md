# CRUD-Operations-with-Laravel
A project on how to perform create, read, update, delete actions with a database.

## Development Environment
1. Create Laravel app files:    
    `composer create-project laravel/laravel <project-name>`
2. Create database and configure environment
Create a database and configure the data base on the `.env` file

Prepare database migration classes for the target table.
    `php artisan make:migration create_<table-name>_table`
 
It will create a PHP Laravel migration class in the database/migrations path

3. Migrate the schema into the database
This creates tables into the database.
    `php artisan migrate`

4. Start the server
    `php artisan serve`

5. Create Laravel model
    `php artisan make:model NameOfModel`
This will create the following Model class into the `app/Model` directory

6. Create Laravel app controller
    `php artisan make:controller NameOfController`

7. Build layouts




