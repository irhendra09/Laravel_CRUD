# Laravel CRUD dan upload gambar
Sebuah Blog sederhana hasil dari implementasi dari Laravel Atuh dan CRUD disertai dengan fitur upload gambar.

## Instalasi

### Composer Packages 
```
composer install
```

## Configurasi

### Membuat '.env' file dari '.env.example'
```
cp .env.example .env
```

### Membuat Laravel App Key
```
php artisan key:generate
```

### Database Integrasi
1. Buka `.env` file
2. Buat sebuah database dan integrasikan dengan memasukkan nama data base pada bagian `DB_DATABASE`
3. Sesuaikan  `DB_USERNAME`
4. Sesuaikan `DB_PASSWORD`

### Migrate Database
```
php artisan migrate
```

## Menjalankan App
Instal NPM packages
```
npm install
```

Menjalankan local web server
```
php artisan serve
```

Buka console baru dan jalankan app dengan Vite
```
npm run dev
```

# URL
http://127.0.0.1:8000/login
![Screenshot 2024-02-08 093948](https://github.com/irhendra09/Laravel_CRUD/assets/118523391/a709519d-6603-4186-aae3-9f7156a6b129)

http://127.0.0.1:8000/register
![Screenshot 2024-02-08 094645](https://github.com/irhendra09/Laravel_CRUD/assets/118523391/7e2dbdab-ff10-484b-a323-32622bb8baa1)

http://127.0.0.1:8000/posts
![Screenshot 2024-02-08 094501](https://github.com/irhendra09/Laravel_CRUD/assets/118523391/88876a3d-dbdd-4a08-ab0a-007516e01735)
![Screenshot 2024-02-08 094433](https://github.com/irhendra09/Laravel_CRUD/assets/118523391/92247a63-c890-45ac-9ba1-5a0baaf3fd6f)

http://127.0.0.1:8000/posts/:id
![Screenshot 2024-02-08 094533](https://github.com/irhendra09/Laravel_CRUD/assets/118523391/85fda2cf-2542-4e64-9e07-71ae4e94434b)

http://127.0.0.1:8000/posts/:id/edit
![Screenshot 2024-02-08 094606](https://github.com/irhendra09/Laravel_CRUD/assets/118523391/d51e1344-74f6-414e-827d-485d70d1c325)
