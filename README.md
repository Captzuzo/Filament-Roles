# Laravel 12 + Filament + Spatie Role Permission

Filament-Roles ini dibangun menggunakan **Laravel 12**, **Filament Admin Panel**, dan **Spatie Laravel Permission** untuk manajemen hak akses. Menggunakan **PHP 8.3.3** dan **MySQL** sebagai database utama.

---

## 🧰 Teknologi yang Digunakan

-   PHP 8.3.3
-   Laravel 12.x
-   MySQL
-   Filament v3 (Admin Panel)
-   Spatie Laravel-Permission
-   TailwindCSS (melalui Filament)
-   Eloquent ORM
-   Laravel Blade & Livewire

---

## 📦 Fitur Utama

-   Manajemen User
-   Role & Permission menggunakan Spatie
-   Panel Admin dengan Filament
-   Middleware berbasis role
-   Responsive UI dengan TailwindCSS

---

## 🚀 Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/nama-kamu/nama-project.git
cd nama-project
```

## 2. Install Composer

composer install

## 3. Atur .env sesuai contoh menggunakan mysql

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database
DB_USERNAME=root
DB_PASSWORD=

## 4. Migrasi Database dan Seeder

php artisan migrate
php artisan db:seed

## 4. Jalankan Server

php artisan serve

## 5. Login

email : admin1@admin.com
password : password
