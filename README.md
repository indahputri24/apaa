# Install Laravel

install composer dulu
```
[https://getcomposer.org/doc/00-intro.md](https://www.malasngoding.com/cara-install-composer/)
```

install laravel

```
https://www.malasngoding.com/pengertian-dan-cara-install-laravel/
```

buka folder xampp > htdocs > masjidshiratalmustaqiem (tarok folder project laravel disini) coba langsung copy aja zip ku ke dalam folder htdocs

kalau udah buat folder projectnya, buka di vs code folder projectnya, trs buka phpmyadmin untuk buat database

folder yg di ubah

<img width="388" height="315" alt="image" src="https://github.com/user-attachments/assets/5d7e4c4a-699b-40ae-9c44-e3653f6e97c8" />

<img width="407" height="391" alt="image" src="https://github.com/user-attachments/assets/ab2fe4aa-5f72-4a39-85df-50883d602982" />

<img width="445" height="110" alt="image" src="https://github.com/user-attachments/assets/92ab3818-9799-4261-a1b0-a416f41a3934" />

<img width="428" height="218" alt="image" src="https://github.com/user-attachments/assets/bde6748f-e21f-493f-a74a-5297d8989091" />

trs sama dua file .env dan .env.example hrs sama isinya

```
Buatkan saya project website menggunakan Laravel dengan konsep MVC (Model View Controller) sesuai ketentuan berikut:
=== KETENTUAN ===
1. Wajib menggunakan Laravel (struktur MVC jelas: Route, Controller, Model, View)
2. Website memiliki fitur:
   - Halaman Landing Page (responsive & modern)
   - Halaman Login
   - Halaman Register (menggunakan berbagai input: text, radio button, select box)
3. Menggunakan CSS atau Bootstrap (boleh kombinasi)
4. Design mengikuti style elegan, minimalis, warna earthy (cream, coklat, gold)
=== STRUKTUR YANG DIINGINKAN ===
1. Route:
   - / → landing page
   - /login → halaman login
   - /register → halaman register
2. Controller:
   - HomeController → landing page
   - AuthController → login & register
3. Model:
   - User / Staf (untuk data user)
4. View (Blade):
   - resources/views/home.blade.php
   - resources/views/login.blade.php
   - resources/views/register.blade.php
   - resources/views/layouts/app.blade.php
=== DESIGN REQUIREMENT ===
Gunakan inspirasi design berikut:
- Hero section dengan background image + overlay
- Typography serif (elegan)
- Warna:
  - Cream (#ede3d0)
  - Coklat tua (#1e1a14)
  - Gold (#a8956e)
- Layout:
  - Navbar atas
  - Hero text besar
  - Section konten
  - Form login/register clean dan modern
Design website menggunakan tema elegan dengan warna coklat, cream, dan gold.
Menggunakan typography serif untuk judul dan layout minimalis dengan banyak whitespace.
Terdapat hero section, navbar, dan section konten seperti pada desain modern museum.
=== FITUR FORM REGISTER ===
Harus ada:
- Nama (text)
- Email (email)
- Password (password)
- Jenis Kelamin (radio button)
- Agama (select box)
- Checkbox persetujuan
=== OUTPUT YANG DIHARAPKAN ===
1. Kode route (web.php)
2. Controller lengkap
3. Model
4. View Blade (HTML + CSS/Bootstrap)
5. Struktur folder
6. Semua hasil dalam format zip
Gunakan kode yang clean, mudah dipahami, dan cocok untuk mahasiswa.
Tambahkan:
- Validasi form Laravel
- Flash message (berhasil / error)
- Responsive design (mobile friendly)
- Animasi sederhana (hover / fade in)
```

KARENA ITU BLUM DI PISAH JADI AKU MINTA PROMPT BUAT PISAHIN

```
Lanjutkan dari project Laravel yang sudah kamu buat sebelumnya.
Sekarang tugas kamu adalah MERAPIKAN dan MEMISAHKAN kode menjadi struktur yang lebih profesional tanpa mengubah desain atau isi kode.
=== ATURAN WAJIB ===
- JANGAN mengubah tampilan (design harus tetap sama persis)
- JANGAN mengubah struktur HTML, class, atau id
- JANGAN menghapus kode apapun
- Hanya memindahkan kode ke file yang sesuai (refactor struktur saja)
=== PEMISAHAN FILE ===
1. CSS:
- Ambil semua kode yang berada di dalam tag <style> ... </style>
- Hapus tag <style>, ambil isinya saja
- Pindahkan ke file: public/css/style.css
2. JavaScript:
- Ambil semua kode di dalam tag <script> ... </script>
- Hapus tag <script>, ambil isinya saja
- Pindahkan ke file: public/js/script.js
3. Blade (View Laravel):
- File:
  - home.blade.php
  - login.blade.php
  - register.blade.php
- Hapus bagian <style> dan <script>
- Bungkus setiap file dengan:
  @extends('layouts.app')
  @section('content')
  ...
  @endsection
4. Layout:
File: resources/views/layouts/app.blade.php
Tambahkan:
DI <head>:
<link rel="stylesheet" href="{{ asset('css/style.css') }}">
SEBELUM </body>:
<script src="{{ asset('js/script.js') }}"></script>
=== STRUKTUR AKHIR ===
public/
 ├── css/style.css
 ├── js/script.js
resources/views/
 ├── layouts/app.blade.php
 ├── home.blade.php
 ├── login.blade.php
 ├── register.blade.php
=== OUTPUT YANG DIHARAPKAN ===
Tampilkan hasil dalam urutan berikut:
1. File style.css
2. File script.js
3. File layouts/app.blade.php 
4. File home.blade.php
5. File login.blade.php
6. File register.blade.php

dalam format zip
Pastikan:
- Tidak ada perubahan tampilan
- Semua class tetap sama
- Semua fitur tetap berjalan
- Code tetap clean dan rapi
```
