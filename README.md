# CodeIgniter4 Ajax CRUD

Program sederhana Ajax Crud dengan CodeIgniter4.

# Installation

### Clone the repository:

```
git clone https://github.com/yeremiaraulandreas/iuran_kas.git
```

### Pindah ke directory iuran_kas:

```
cd iuran_kas
```

### Install dependency composer dengan git bash atau terminal:

```
composer install
```

### Buat database baru. Kemudian rename .env.example ke .env selanjutnya sesuaikan dengan konfigurasi database:

```
database.default.hostname = localhost
database.default.database = crud-ci4
database.default.username = root
database.default.password =
database.default.DBDriver = MySQLi
```

### Migrasi database:

```
php spark migrate
```

### Buat data dummy dengan perintah:

```
php spark db:seed BookSeeder
```

### Jalankan aplikasi dengan perintah:

```
php spark serve
```

Sekarang buka browser dengan alamat address http://localhost:8080/

# Screenshoot | Demo on [Heroku](https://crud-codeigniter4.herokuapp.com)



[Dashboard]![image](https://user-images.githubusercontent.com/81977332/126323975-6c9ea99b-b061-408d-bbfc-e3eec3874d09.png)
[Warga]![image](https://user-images.githubusercontent.com/81977332/126324070-381ecd38-36fe-4bc8-b25d-692ad6798d3f.png)
[Update]![image](https://user-images.githubusercontent.com/81977332/126324153-2592c5fc-047d-4659-a233-0f4d23fb6aa7.png)
[Delete]![image](https://user-images.githubusercontent.com/81977332/126324275-88ecbef6-d2b3-43f3-9298-2872a2f88ff6.png) 
[Iuran]![image](https://user-images.githubusercontent.com/51916189/126337644-08be92d8-5b55-4626-8d91-f9568ff9bf3a.png)
[Laporan]![image](https://user-images.githubusercontent.com/51916189/126337722-38200672-0f6d-46ad-b698-2c0c6fe70354.png)


