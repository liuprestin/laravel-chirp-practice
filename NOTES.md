When developing applications using Sail, you may execute Artisan, NPM, and Composer commands via the Sail CLI instead of invoking them directly:

./vendor/bin/sail php --version
./vendor/bin/sail artisan --version
./vendor/bin/sail composer --version
./vendor/bin/sail npm --version


### To activate:
./vendor/bin/sail up

in another terminal:

./vendor/bin/sail npm run dev

have another terminal for regular works 

---

this project follows the 
Inertia-React path to setup Chirp:

https://bootcamp.laravel.com/inertia

---

php artisan make:model -mrc Chirp

creates:
- app/Models/Chirp.php - The Eloquent model.
- database/migrations/<timestamp>_create_chirps_table.php - The database migration that will create your database table.
- app/Http/Controller/ChirpController.php - The HTTP controller that will take incoming requests and return responses.

---

To list all the routes in an app use:

php artisan route:list 

---

localhost/chirps...

https://bootcamp.laravel.com/inertia/creating-chirps

---

php artisan migrate:fresh 

will rebuild the database tables from scratch 


---

https://laravel.com/docs/10.x/artisan#tinker