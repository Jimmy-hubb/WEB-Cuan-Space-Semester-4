# 🛒 Cuan Space – Platform UMKM Online

**Cuan Space** merupakan aplikasi berbasis **web** yang dikembangkan untuk membantu **pelaku UMKM** dalam menjual produk mereka secara online dengan lebih mudah dan terorganisir.

Aplikasi ini memungkinkan pelaku usaha untuk **menampilkan produk, menerima pesanan, serta mengelola transaksi secara digital**. Dengan adanya platform ini, diharapkan UMKM dapat memperluas jangkauan pasar dan meningkatkan penjualan melalui sistem berbasis web.

Project ini dikembangkan menggunakan **Laravel Framework** sebagai backend serta **Blade Template, CSS, dan PHP** untuk membangun tampilan antarmuka aplikasi.

Project ini juga dibuat sebagai bagian dari **portfolio pengembangan web developer** serta pembelajaran dalam membangun aplikasi berbasis **Laravel Framework**.

---

# 🚀 Features

Beberapa fitur utama dalam aplikasi **Cuan Space** antara lain:

### 🛍️ Katalog Produk
Menampilkan berbagai produk yang dijual oleh pelaku UMKM lengkap dengan deskripsi dan harga produk.

### 📦 Detail Produk
Pengguna dapat melihat detail informasi produk seperti:

- Nama produk
- Harga produk
- Deskripsi produk
- Gambar produk
- Informasi penjual

### 🛒 Sistem Pemesanan
Pengguna dapat melakukan pemesanan produk secara langsung melalui website.

### 📑 Riwayat Transaksi
Pengguna dapat melihat **history pembelian atau pesanan** yang telah dilakukan.

### 🔐 Sistem Login & Register
Pengguna dapat membuat akun untuk melakukan transaksi dan mengelola pesanan.

### ⚙️ Dashboard Admin
Admin dapat mengelola berbagai data seperti:

- Mengelola produk
- Mengelola pesanan
- Mengelola pengguna
- Melihat riwayat transaksi

### 📱 Responsive Web Design
Website dapat diakses dengan baik melalui berbagai perangkat seperti **desktop maupun mobile**.

---

# 🛠 Tech Stack

Teknologi yang digunakan dalam pengembangan aplikasi ini:

| Technology | Description |
|-----------|-------------|
| Laravel | Framework PHP untuk backend |
| PHP | Bahasa pemrograman utama |
| Blade | Template engine Laravel |
| MySQL | Database management system |
| HTML5 | Struktur halaman website |
| CSS3 | Styling halaman |
| JavaScript | Interaktivitas pada website |
| Vite | Build tool frontend Laravel |

---

# 📂 Project Structure

Struktur folder utama pada project Laravel:

```
cuan-space
│
├── app
│   ├── Http
│   ├── Models
│   └── Providers
│
├── bootstrap
├── config
├── database
│   ├── migrations
│   └── seeders
│
├── public
├── resources
│   ├── views
│   ├── css
│   └── js
│
├── routes
│   └── web.php
│
├── storage
├── tests
├── composer.json
├── package.json
├── vite.config.js
└── README.md
```

---

# ⚙️ Installation

Ikuti langkah berikut untuk menjalankan project secara lokal.

### 1. Clone Repository

```bash
git clone https://github.com/username/cuan-space.git
```

### 2. Masuk ke Folder Project

```bash
cd cuan-space
```

### 3. Install Dependency Laravel

```bash
composer install
```

### 4. Install Dependency Frontend

```bash
npm install
```

### 5. Copy File Environment

```bash
cp .env.example .env
```

### 6. Konfigurasi Database

Buka file `.env` lalu ubah konfigurasi database.

Contoh:

```
DB_DATABASE=cuan_space
DB_USERNAME=root
DB_PASSWORD=
```

---

### 7. Generate Application Key

```bash
php artisan key:generate
```

---

### 8. Migrasi Database

```bash
php artisan migrate
```

---

### 9. Jalankan Server

```bash
php artisan serve
```

---

### 10. Jalankan Frontend Vite

```bash
npm run dev
```

---

### 11. Akses Website

Buka browser dan akses:

```
http://localhost:8000
```

---

# 📸 Application Preview

Tambahkan screenshot aplikasi pada folder `images`.

```
![Home Page](images/home.png)
![Product Page](images/products.png)
![Admin Dashboard](images/admin.png)
```

---

# 🎯 Project Goals

Tujuan utama dari pengembangan aplikasi ini:

- Membantu UMKM dalam menjual produk secara online
- Mempermudah pengelolaan produk dan pesanan
- Mendukung digitalisasi usaha kecil dan menengah
- Mengembangkan keterampilan dalam pengembangan aplikasi menggunakan Laravel
