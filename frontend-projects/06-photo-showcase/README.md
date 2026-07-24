# 📸 Media Gallery & Video Showcase - Apotek Shabah

Proyek ini adalah implementasi **Galeri Foto & Video Aksesibel** yang dibangun menggunakan **HTML5 Murni** sesuai dengan standar **W3C** dan prinsip **Aksesibilitas Web (WCAG)**. Proyek ini menyajikan dokumentasi kegiatan, fasilitas, serta video edukasi Apotek Shabah secara terstruktur, ramah _screen reader_, dan bebas dari pergeseran tata letak (_Layout Shift/CLS_).

---

## 📌 Fitur & Keunggulan Kode

Halaman galeri media ini dibangun dengan memenuhi seluruh kriteria _Media Accessibility_:

- **Struktur Semantik Utuh:** Menggunakan elemen `<header>`, `<main>`, dan `<footer>` sebagai kerangka utama halaman.
- **Optimasi Performa Gambar (_Layout Stability_):**
  - Setiap tag `<img>` dilengkapi atribut `width` dan `height` untuk memesan ruang (_layout space_) guna mencegah _Cumulative Layout Shift_ (CLS) saat gambar dimuat.
  - Atribut `alt` diisi dengan deskripsi gambar yang berguna dan relevan.
- **Gambar Dekoratif (_Decorative Images_):** Menggunakan `alt=""` pada gambar hiasan agar diabaikan oleh alat pembaca layar (_screen reader_) tanpa mengganggu navigasi.
- **Keterangan Foto Aksesibel:** Foto-foto dokumentasi dibungkus rapi menggunakan pasangan tag `<figure>` dan `<figcaption>`.
- **Integrasi Video HTML5 Modern:**
  - Menggunakan elemen `<video>` dengan atribut `controls` untuk kemudahan navigasi pemutaran.
  - Memiliki gambar _thumbnail_ pendahulu menggunakan atribut `poster`.
  - Dilengkapi _fallback text_ di dalam tag video untuk mengantisipasi browser lama yang tidak mendukung pemutaran video HTML5.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** (Semantik Murni & Multimedia Murni)

---

## 📂 Struktur Kode

```text
├── index.html       # File utama galeri foto & video
├── assets/          # Folder media lokal (video & gambar)
│   └── edukasi-tablet-tambah-darah.mp4
└── README.md        # File dokumentasi proyek
```

````

---

## 💻 Cara Menjalankan Proyek

1. **Clone Repositori ini:**

```bash
git clone [https://github.com/wildan-arch/tantangan-roadmap-sh.git](https://github.com/wildan-arch/tantangan-roadmap-sh.git)

```

2. **Buka File di Browser:**

- Klik ganda pada file `index.html` untuk membukanya langsung di browser, ATAU
- Gunakan ekstensi **Live Server** di Visual Studio Code untuk pratinjau lokal interaktif.

---

## 🧑‍💻 Penulis

**Wildan Fajar Pamungkas & Team Apotek Shabah**

Website: _(segera hadir)_

---

## 📝 Lisensi

Proyek ini dibuat untuk tujuan pembelajaran dan dapat digunakan serta dimodifikasi secara bebas.

```

---


```
````
