# Todo App
Simple Todo app developed in Laravel to try CRUD functions

## Getting Started

**Requirements:**

 - Wampp
 - Laravel 5.4.36
 - Composer 1.10
 
 **How to run**
 
- Clone this Github repo to `wamp64/www/Todo-CRUD-Laravel`  
- Navigate to the directory
- Install Composer Dependencies `composer install`
- Create a copy of your .env file `cp .env.example .env` 
- Generate an app encryption key `php artisan key:generate`
- Create an empty database for our application and add it to `.env` file
- Migrate the database `php artisan migrate`
- Start Server `php artisan serve` and open address in browser

**Routes**

'/' - Default Laravel homepage
'/todo' - List of all todos and main application page

**Screenshots**

![Blank List](https://imgur.com/QTespzk)


![Filled List](https://imgur.com/2ifXGzi)
