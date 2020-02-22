### requirement
kebutuhan untuk menjalankan program ini:
- PHP >= 7.1.3
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP extension
- XML PHP Extension
- Ctype PHP Extension
- JSON PHP Extension
- BCMath PHP extension
- composer
- Browser that supports ES6 syntax

### cara memasang program

ketika berada di directory web server(htdocs, http, www, etc.)

```
https://github.com/MuhammadAkmalFahlevi/LaravelSaya

```
masuk ke folder git yang baru saja di-clone

```
cd ./XAMPP/htdocs/AyoLaravel
```

lalu jalankan perintah

```
composer global require laravel/installer
```

lalu buat file .env baru, copy seluruh kode yang berada di .env.example dan sesuaikan konfigurasinya dengan pc anda.

jalankan perintah

```
php artisan key:generate
php artisan migrate
```

untuk memulai program dengan data yang sudah disediakan, import file .sql yang sudah dilampirkan 

### menjalankan program

untuk menjalankan program ini, jalankan perintah 
```
php artisan serve
```
di root project, lalu buka http://localhost:127.0.0.1:8000/
