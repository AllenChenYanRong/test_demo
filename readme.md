## init

* add your computer name to setting.
	* in bootstrap/start.php , add computer name to $app->detectEnvironment

* quick run

on command:

	php artisan serve --port 11000

## what's target?

1. create a table "users" , contains fields: id, name(String), balance(decimal(15,4), default 0), soft delete,timestamps

2. add field "description" to "users" , type: text.

3. add some seed data to users. at least 5 rows.

4. create controller "UserController" with "view" and "report" method. add 2 routes "/user/view" and "/user/report"

5. create view user_view.php and user_report.php. just put simple table in there.

6. call url "/user/view/<user id>" will appear this user all info in table.

7. call url "/user/report" will appear a user list which contains all users in table.

## document for Laravel

* Quickstart

http://laravel.com/docs/4.2/quick

* DB migration: create table, add field

http://laravel.com/docs/4.2/schema

* Seed Data

http://laravel.com/docs/4.2/migrations#database-seeding

* Routing

http://laravel.com/docs/4.2/routing

* Requests and Input

http://laravel.com/docs/4.2/requests

* View and Responses

http://laravel.com/docs/4.2/requests

* DB Query

http://laravel.com/docs/4.2/queries

* Bootstrap, jQuery and FontAwesome

public/css and public/js

