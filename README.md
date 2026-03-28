# Laporan Proyek Web: dxktbd tutor

Proyek ini adalah implementasi *Landing Page* untuk platform kursus online bernama **dxktbd tutor**. Proyek ini dikembangkan menggunakan teknologi web dasar (HTML5 & CSS3) dengan fokus pada aspek *responsiveness*, *user experience*, dan estetika desain modern.
Visit site: https://fathurdxs.github.io/tugas_htmlcss/
---

## Informasi Mahasiswa
* **Nama:** [Nama Lengkap Kamu]
* **NIM:** [Nomor Induk Mahasiswa Kamu]
* **Mata Kuliah:** [Nama Mata Kuliah, misal: Pemrograman Web]
* **Dosen/Asisten:** [Nama Dosen/Asprak]

---

## Fitur dan Implementasi Teknis

### 1. Arsitektur Kode
* **HTML5 Semantic:** Menggunakan tag semantik seperti `<nav>`, `<header>`, `<section>`, dan `<footer>` untuk mempermudah pembacaan struktur oleh *search engine* (SEO) dan *screen reader*.
* **CSS3 Custom Variables:** Menggunakan `:root` variables untuk manajemen warna (Primary, Secondary, Dark, Light) agar konsistensi desain terjaga dan mudah di-maintenance.

### 2. Layout & Responsivitas
* **CSS Grid & Flexbox:** Implementasi *Grid* pada bagian Kursus dan Testimoni untuk tata letak yang presisi.
* **Media Queries:** Menggunakan `@media` screen untuk memastikan tampilan tetap optimal di perangkat *mobile* (lebar layar < 768px).
* **Sticky Navigation:** Navbar dikunci di posisi atas menggunakan `position: sticky` untuk memudahkan akses navigasi pengguna.

### 3. Interaktivitas
* **Smooth Scrolling:** Mengimplementasikan `scroll-behavior: smooth` pada level elemen `html` untuk transisi antar-section yang halus saat navigasi diklik.
* **Hover Effects:** Penambahan efek *transform* (translateY) dan *box-shadow* pada komponen kartu untuk memberikan umpan balik visual kepada pengguna.

---

## Struktur File
```text
.
├── index.html     # Struktur utama konten web
├── style.css      # Logika styling dan desain responsif
└── README.md      # Dokumentasi proyek (file ini)
