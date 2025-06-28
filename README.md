# PersonalWeb
Personal portofolio menggunakan tailwind css
🌐 Personal Web | Divi Agung Satria
Berbagi cerita, ide, dan inspirasi melalui tulisan dan galeri pribadi.
Dibuat sebagai proyek pembelajaran menggunakan PHP, Tailwind CSS, dan MySQL.

📌 Deskripsi Proyek
Website ini adalah personal web milik Divi Agung Satria yang menampilkan artikel pribadi, galeri foto, dan fitur admin untuk mengelola konten. Web ini bertujuan menjadi ruang ekspresi dan latihan praktis membuat web dinamis dan interaktif.

✨ Fitur-Fitur Aplikasi
📝 Halaman Publik
Beranda / Artikel Terbaru
Menampilkan artikel-artikel yang telah dipublikasikan.

Galeri Foto
Menampilkan gambar-gambar pilihan dari folder images/.

About (Tentang Saya)
Informasi dan profil pemilik web.

Login Admin
Form login untuk mengakses dashboard admin.

🛠 Halaman Admin
Dashboard Admin
Ringkasan jumlah artikel, galeri, dan akses cepat.

Kelola Artikel
Tambah, edit, dan hapus artikel.

Kelola Galeri
Upload gambar baru, edit, dan hapus gambar lama.

Kelola About
Edit isi halaman tentang saya.

Logout
Keluar dari sistem admin dengan aman.

📷 Screenshot Tampilan
Catatan: Letakkan semua screenshot di dalam folder screenshots/.

1. Beranda
ss/Cuplikan layar 2025-06-28 204506.png

2. Galeri Foto


3. Tentang Saya


4. Form Login Admin


5. Dashboard Admin


6. Tambah Artikel Baru


7. Kelola Halaman About


8. Kelola Galeri


🧰 Teknologi yang Digunakan
Frontend: HTML5, Tailwind CSS v4.0

Backend: PHP Native

Database: MySQL

Web Server: XAMPP (Localhost)

🚀 Cara Menjalankan Aplikasi
Clone atau download repositori ini ke folder htdocs di XAMPP.

Jalankan XAMPP, aktifkan Apache dan MySQL.

Buka phpMyAdmin, lalu import database dari file db_divi_agung_satria.sql.

Akses web di browser:
http://localhost/personal_web_divi/

Login admin melalui:
http://localhost/personal_web_divi/admin/login.php

📁 Struktur Folder
pgsql
Salin
Edit
├── admin/
│   ├── add_about.php
│   ├── add_artikel.php
│   ├── add_gallery.php
│   ├── data_artikel.php
│   ├── data_gallery.php
│   ├── edit_about.php
│   ├── edit_artikel.php
│   ├── edit_gallery.php
│   ├── delete_artikel.php
│   ├── delete_gallery.php
│   ├── proses_add_about.php
│   ├── proses_add_artikel.php
│   ├── proses_add_gallery.php
│   └── login.php, logout.php, dll.
│
├── images/
│   └── (gambar galeri)
│
├── mp3/
│   └── (file audio mp3)
│
├── ss/
│   └── about.php (backup atau versi lain)
│
├── index.php
├── about.php
├── gallery.php
├── koneksi.php
