Pembuat 
Nama :Fazlul Rachmat Mubbaraq
Asal Perguruan tinggi : Universitas Halu Oleo


📖 Cara Menjalankan
Clone repositori ini
#
git clone [https://github.com/ferdyhape/latihan_minibos_gits.git](https://github.com/fazlulrachmatmubbaraq/MSIB4-Tugas6.git)

Copy paste .env.example file dan ganti dengan .env

Sesuaikan nama database di env pada file DB_DATABASE

Generate Key
#
php artisan key:generate
Instal dependensi
#
composer install
Generate mirror link
#
php artisan storage:link
Migrate the tables
#
php artisan migrate
Masukkan data dari seeder ke database
#
php artisan db:seed
Menjalankan server
#
php artisan serve
#
Masuk dengan kredensial ini


Jika Anda ingin menggunakan peran admin :

email = admin@example.com
password = 123

Jika Anda ingin menggunakan peran User :
email = user12@example.com

password = 12345678
Anda juga dapat menggunakan fitur register, tetapi Anda tidak mendapatkan akses admin:
#
http://127.0.0.1:8000/register
Enjoy use!

⚙️ Stack yang digunakan:
Laravel 9
SweetAlert
Bootstrap 5.2
BootstrapIcon
BoxIcon


