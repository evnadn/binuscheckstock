## TK 1 & 2 Team 4 Web Programming - Binus University
### Case TK 1
Buatlah aplikasi pendataan produk menggunakan Laravel untuk membuat proses create, read, update, dan delete (CRUD) sederhana. CRUD merupakan proses standar yang biasa ditemukan pada sebuah sistem aplikasi web. Berikut adalah user stories dari fitur CRUD yang akan kita buat:
- Pengguna memasukkan data sbb:
    - Data Produk: 
        - Produk
        - Deskripsi
        - Harga Beli
        - Harga Jual 
        - Gambar
    - Data User:
        - Nama 
        - TTL
        - Jenis Kelamin 
        - Password	
        - Retype password:
        - Email
- Aturannya adalah 
    - Pengguna harus login terlebih dahulu sebelum masuk ke aplikasi
    - Pengguna dapat melihat data produk dan data user.
    - Pengguna dapat memperbaharui / Edit data produk dan data user.
    - Pengguna dapat menghapus / delete data produk dan data user tertentu. 
   
### Case TK 2
Mengacu pada pembuatan aplikasi CRUD sebelumnya pada team assignment 1 nomor 3. Buatlah pengaplikasian user managementnya. 
Tugas Anda dalam penugasan ini adalah membuat aplikasi backend untuk manajemen pengguna. Beberapa aplikasi berbasis web backend membatasi akses hanya untuk mengizinkan pengguna dapat menggunakan aplikasi. Ini berarti ada mekanisme untuk memfilter pengguna (otentikasi) dan menetapkan beberapa fitur berdasarkan kategori pengguna (otorisasi). Adapun aturannya adalah:
- User biasa hanya dapat melihat data yang sudah dimasukkan oleh admin.
- Admin dapat memasukkan, mengedit dan menghapus data.

### Step by step using this project
- Clone project ini
- Jalankan "php artisan serve" 
    - Jika error silahkan lakukan "composer install" 
    - Copy ".env.exampel" dan ubah nama menjadi ".env" kemudian ubah nama database menjadi "checkstock"
    - Buat database baru dengan nama "checkstock"
    - Lakukan generate key "php artisan key:generate"
    - Lakukan "php artisan migrate" dan "php artisan db:seed"
- Login menggunakan : 
    - Role admin = admin@admin.localhost / admin  
    - Role user = user@user.localhost / user
