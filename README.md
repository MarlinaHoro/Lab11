## Nama     : Marlina Horo
## Nim      : 312010250
## kelas    : Ti 20 A2

Sebelum memulai menggunakan Framework Codeigniter, perlu dilakukan konfigurasi pada webserver. Beberapa ekstensi PHP perlu diaktifkan untuk kebutuhan pengembangan Codeigniter 4. Berikut beberapa ekstensi yang perlu diaktifkan: • php-json ekstension untuk bekerja dengan JSON; • php-mysqlnd native driver untuk MySQL; • php-xml ekstension untuk bekerja dengan XML; • php-intl ekstensi untuk membuat aplikasi multibahasa; • libcurl (opsional), jika ingin pakai Curl.

## 1. Mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini

![1.png](img/1.png)

Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.

## 2. Instalasi Codeigniter 4

Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.

![2.png](img/2.png)

aktifkan bebarapa exetension seperti diatas.`

## 3. kemudia membuat file baru dengan nama lab11_php_ci

![3.png](img/3.png)

## 4. INSTALISASI CODINGITER 4

Untuk melakukan instalasi codeigniter 4 dapat dilakukan dengan dua cara , yaitu cara manual dan menggunakan composer. pada praktikum ini kita menggunakan cara manual.

Unduh Codeigniter dari website https://codeigniter.com/download Extrak file zip Codeigniter ke directori htdocs/lab11_ci. Ubah nama direktory framework-4.x.xx menjadi ci4 Buka browser dengan alamat
https://http://localhost/lab11_php_ci/ci4/public/

![4.png](img/4.png)

container telah berhasil didonwload

## 5.MENJALANKAN CLI (Command Line Interface)

Codeigniter 4 menyediakan CLI untuk mempermudah proses development. Untuk mengakses CLI buka terminal/command prompt.


![5.png](img/5.png)

Arahkan lokasi direktori sesuai dengan direktori kerja project dibuat (C:\xampp\htdocs\Lab11Web\lab11_php_ci\ci4)

Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah

![6.png](img/6.png)

php spark berhasil dipanggil


## 6. MENGAKTIFKAN MODE DEBUGGING

Codeigniter 4 menyediakan fitur debugging untuk memudahkan developer untuk mengetahui pesan erorr apabila terjadi kesalahan membuat kode program.

Secara default fitur ini belum aktif. Ketika terjadi erorr pada aplikasi akan ditampilkan pesan seperti berikut

![7.png](img/7.png)

Semua jenis erorr akan ditampilkan sama. Untuk memudahkan mengetahui jenis erorrnya, maka perlu diaktifkan mode debugging dengan mengubah nilai konfigurasi pada environment variable CI_ENVIRONMENT menjadi development.

## 7 Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable CI``_ENVIRONMENT menjadi development.

![8.png](img/8.png)



contoh erorr yang terjadi. Untuk mencoba erorr tersebut, ubah kode pada file app/Controller/Home.php hilangkan titik koma pada akhir kode.

![10.png](img/10.png)


## 8. Membuat rute Baru

Tambahkan kode berikut di dalam Routes.php


![11.png](ci4/public/img/11.png)

## 9. Buat file baru dengan nama about.php pada direktori view (app/view/about.php)

![19.png](img/19.png)

Ubah method about pada class Controller Page

![14.png](img/14.png)

![13.png](img/13.png)

halaman about

![17.png](img/17.png)

## 10. membuat file baru dengan contact.php

![20.png](img/20.png)


halaman contact 

![18.png](img/18.png)






