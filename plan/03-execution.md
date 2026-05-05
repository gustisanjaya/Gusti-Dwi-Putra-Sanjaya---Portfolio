# Step-by-step Execution

## Step 1: Persiapan (Planning)

- [x] Baca tugas Portfolio Homework - KAreerr Elevation Vol. 2
- [x] Pahami RTCC-O framework
- [x] Identifikasi struktur file yang diminta
- [x] Buka file app.blade.php dan home.blade.php asli

## Step 2: Ekstrak CSS

- [x] Ambil semua style dari kedua file Blade
- [x] Gabungkan ke dalam satu file style.css
- [x] Pastikan tidak ada style yang bentrok
- [x] Tambahkan media query untuk responsive (mobile-first)
- [x] Tambahkan print styles untuk PDF

## Step 3: Buat Struktur HTML dengan Semantic Tags

- [x] Buat skeleton HTML dasar (DOCTYPE, head, body)
- [x] Copy navbar dari app.blade.php ke dalam <nav>
- [x] Ganti <div class="container"> dengan <main class="container">
- [x] Ganti <div class="profile-header"> dengan <header class="profile-header">
- [x] Pastikan setiap section menggunakan <section>
- [x] Copy footer ke dalam <footer>
- [x] Copy palette container dan script

## Step 4: Konversi Blade ke HTML Murni

- [x] Ganti @yield('title') dengan title langsung
- [x] Ganti @yield('content') dengan konten home.blade.php
- [x] Hapus @extends, @section, @endsection, @push
- [x] Ganti asset() dengan path langsung atau data URI
- [x] Ganti {{ date('Y') }} dengan tahun statis (2026)

## Step 5: Integrasi CSS

- [x] Simpan style.css di root folder
- [x] Tambahkan <link rel="stylesheet" href="style.css">
- [x] Hapus semua tag <style> dari HTML

## Step 6: Testing Fungsi

- [x] Navbar muncul dengan benar
- [x] Links navigasi berfungsi (smooth scroll)
- [x] Active navbar highlight saat scroll
- [x] Palette warna bisa di-click dan mengubah background
- [x] Tombol PDF berfungsi (window.print)
- [x] Responsif di berbagai ukuran layar (test dengan DevTools)

## Step 7: Dokumentasi

- [x] Buat README.md (project overview)
- [x] Buat plan/01-brainstorm.md
- [x] Buat plan/02-details.md (dengan RTCC-O)
- [x] Buat plan/03-execution.md
- [x] Buat plan/04-results.md

## Step 8: Screenshots (akan dikerjakan sendiri)

- [ ] Ambil screenshot desktop, simpan di assets/desktop-view.png
- [ ] Ambil screenshot mobile, simpan di assets/mobile-view.png
- [ ] Pastikan screenshot menunjukkan tampilan portfolio

## Step 9: Finalisasi

- [x] Cek semua path file (CSS)
- [x] Validasi tidak ada error di console browser
- [x] Pastikan desain 100% sama dengan asli
- [x] Pastikan semantic HTML lengkap

## Catatan

Step 8 (screenshots) dan deployment ke GitHub Pages akan dikerjakan
setelah semua file siap.