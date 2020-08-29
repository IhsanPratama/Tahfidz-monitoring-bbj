# Tahfidz-monitoring-bbj
Tahfidz monitoring awardee BBJ 2020

untuk demo 
http://bit.ly/MiniProjectIhsanBBJ10

INSTALASI TAHFIDZ MONITORING
dibuat dengan framework laravel
masih perlu perbaikan ,
Persiapkan Xampp / Aplikasi Local Server Sejenis
jalankan mysql pada xampp
Install Composer, Download di https://getcomposer.org/
Restart komputer jika selesai instalasi jika perlu
Masuk ke direktori program tahfidz monitoring
Lakukan perintah pada cmd. composer update
Copy .env.example dan buat file pada direktori yang sama .env
Masih pada file .env file yang baru, ganti DB_DATABASE isi dengan tahfidz DB_USERNAME isi dengan root DB_PASSWORD kosongkan | (atau sesuaikan dengan xampp anda)
lalu jalankan perintah php artisan migrate kemudian

jalankan php artisan db:seed

CARA PENGAKSESAN

masih pada cmd di direktori tahfidz ketikan perintah php artisan serve
Akses 127.0.0.1:8000
Masukkan user: admin
pass : admin
(USER LEVEL CREATOR)

