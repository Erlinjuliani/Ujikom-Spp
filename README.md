<p align="center">
    <h1>Aplikasi Pembayaran SPP</h1>
</p>

## Tentang Aplikasi Pembayaran SPP

Aplikasi ini memiliki 3 hak akses level login, yang diantaranya :

Level Admin
- Login
- Logout
- CRUD data siswa
- CRUD data petugas
- CRUD data Kelas
- CRUD data SPP
- Entri Transaksi Pembayaran
- Lihat Histori Pembayaran
- Generate Laporan

Level Petugas
- Login
- Logout
- Entri Transaksi Pembayaran
- Lihat Histori Pembayaran

Level Siswa
- Login
- Logout
- Lihat Histori Pembayaran

## Cara Install Project Aplikasi Pembayaran SPP via GIT

$ git clone https://github.com/Erlinjuliani/UJIKOM-SPP.git<br>
$ cd pembayaran-spp <br>
$ composer update <br>
$ php artisan migrate --seed <br>
$ php artisan serve <br>

Catatan :
lakukan terlebih dahulu pembuatan database dengan nama db_spp sebelum melakukan migrate.

## Akun Untuk Login

Level Admin
- email        : adminspp@gmail.com
-  password : admin

Level Petugas
- email       : petugasspp@gmail.com
- password : petugas

Level Siswa
- NISN  : 070702200200
- Nama : Erlin Juliani