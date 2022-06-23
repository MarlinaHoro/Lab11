# PRAKTIKUM 12

## Framework Lanjutan (CRUD)


1. Membuat Database

![1.png](img1/1.png)

Konfigurasi koneksi database
Selanjutnya membuat konfigurasi untuk menghubungkan dengan database server.
Konfigurasi dapat dilakukan dengan du acara, yaitu pada file app/config/database.php
atau menggunakan file .env. Pada praktikum ini kita gunakan konfigurasi pada file .env.

![2.png](img1/2.png)

2. Membuat Model
Selanjutnya adalah membuat Model untuk memproses data Artikel. Buat file baru pada
direktori app/Models dengan nama ArtikelModel.php

![3.png](img1/3.png)

3. Membuat Controller
Buat Controller baru dengan nama Artikel.php pada direktori app/Controllers.

![4.png](img1/4.png)

![4.1.png](img1/4.1.png)

![4.2.png](img1/4.2.png)

4. Membuat View
Buat direktori baru dengan nama artikel pada direktori app/views, kemudian buat file
baru dengan nama index.php.

![5.png](img1/5.png)

Selanjutnya buka browser kembali, dengan mengakses url http://localhost:8080/artikel

![6.png](img1/6.png)

8. Belum ada data yang diampilkan. Kemudian coba tambahkan beberapa data pada
database agar dapat ditampilkan datanya.
menggunakan cmd

![7.png](img1/7.png)

9. Membuat View Detail
Buat view baru untuk halaman detail dengan nama app/views/artikel/detail.php.

![8.png](img1/8.png)

10. Membuat Menu Admin
Menu admin adalah untuk proses CRUD data artikel. Buat method baru pada
Controller Artikel dengan nama admin_index().

![9.png](img1/9.png)

Akses menu admin dengan url http://localhost:8080/admin/artikel

![10.png](img1/10.png)

Kemudian buat view untuk form tambah dengan nama form_add.php

![11.png](img1/11.png)


![12.png](img1/12.png)


11. Mengubah Data
Tambahkan fungsi/method baru pada Controller Artikel dengan nama edit().

![13.png](img1/13.png)


![14.png](img1/14.png)


12. Menghapus Data
Tambahkan fungsi/method baru pada Controller Artikel dengan nama delete().

![15.png](img1/15.png)













