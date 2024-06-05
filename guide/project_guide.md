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
    [ref](https://www.youtube.com/watch?v=069oMpRX9zA&list=PLBs-bxLCgCx8RnTNzu2QYvzQMuskmID1A&index=4&t=3m10s)
