# Sekilas Tentang Blogotext

_**Blogotext**_ merupakan salah satu blogging system, tujuan dari web ini adalah untuk memberikan aplikasi yang interaktif dan mudah bagi pengguna dalam berbagi di web. Salah satu yang menjadi kelebihan dari Blogotext adalah instalasi file yang tidak banyak menggunakan space hosting, dapat mengunggah dan mengunduh fail, support Addons, dan sebagainya.

# Fitur yang tersedia
-	Blog with comments and RSS feeds
-   Links sharing
-   RSS Reader
-   Images/Files uploading and sharing
-   JSON/ZIP/HTML import-export; WordPress import
-   Support [Addons](https://github.com/BlogoText/blogotext-addons)

# Instalasi

**Kebutuhan Sistem dan Perangkat :**

-   `PHP > 5.5`
-   `SQLite or MySQL with PDO support`
-   `A CSS3 / HTML5 / ES6 compatible Browser, for the admin panel (Firefox, Chrome…)`
-   `min 2 Mo disk space (more data = more space needed)`

## Rekomendasi untuk PHP

-   GD (for comments icons / favicons)
-   cURL (for RSS reader, links sharing, comments icons)
-   LibXML (for RSS reader)
-   GZip (for zip exporting function)
-   [Intl](http://php.net/manual/book.intl.php)
-   [mbstring](http://php.net/manual/book.mbstring.php)

**Proses Instalasi :**

-   _Update_ sistem dengan versi yang terbaru `$ sudo apt-get update -y`
    
-   _Install_ ssh `$ sudo apt update` lalu `$ sudo apt install ssh`
    
-   _Install_ apache, MySQL, dan PHP
```
$ sudo apt install apache2
$ sudo apt install mysql-server
$ sudo apt install php
$ sudo apt install libapache2-mod-php
$ sudo apt install php-mysql
$ sudo apt install php-gd php-mcrypt php-mbstring php-xml php-ssh2
$ sudo service apache2 restart
```
- Unduh [versi terakhir](https://github.com/BlogoText/blogotext/releases)
- Unzip berkas yang telah didownload `$ sudo unzip blogotext-3.7.6`
- Untuk mempermudah, ubah nama file menjadi blogotext dengan cara `$ sudo mv blogotext-3.7.6 blogotext`
- Selanjutnya buka [http://localhost](http://localhost) (localhost -> alamat IP atau URL anda). Untuk contoh : `http://localhost:8000/blogotext/admin`
- Ikuti langkah - langkahnya
- Login dengan menggunakan akun mysql
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-27-15.png></img>
- Maka akan muncul tampilan login dan siap digunakan, seperti berikut :
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-04-39.png></img>
## Konfigurasi

Untuk masuk ke menu konfigurasi, anda dapat klik gambar avatar di pojok kanan atas dan pilih menu settings. Maka akan muncul tampilan berikut :
![enter image description here](https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-18-33.png)

Admin dapat mengatur beberapa pengaturan yang terdapat di menu settings.

## Maintenance
Untuk mengakses maintenance, anda dapat memilih menu Maintenance di sub menu Maintenance, maka akan muncul tampilan berikut dan beberapa pilihan, sebagai contoh Cleanup database.
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-20-17.png></img>

## Cara Pemakaian

Untuk melihat artikel (dapat disort berdasarkan beberapa kategori), pilih menu my artikel. Maka akan muncul tampilan seperti berikut :
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-05-24.png></img>

Untuk mengedit artikel, dapat memilih judul artikel yang tersedia, maka akan tampil seperti berikut:
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-09-09.png></img>

Untuk membuat artikel baru, dapat memilih menu new article, maka akan tampilan seperti berikut:
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-06-12.png></img>

Untuk meng-upload file, dapat memilih menu files, akan tampil tampilan berikut:
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-09-46.png></img>

Tampilan setelah upload file:
<img src=https://raw.githubusercontent.com/jojowvan/Blogotext/master/screenshot-localhost%208000-2018-03-20-20-14-23.png></img>

## Pembahasan
**Blogotext** merupakan salah satu aplikasi _open source blog publishing_ dan _Content Management System (CMS)_ naungan _General Public License (GNU)_. Blogotext ditulis dalam bahasa pemrograman PHP. Proses instalasi Blogotext terbilang cukup mudah sehingga mempermudah untuk pengguna yang baru pertama kali mencoba.

**Kelebihan**

-   Instalasi mudah
-   Mendukung Addons
-   Mudah dalam penggunaan
-   Dapat upload file

**Kekurangan**

-   Terlalu sedikit fungsi yang ada
-   Kurang menarik
-   Proses yang agak rumit

## Perbandingan dengan Blogging Platform lain
Dibandingkan dengan blogging platform lain, contoh: Wordpress, Blogotext tidak memiliki integrasi dengan sistem atau aplikasi lain. Namun, fitur yang ditawarkan oleh Blogotext tidak jauh berbeda dengan Wordpress namun Wordpress lebih baik dalam segi tampilan maupun proses pemakaian. Blogotext tersedia dalam bahasa Inggris dan Prancis, sementara Wordpress hanya tersedia dalam bahasa Inggris.

## Referensi

1.  [Blogotext](https://github.com/BlogoText/blogotext) \- Blogotext
2.  [Blogotext](https://github.com/BlogoText/blogotext/releases) \- Lastest Release
3.  [Command in ubuntu](http://www.linuxandubuntu.com/home/10-basic-linux-commands-that-every-linux-newbies-should-remember) \- Ubuntu Help
4.  [What is WordPress](https://en.wikipedia.org/wiki/WordPress) \- Wordpress
