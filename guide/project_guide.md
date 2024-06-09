-   Daftar akun midtrans
-   Install laravel [ref](https://www.youtube.com/watch?v=4vwCjm5VLpo&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=2&t=7m18s)
-   Install midtrans [ref](https://www.youtube.com/watch?v=4vwCjm5VLpo&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=2&t=8m08s)
-   Ubah variabel env yang diperlukan (nama project, database, nama database, port, dll) [ref](https://www.youtube.com/watch?v=9u7To5v0Q4k&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=2&t=50s)
-   Tambahkan MERCHAN_ID, CLIENT_KEY dan SERVER_KEY (lihat di dashboard midtrans, di setting/access key) di env
-   Buat file midtrans.php di dalam folder config untuk memanggil merchan_id, client_key dan server_key di env tadi [ref](https://www.youtube.com/watch?v=9u7To5v0Q4k&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=2&t=2m45s)
-   Buat model dan controller untuk Order, dengan command:

    ```
    php artisan make:model Order -mc
    ```

-   Lakukan migrate untuk model dan controller Order yang telah dibuat, dengan command:
    ```
    php artisan migrate
    ```
-   Buat route untuk halaman utama [ref](https://www.youtube.com/watch?v=BIGWutJ6260&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=3&t=56s)
-   Buat controller yang diinputkan ke route halaman utama tadi, atur viewnya ke halaman order
-   Tambahkan cdn bootstrap [ref](https://www.youtube.com/watch?v=BIGWutJ6260&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=3&t=2m21s)
-   Buat route untuk checkout
-   Buat method controller untuk checkout di file `OrderController` [ref](https://www.youtube.com/watch?v=BIGWutJ6260&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=3&t=11m23s)
-   Tambahkan snap token dari dokumentasi midtrans ke method controller checkout tadi [ref](https://www.youtube.com/watch?v=BIGWutJ6260&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=3&t=14m31s)
-   Buat view untuk halaman checkout [ref](https://www.youtube.com/watch?v=BIGWutJ6260&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=3&t=18m14s)
-   Tampilkan popup pemayaran menggunakan configurasi snap popup mode [ref](https://www.youtube.com/watch?v=BIGWutJ6260&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=3&t=20m02s)
-   Buat method controller callback di order checkout untuk mengarahkan action setelah proses pembayaran berhasil dilakukan
    [ref](https://www.youtube.com/watch?v=069oMpRX9zA&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=4&t=3m0s)
-   Siapkan url aplikasi yang kita develop di hosting (https). Untuk versi gratis kita bisa memanfaatkan ngrok yang nantinya digunakan sebagai callback url untuk midtrans ketika pembayaran telah berhasil dilakukan [ref](https://www.youtube.com/watch?v=069oMpRX9zA&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=4&t=6m40s)
-   Tambahkan url yg sudah dipersiapkan tadi ke dashboard midtrans bagian [notifikasi payment](https://dashboard.sandbox.midtrans.com/settings/payment/notification) [url](https://www.youtube.com/watch?v=069oMpRX9zA&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=5&t=9m8s)
-   Buat fitur auto direct ketika berhasil transaksi maka user auto diarahkan ke halaman invoice [url](https://www.youtube.com/watch?v=069oMpRX9zA&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=5&t=17m37s)
-   Perbaiki bug nama user tidak muncul di snapshot pembayaran indomart [ref](https://www.youtube.com/watch?v=wa9GgebMOp4&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=5)
-   Perbaiki bagian hadle after payment di callback method di order controller
    [ref](https://www.youtube.com/watch?v=wa9GgebMOp4&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=5&t=3m32s)
-   Beli product vps NEO lite di biznet [ref](https://www.youtube.com/watch?v=E8hS2gMeLQQ&t=3m11s)
-   Buat SSH Key [ref](https://www.youtube.com/watch?v=E8hS2gMeLQQ&t=3m30s)
-   Buat config untuk SSH [ref](https://www.youtube.com/watch?v=E8hS2gMeLQQ&t=13m48s)
-   Install web server nginx di vps kita [ref](https://www.youtube.com/watch?v=4ftrM2DAohg&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=2)
-   Install php di dalam vps kita [ref](https://www.youtube.com/watch?v=WepMjxsmu70&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=3) [ref2](https://techvblogs.com/blog/install-php-8-2-ubuntu-22-04)
-   Install mariaDB di vps kita [ref](https://www.youtube.com/watch?v=OQ0pU-bvU2I&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=4)
-   Install mysql di vps kita [ref](https://www.youtube.com/watch?v=XVio1aNRMh0&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=5)
-   Install phpmyadmin di vps kita [ref](https://www.youtube.com/watch?v=wysXVmwRcZ4&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=6)
-   Beli domain [ref](https://www.youtube.com/watch?v=3Wqr2P1hhPU)
-   Setup Domain yng kita beli, agar terhubung dengan vps kita [ref](https://www.youtube.com/watch?v=BQOSRUGsbLo)
-   Install project laravel kita ke vps [ref](https://www.youtube.com/watch?v=a4l7XCIvNb4&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=9), pada saat melakukan setup project laravel ke vps kita mengalami error tepatnya di bagian instalasi `optimize-autoloader`. Ini [solusinya](#error-saat-install-composer-dan-menjalankan-comman-php-artisan-keygenerate)
-   Setting permission vps pada project laravel kita menggunakan `chmod` [ref](https://www.youtube.com/watch?v=sZ9a_CHJ53E&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=10)
-   Membuat subdomain pada vps [ref](https://www.youtube.com/watch?v=oYAfEV8kc5w&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=11), disini kita mengalami [error connection refused](#error-connection-refused) dan [error no aplication encryption key](#error-no-application-encryption-key-has-been-specified)
-   Membuat subdomain untuk phpmyadmin [ref](https://www.youtube.com/watch?v=oYAfEV8kc5w&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=11&t=5m12s)
-   Pasang ssl pada domain menggunakan certbot [ref](https://www.youtube.com/watch?v=jnAIiOWdBOU&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=12)
-   Pasang firewall di vps kita [ref](https://www.youtube.com/watch?v=h6XiX6TEStw&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=13)
-   Update Website Lewat GIT (Github) - Pull Request Dari VPS [ref](https://www.youtube.com/watch?v=N_7MAuMFJh8&list=PLBs-bxLCgCx95ukFoiMD5J6nzft3SJFKB&index=15)
-   Saat kita mencoba menjalankan user

### Error saat install composer dan menjalankan comman `php artisan key:generate`

Error yang muncul ketika kita melakukan command `composer install --optimize-autoloader --no-dev`:

```
Fatal error PHP: Kelas "Normalizer" tidak ditemukan di /usr/share/php/Symfony/Component/String/AbstractUnicodeString.php:31 Stack trace :
```

Masalah tersebut disebabkan oleh ekstensi PHP yang hilang atau rusak, khususnya ekstensi "intl" yang diperlukan oleh library Symfony. Dengan reinstall Composer dan menginstal ekstensi "intl", kita dapat menyelesaikan masalah tersebut.

Langkah - langkah penyelesaiannya:

1. Install ekstensi PHP "intl"
    ```
    sudo apt-get install php8.2-intl
    ```
    Ganti versi php sesui dengan versi php yang kita gunakan
2. Restart layanan PHP-FPM
    ```
    sudo service php8.2-fpm restart
    ```
    Ganti versi php sesui dengan versi php yang kita gunakan
3. Cek versi composer dengan command:
    ```
    composer -v
    ```

### error connection refused

begini respon errornya di terminal

```
SQLSTATE[HY000] [2002] Connection refused (SQL: select * from information_schema.tables wehre table_schema = laratranspay and table_name = migrations and table_type = 'BASE TABLE')
```

Solusinya ganti DB_HOST = 127.0.0.1 jadi localhost [ref](https://stackoverflow.com/questions/58658735/laravel-6-4-1-sqlstatehy000-2002-connection-refused)

### error No Application Encryption Key Has Been Specified

Setelah selesai mengatur permission menggunakan `chmod -R 777` muncul `error No Application Encryption Key Has Been Specified` di browser.

Solusinya jalankan command `php artisan key:generate` di terminal [ref](https://stackoverflow.com/questions/44839648/no-application-encryption-key-has-been-specified)

### Error ErrorSQLSTATE[HY000] [1698] Access denied for user

Error ini terjadi karena DB_USERNAME dan DB_PASSWORD yang kita masukkan di file .env di project kita. Berikut keteranggan errornya:

```
Error ErrorSQLSTATE[HY000] [1698] Access denied for user 'root'@'localhost' (SQL: insert into `orders` (`qty`, `name`, `phone`, `address`, `total_price`, `status`, `updated_at`, `created_at`) values (2, romi, 087785589009, lamongan, 2000, Unpaid, 2024-06-08 14:49:08, 2024-06-08 14:49:08))
```

Solusinya kita harus memasukkan user yang teruhubung ke mysql server ke konfirgurasi .env di aplikasi kita. Jika kita belum memiliki user yang terhubung ke mysql server kita bisa mendaftarkan sendiri dengan cara berikut :

### Mendaftarkan user baru di mysql server [ref](https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql)

-   ```
    sudo mysql
    ```

-   ```
     CREATE USER 'nama user baru'@'localhost' IDENTIFIED BY 'password user baru';
    ```
-   ```
     GRANT ALL PRIVILEGES ON mydatabase.* TO 'nama user baru'@'localhost';
    ```
-   ```
    GRANT CREATE, ALTER, DROP, INSERT, UPDATE, DELETE, SELECT, REFERENCES, RELOAD on *.* TO 'nama user'@'localhost' WITH GRANT OPTION;
    ```
-   ```
     FLUSH PRIVILEGES;
    ```
-   ```
     exit;
    ```
-   ```
    php artisan config:cache
    ```
-   ```
    php artisan config:clear
    ```
-   ```
    php artisan cache:clear
    ```
