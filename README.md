Selamat Datang Ke Repo Saya Yang Noob ni.

Ok kalau nak guna untuk sistem baru JKR, boleh guna repo ni ye.

Step 1: 
JANGAN KLON!!!
Forkkan(duplicate) so repo ni akan ada as YOUR project di github account kamu.

Step 2:
Dah fork, KLON kan ke dalam local laptop.

Step 3:
Konfigure .env fail anda

Pastikan ada database ini:
- sumber (untuk MYKJ database)
- database korang la

PASTIKAN settle database dulu

Step 4:
Run command2 ni, PASTIKAN .env ANDA DAH KONFIGURE. Kalau X buat, Isa Datang

composer install
php artisan key:generate
php artisan config:cache
php artisan migrate
php artisan db:seed

php artisan serve (kalau tiada virtual host)

Ada user admin di dalam
username: 111
password: 123123123

Ini untuk login sso je. Kalau ada perubahan flow, ubah la, tapi JANGAN ubah repo ni, repo ni untuk FORK je supaya laju la sikit development korang
