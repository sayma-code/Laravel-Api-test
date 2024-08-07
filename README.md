## Process

##### Command used
1. php artisan make:model Customer --all
   Created model with Factory, Migration, Seeder, Request, Controller, Policy.
2. php artisan make:model Invoice --all
3. Create one to many relationship between (customer to invoices).
4. Add needed data to Migration file.
5. Now for data create factories.
6. Include this factories in seeder.
7. Create the database( migrate with seed)
    php artisan migrate:fresh --seed
8. Add api to project
    php artisan install:api
    Add all the routes in api.php
9. Create resource file to change the namespace
    php artisan make:resource V1/CustomerResource
10. 
