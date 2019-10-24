# Laravel Nginx MariaBD
Hal yang perlu diperhatikan: pastikan kamu mengecek isi dari docker-compose ini dan tidak bentrok dengan docker container dan volume yang ada di komputer kamu.

## error port
jika terjadi pada port yang error ganti dengan port yang sesuai

## composer install
jalankan omposer install untuk mengintall tool pendukung

## generate key
buat key dengna menggunakan perintah ```php artisan key:generate```

## clear cache
```docker-compose exec app php artisan config:cache```

## database
untuk menguji apakah database sudah berjalan dengan baik yaitu dengan menggunakan perintah : ```mysql -u root -p -P 3309 -h 127.0.0.1``` 

## referensi 
- https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose