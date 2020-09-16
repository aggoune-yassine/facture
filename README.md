When you are done with installation, copy the .env.example file to .env

$ cp .env.example .env

Generate the application key

$ php artisan key:generate

Add your database credentials to the necessary env fields

Migrate the application

$ php artisan migrate

Install node modules

$ npm install

Run the application

$ php artisan serve
