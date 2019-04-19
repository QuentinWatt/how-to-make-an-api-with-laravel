# How to make an API

This is a simple laravel API example including API versioning from my YouTube tutorial series on how to make an API.

[My YouTube Tutorial Series](https://www.youtube.com/watch?v=xYsUKrKe_OI&list=PL41lfR-6DnOppiHXkPKZ2tT1WBIjIufVs)

## How to set up this project

1. Clone this repo
2. cd into the directory
3. Run `composer install`
4. Run `php artisan key:generate`
5. Set up your `.env` file with the correct data (don't forget API_DOMAIN)
6. Run the table migrations `php artisan migrate`
7. Seed the database `php artisan db:seed`

Now you should have the same project I ended the series with.
