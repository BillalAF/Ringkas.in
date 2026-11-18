# ringkas.in

Aplikasi web berbasis PHP untuk memperpendek tautan panjang menjadi URL ringkas dan mengarahkan pengunjung ke alamat tujuan asli.

## Fitur Utama

* Pemendekan tautan panjang (URL shortening) secara otomatis dengan kode unik acak.
* Pengalihan (HTTP redirect) otomatis dari tautan pendek ke URL asli.
* Penghitungan jumlah klik (click counter) pada setiap tautan yang dibuat.
* Validasi format URL untuk mencegah tautan rusak atau tidak valid.

## Teknologi yang Digunakan

* **Backend:** PHP [ISI VERSI, misal: 8.1+]
* **Database:** MySQL / MariaDB
* **Web Server:** Apache (dengan dukungan `mod_rewrite`) atau Nginx
* **Frontend:** HTML, CSS, JavaScript, BulmaCSS

## Prasyarat Sistem

Sebelum menjalankan proyek ini di komputer lokal atau server, pastikan kamu sudah menyiapkan:

1. PHP versi 8 atau lebih baru beserta ekstensi `mysqli` atau `pdo_mysql`.
2. Database server MySQL atau MariaDB.
3. Web server (Apache dengan `mod_rewrite` aktif) atau PHP built-in server untuk pengujian lokal.

## Cara Instalasi

1. **Unduh repositori ini**
   ```bash
   git clone [https://github.com/](https://github.com/)[USERNAME-KAMU]/ringkas.in.git
   cd ringkas.in
