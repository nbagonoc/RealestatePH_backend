## RealestatePH

RESTful backend API for RealestatePH using Laravel

## How to run locally:

- Download dependencies:
```
composer install
cp .env.example .env
php artisan key:generate
setup your database in the .env file
php artisan migrate
php artisan jwt:secret
php artisan db:seed
```

- Serve by running:
```
php artisan serve
```

- Backlog:
```
manage(update) profile (authenticated)
include userID in the listings Like object
manage(create, update, delete) review/rate an agent (authenticated)

manage(create available booking timeslots, book timeslot, cancel booking timeslot) viewing (none MVP)
```
