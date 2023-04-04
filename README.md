# TUGAS 6 CMS | Studi Independen GITS ID

## Developer
- Name: ``` Ristian Naufal Apriliawan ```

- Campus: ``` Universitas Dian Nuswantoro ```

## :gear: Tools Used:

 - Laravel 9
 - Node.js
 - Bootstrap 
 
## Installation

### Requirements

Untuk persyaratan sistem Anda [Check Laravel Requirement](https://laravel.com/docs/9.x/deployment#server-requirements)

### Clone  repository dari github.

    git clone 

### Install dependencies

Laravel utilizes [Composer](https://getcomposer.org/) untuk mengelola dependencies. Jadi, sebelum menggunakan Laravel, pastikan Anda telah menginstal Composer di komputer Anda.

    cd YourDirectoryName
    composer install

### Config file

Rename or copy `.env.example` file to `.env`. Kemudian jalankan perintah `php artisan key:generate` untuk generate app key.

### Database

- Migrate database table dengan perintah berikut `php artisan migrate`
- `php artisan db:seed`, ini akan menginisialisasi pengaturan dan membuat pengguna admin untuk Anda [email: admin@gmail.com  - password: admin123]

### Install Node Dependencies

- Jalankan perintah `npm install` untuk menginstall node dependecies
- Jalankan perintah `npm run dev` untuk development atau `npm run build` untuk production

### Create storage link

- Jalankan perintah `php artisan storage:link` untuk membuat tautan penyimpanan

### Run Server

- Jalankan perintah `php artisan serve` untuk menjalankan aplikasi 
- Kunjunngi server `http://127.0.0.1:8000` pada browser anda. Email: `admin@gmail.com`, Password: `admin123`.