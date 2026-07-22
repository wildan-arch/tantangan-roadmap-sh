# Basic HTML Website (Multiple Pages)

Proyek ini adalah implementasi website multi-halaman (_multiple pages_) sederhana yang dibangun menggunakan **Semantic HTML**. Proyek ini dibuat untuk memenuhi tantangan proyek dari [roadmap.sh](https://roadmap.sh/) guna memahami struktur layout web yang baik, keterhubungan antar halaman, serta pembuatan form tanpa bantuan CSS.

## 🚀 Fitur & Struktur Halaman

Website ini terdiri dari 4 halaman utama yang saling terhubung melalui menu navigasi seragam di setiap halaman:

1.  **Home (`index.html`):** Halaman utama profil berisi ringkasan profesi, keahlian, pengalaman kerja di roadmap.sh, riwayat pendidikan, serta ulasan (_reviews_).
2.  **Projects (`projects.html`):** Halaman yang didedikasikan untuk menampilkan daftar portofolio proyek.
3.  **Articles (`articles.html`):** Halaman yang memuat daftar artikel atau tulisan.
4.  **Contact (`contact.html`):** Halaman kontak yang dilengkapi dengan struktur form interaktif untuk mengirim pesan.

## 🛠️ Analisis Struktur HTML Semantik

- **`<header>` & `<nav>`:** Digunakan di semua halaman untuk membungkus menu navigasi utama agar konsisten dan mudah diakses oleh pembaca layar (_screen reader_).
- **`<main>` & `<section>`:** Membagi konten inti halaman menjadi blok-blok informasi yang terstruktur secara hierarkis (Home, Projects, Experience, Education, dll).
- **`<article>`:** Digunakan di dalam riwayat pekerjaan untuk memisahkan setiap pengalaman secara mandiri dan utuh.
- **`<form>` & `<textarea>`:** Pada halaman kontak, digunakan untuk menangkap input data nama, email, dan pesan pengguna dengan atribut `required` sebagai validasi dasar.

## 📁 Struktur File Proyek

```text
.
├── index.html          # Halaman utama (Homepage)
├── projects.html       # Halaman daftar proyek
├── articles.html       # Halaman artikel
└── contact.html        # Halaman kontak (Form pesan)
```

- challanges \*
  https://roadmap.sh/projects/basic-html-website
