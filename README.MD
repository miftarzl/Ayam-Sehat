# Sistem Pakar Diagnosa Penyakit Ayam

<div align="center" id="top">
  <img src="gambar/demo/landing-page.png" width="900" alt="Landing Page" />
</div>

## 📖 Tentang

Penyakit ayam merupakan salah satu permasalahan yang sering dihadapi oleh peternak ayam. Untuk mendiagnosis penyakit ayam, peternak perlu mengenali gejala-gejala yang muncul pada ayam dan berkonsultasi dengan ahlinya. Namun, hal tersebut membutuhkan waktu dan biaya yang cukup besar.

Proyek ini bertujuan untuk mengembangkan **sistem pakar berbasis web** yang dapat membantu peternak mendiagnosis penyakit ayam secara cepat dan mudah. Sistem ini menggunakan metode **Forward Chaining** untuk menentukan penyakit ayam berdasarkan gejala yang diinput oleh pengguna. Sistem ini dikembangkan dengan bahasa pemrograman **PHP** dan basis data **MySQL**, serta didukung oleh tampilan antarmuka **Bootstrap**.

Sistem ini menyediakan panduan penanganan yang tepat terhadap penyakit yang didiagnosis, dan diuji menggunakan **33 gejala** dan **10 jenis penyakit** ayam yang umum terjadi. Hasil pengujian menunjukkan bahwa sistem dapat mendiagnosis penyakit ayam dengan akurasi tinggi dan memberikan hasil diagnosis secara langsung melalui browser.

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Demo App

<div align="center" id="top">
  <figure>
    <img src="gambar/demo/dashboard-admin.png" width="900" alt="Halaman Dashboard" />
    <figcaption>---Halaman Dashboard---</figcaption>
  </figure>
  
  <figure>
  <img src="gambar/demo/gejala-admin.png" width="900" alt="Halaman Gejala" />
    <figcaption>---Halaman Gejala---</figcaption>
  </figure>
  
  <figure>
  <img src="gambar/demo/penyakit-admin.png" width="900" alt="Halaman Penyakit" />
    <figcaption>---Halaman Penyakit---</figcaption>
  </figure>
  
  <figure>
  <img src="gambar/demo/solusi-admin.png" width="900" alt="Halaman Solusi" />
    <figcaption>---Halaman Solusi---</figcaption>
  </figure>

  <figure>
  <img src="gambar/demo/result.png" width="900" alt="Halaman Result" />
    <figcaption>---Halaman Result---</figcaption>
  </figure>
</div>

---

## 🛠️ Teknologi yang Digunakan

- **PHP** - Web development
- **Bootstrap** - Responsive design
- **MySQL** - Database management

## Konfigurasi

#### Dummy User

- Username = ara
- Password = 12345678

#### Admin

- Username = admin
- Password = 12345678

## 🚀 Features
- [x] **Diagnosa**

  - [x] Tambah Gejala
  - [x] Tambah Penyakit
  - [x] Tambah Solusi
  - [x] Edit Gejala
  - [x] Edit Penyakit
  - [x] Edit Solusi
  
- [x] **Authentication**

  - [x] Register
  - [x] Login
  - [x] Logout
  - [x] Reset Password

- [ ] **User Management**

  - [x] View Profile
  - [ ] Edit Profile
  - [ ] Delete Account

- [ ] **Dashboard**

  - [x] User Dashboard
  - [x] Admin Dashboard
  - [ ] Statistics Overview

- [x] **Responsive Design**
  - [ ] Mobile-Friendly Layout
  - [ ] Tablet-Friendly Layout
  - [x] Desktop Layout

## 🔗 Link Pendukung

- **Documentasi API** - Tautan ke documentasi API
- **Database Diagram** - Tautan ke diagram database

## 👤 Kontribusi

Kontribusi untuk pengembangan lebih lanjut sangat terbuka! Berikut cara Anda dapat berkontribusi:

- Fork repositori ini.
- Buat branch fitur baru (`git checkout -b fitur-anda`).
- Commit perubahan Anda (`git commit -m 'Menambahkan fitur ABC'`).
- Push ke branch (`git push origin fitur-anda`).
- Ajukan Pull Request.

## ❤️ Dukungan dan Donasi

Jika Anda merasa sistem ini bermanfaat dan ingin mendukung pengembangan lebih lanjut, Anda dapat memberikan donasi melalui platform berikut:

- ![Saweria](https://img.shields.io/badge/-Saweria-orange?style=flat-square&logo=sawe&logoColor=white) [Klik di sini](https://saweria.co/AhmadJanuar)
- ![PayPal](https://img.shields.io/badge/-PayPal-blue?style=flat-square&logo=paypal&logoColor=white) [Klik di sini](https://paypal.me/ahmadjanuar)
- ![Dana](https://img.shields.io/badge/-Dana-blue?style=flat-square&logo=dana&logoColor=white)  
  **Nomor HP**: 089630507889 
  **Atas Nama**: Desvita Damayanti

<p>Email: desvitadamayanti@gmail.com</p>

Setiap dukungan yang Anda berikan akan sangat membantu untuk pengembangan proyek ini lebih lanjut. Terima kasih atas dukungannya! 😊

---

## ⚙️ Cara Setup & Penggunaan

### 1. Persiapan Lingkungan
- Pastikan sudah menginstall XAMPP/Laragon atau web server lain yang mendukung PHP dan MySQL.
- Clone atau download source code ke folder web server, misal: `C:/laragon/www/ayam-sehat-master`.

### 2. Setup Database
- Buka phpMyAdmin.
- Buat database baru dengan nama: `spk_ayam`.
- Import file `spk_ayam.sql` yang ada di folder project ke database tersebut.

### 3. Konfigurasi Koneksi Database
- Pastikan file `function.php` sudah menggunakan username dan password database Anda.
  - Default: username `newuser`, password `mifta1234` (atau sesuaikan dengan user MySQL Anda).

### 4. Menjalankan Aplikasi
- Jalankan web server (Apache/Nginx) dan MySQL.
- Akses aplikasi melalui browser: `http://localhost/ayam-sehat-master/index.php`

### 5. Login & Penggunaan
- **Admin**
  - Username: `admin`
  - Password: `12345678`
- **User**
  - Username: `ara`
  - Password: `12345678`
- Anda juga dapat melakukan registrasi user baru melalui halaman register.

### 6. Fitur Utama
- Diagnosa penyakit ayam berdasarkan gejala.
- Manajemen data gejala, penyakit, solusi (tambah, edit, hapus) untuk admin.
- Registrasi dan login user/pakar.

### 7. Catatan
- Jika ada error koneksi database, cek kembali konfigurasi di `function.php` dan pastikan user MySQL sudah benar.
- Untuk menambah admin baru, tambahkan data langsung ke tabel `user` dengan `role` = 0.

---

<p align="right">(<a href="#readme-top">back to top</a>)</p>
