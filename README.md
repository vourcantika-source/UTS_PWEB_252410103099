# UTS_PWEB_252410103099

# Maison Sucrée

Maison Sucrée adalah aplikasi web toko kue premium berbasis Laravel yang dibuat untuk memenuhi tugas mata kuliah Pemrograman Web. Aplikasi ini dirancang dengan tampilan modern, minimalis, dan elegan untuk menampilkan berbagai pilihan produk kue.

# Fitur Utama

- **Login** – Halaman untuk masuk ke aplikasi.
- **Dashboard** – Menampilkan halaman utama dan informasi produk best seller.
- **Pengelolaan Produk** – Menampilkan daftar produk kue beserta gambar, nama, deskripsi, dan harga.
- **Profile** – Menampilkan informasi profil pengguna.
- **Logout** – Fitur untuk keluar dari aplikasi.

## Teknologi yang Digunakan

- PHP
- Laravel
- Blade Template
- HTML5
- CSS3
- JavaScript

## Struktur Project

```text
maison-sucree/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
│   └── views/
├── routes/
├── storage/
├── tests/
├── artisan
├── composer.json
└── README.md
```

## Cara Menjalankan Project

1. Clone atau download repository project.
2. Buka folder project melalui VS Code.
3. Buka terminal dan jalankan perintah:

```bash
composer install
```

4. Salin file `.env.example` menjadi `.env`:

```bash
cp .env.example .env
```

5. Generate application key:

```bash
php artisan key:generate
```

6. Jalankan server Laravel:

```bash
php artisan serve
```

7. Buka browser dan akses:

```text
http://127.0.0.1:8000
```

## Design Concept

Maison Sucrée mengusung konsep desain minimalis dan elegan dengan perpaduan warna ivory, mocha, dan espresso. Tampilan website dirancang untuk memberikan pengalaman pengguna yang nyaman dengan layout yang rapi dan responsif.

---

**Maison Sucrée, A Little Taste of Elegance.**
