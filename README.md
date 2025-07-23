Styluxe
Styluxe adalah sebuah platform e-commerce sederhana berbasis PHP dan MySQL yang memungkinkan pengguna untuk melakukan pembelian produk fashion secara online. Proyek ini mencakup fitur lengkap mulai dari pendaftaran akun pengguna, keranjang belanja, checkout, hingga panel admin untuk pengelolaan data produk dan transaksi.

styluxe/
├── admin/                 # Panel admin
│   ├── beranda.php
│   ├── hapuskategori.php
│   ├── hapuspembayaran.php
│   └── ...
├── akun.php               # Halaman akun pengguna
├── checkout.php          # Proses checkout
├── daftar.php            # Registrasi akun
├── detail.php            # Detail produk
├── header.php/footer.php # Layout
├── index.php             # Halaman utama
├── kategori.php          # Produk per kategori
├── keranjang.php         # Halaman keranjang
├── koneksi.php           # Koneksi database
├── login.php/logout.php  # Autentikasi
├── pembayaran.php        # Konfirmasi pembayaran
├── produk.php            # Daftar produk
├── riwayat.php           # Riwayat belanja pengguna
├── style.css             # Gaya tampilan

Fitur Utama
Untuk Pengunjung / Pembeli:
Pendaftaran dan login akun

Melihat produk dan detailnya

Menambahkan produk ke keranjang

Checkout dan konfirmasi pembayaran

Melihat riwayat transaksi

Untuk Admin:
Login admin (melalui /admin)

Melihat, menghapus data kategori

Mengelola pembayaran

Panel beranda admin

⚙️ Teknologi yang Digunakan
Bahasa Pemrograman: PHP (native)

Database: MySQL

Frontend: HTML, CSS

Server: Apache / XAMPP

Cara Menjalankan Proyek
Clone repositori ini:

bash
Salin
Edit
git clone https://github.com/username/styluxe.git
Pindahkan folder ke direktori web server:

Jika menggunakan XAMPP: letakkan di htdocs/styluxe

Import database:

Buka phpMyAdmin

Buat database bernama styluxe (atau sesuai dengan di koneksi.php)

Import file SQL (jika tersedia, bisa ditambahkan nanti di repositori)

Jalankan aplikasi:

Buka browser dan akses: http://localhost/styluxe/

🧩 Catatan
Pastikan konfigurasi database di koneksi.php sesuai dengan server lokal Anda:

php
Salin
Edit
$koneksi = new mysqli("localhost", "root", "", "styluxe");
Belum termasuk sistem keamanan yang lengkap (sebaiknya jangan langsung digunakan untuk produksi).
