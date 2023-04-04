📖 How To Use
Clone this repository

git clone [https://github.com/ferdyhape/latihan_minibos_gits.git](https://github.com/fazlulrachmatmubbaraq/MSIB4-Tugas6.git)
Copy paste .env.example file and rename as .env

Adjust the database name in the env file on DB_DATABASE

Generate Key

php artisan key:generate
Install dependencies

composer install
Generate mirror link

php artisan storage:link
Migrate the tables

php artisan migrate
Insert the data from seeder to database

php artisan db:seed
Start the server

php artisan serve
Login with this crediential

If you want to use admin role (can dashboard access):

email = admin@example.com
password = 123

If you want to use non admin role (can't dashboard access):
email = user12@example.com

password = 12345678
You can also use the register feature, but you don't get admin access (can't dashboard access):

http://127.0.0.1:8000/register
Enjoy use!

⚙️ Technology Used:
Laravel 9
SweetAlert
Bootstrap 5.2
BootstrapIcon
BoxIcon


