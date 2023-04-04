#
Pembuat 
Nama :Fazlul Rachmat Mubbaraq

Asal Perguruan tinggi : Universitas Halu Oleo


📖 Cara Menjalankan
Clone repositori ini
```bash
git clone [https://github.com/ferdyhape/latihan_minibos_gits.git](https://github.com/fazlulrachmatmubbaraq/MSIB4-Tugas6.git)
```
Copy paste .env.example file dan ganti dengan .env

Sesuaikan nama database di env pada file DB_DATABASE

Generate Key
```bash
php artisan key:generate
```
Instal dependensi
```bash
composer install
```
Generate mirror link
```bash
php artisan storage:link
```
Migrate the tables
```bash
php artisan migrate
```
Masukkan data dari seeder ke database
```bash
php artisan db:seed
```
Menjalankan server
```bash
php artisan serve
```
Masuk dengan kredensial ini


Jika Anda ingin menggunakan peran admin :

email = admin@example.com
password = 123

Jika Anda ingin menggunakan peran User :
email = user12@example.com

password = 12345678
Anda juga dapat menggunakan fitur register, tetapi Anda tidak mendapatkan akses admin:
```bash
http://127.0.0.1:8000/register
```
Enjoy use!

⚙️ Stack yang digunakan:

:black_circle:Laravel 9

:black_circle:SweetAlert

:black_circle:Bootstrap 5.2

:black_circle:BootstrapIcon

:black_circle:BoxIcon


