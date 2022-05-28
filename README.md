## Getting Started

Sebelum memulai untuk menjalankan projek ini ada beberapa hal yang harus disiapkan.
1. Jalankan front-end
2. Jalankan back-end

`Jalankan front-end dan back-end secara BERGILIRAN tanpa mematikan server (buka dua tab / terminal)`

## Front-End

Buka folder project `challenge-07`, lalu install semua dependencies, dengan menjalankan
```
yarn install
```

Kemudian, jalankan program
```
yarn start
```

## Back-End
Buka folder project `challenge-07`, lalu `cd/backend` untuk berpindah ke folder `backend`. Selanjutnya install semua dependencies, dengan menjalankan
```
yarn install
```
Menjalankan project backend, jalankan dengan perintah
```
yarn develop
```

## Cloud Database
Database yang digunakan dalam database ini menggunakan database cloud, gunakan aplikasi `TablePlus` kemudian create new connection menggunakan URL berikut
```
postgres://zwetnoba:jqtb4_d73kwN5MgQslKj1N5l5sQOxA9u@tiny.db.elephantsql.com/zwetnoba
```

## Database Management

Di dalam repository ini sudah terdapat beberapa script yang dapat digunakan dalam memanage database, yaitu:

- `yarn db:create` digunakan untuk membuat database
- `yarn db:drop` digunakan untuk menghapus database
- `yarn db:migrate` digunakan untuk menjalankan database migration
- `yarn db:seed` digunakan untuk melakukan seeding