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

http://127.0.0.1:8000/register

http://127.0.0.1:8000/posts

http://127.0.0.1:8000/posts/:id

http://127.0.0.1:8000/posts/:id/edit
