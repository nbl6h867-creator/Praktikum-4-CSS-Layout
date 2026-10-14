# Praktikum-4-CSS-Layout

## Tujuan
1. Memahami struktur dasar pembuatan layout.
2. Memahami konsep box element.
3. Memahami CSS floating.
4. Memahami HTML5 semantic element.
5. Mampu membuat layout web sederhana.

## Langkah-Langkah Praktikum

### 1. Membuat Dokumen Dasar
Buat file `lab4_box.html` dengan struktur HTML5 dasar (head, title "Box Element", dan header berisi `<h1>Box Element</h1>`)

### 2. Membuat Box Element
Tambahkan tiga `<div>` di dalam `<section>` dengan class `div1`, `div2`, `div3` untuk merepresentasikan box element.

### 3. Menerapkan CSS Float Property
Tambahkan CSS dengan `float: left` dan `padding: 10px` pada elemen `div`, serta warna background berbeda untuk tiap class (merah, kuning, hijau) agar box tampil sejajar secara horizontal.

### 4. Mengatur Clearfix Element
Tambahkan `div4` setelah `div3`, lalu beri properti `clear: left` dan `float: none` pada `div4` agar elemen berikutnya tidak ikut "mengambang" mengikuti float sebelumnya.
**Eksperimen:** coba ubah nilai `clear` menjadi `left`, `both`, dan `right`, lalu amati perbedaannya.

### 5. Membuat Layout Sederhana
Buat folder baru `lab4_layout`, lalu buat dua file: `home.html` dan `style.css`.

#### a. Kerangka HTML Dasar
Buat `home.html` dengan `<div id="container">` sebagai pembungkus utama, dan hubungkan ke `style.css` lewat `<link>`.

#### b. Kerangka Layout dengan Semantic Element
Susun struktur dengan elemen semantik:

<header>...</header>
<nav>...</nav>
<section id="hero"></section>
<section id="wrapper">
  <section id="main"></section>
  <aside id="sidebar"></aside>
</section>
<footer>...</footer>

#### c. Styling Dasar (Reset CSS & Container)
Tambahkan CSS reset (`margin: 0; padding: 0;`), font Google Fonts (Open Sans), dan styling `#container` (lebar 980px, center, box-shadow).

#### d. Membuat Navigasi
Styling elemen `<nav>` dan `<nav a>` dengan background biru, padding, dan efek hover/active.

#### e. Membuat Hero Panel
Isi `<section id="hero">` dengan judul "Hello World!", paragraf deskripsi, dan tombol "Learn more". Styling dengan background abu-abu dan padding.

#### f. Mengatur Layout Main dan Sidebar
Terapkan `float: left` pada `#main` (lebar 640px) dan `#sidebar` (lebar 260px) agar tampil berdampingan.

#### g. Membuat Sidebar Widget
Tambahkan dua widget di `<aside id="sidebar">`: "Widget Header" (daftar link) dan "Widget Text" (paragraf), lengkap dengan styling `.widget-box`.

#### h. Mengatur Footer
Styling `<footer>` dengan `clear: both`, background gelap, dan warna teks terang agar berada di bawah seluruh elemen float.

#### i. Menambahkan Elemen Grid pada Main Content
Tambahkan tiga `.box` (gambar lingkaran, heading, deskripsi, tombol "View detail") dalam `.row` menggunakan `float: left` dengan lebar 33.33% masing-masing.

#### j. Menambahkan Content Artikel
Tambahkan dua `<article class="entry">` dengan gambar dan teks, salah satunya menggunakan class `.right-img` agar gambar rata kanan. Pisahkan tiap artikel dengan `<hr class="divider">`.

## Pertanyaan dan Tugas
1. Tambahkan layout untuk menu **About** buat single layout berisi deskripsi, portfolio, dll.
2. Tambahkan layout untuk menu **Contact** buat form isian (nama, email, message, dll).
