# 📬 Contact Form - Accessible & Validated HTML5 Form

Proyek ini adalah implementasi **Formulir Kontak Aksesibel** yang dibangun menggunakan **HTML5 Murni** sesuai dengan standar **W3C** dan prinsip **Aksesibilitas Web (WCAG)**. Proyek ini berfokus pada struktur formulir yang semantik, keterhubungan label & input yang presisi, serta validasi bawaan browser (_Native Browser Validation_).

---

## 📌 Fitur & Keunggulan Kode

Halaman formulir ini dibuat untuk memenuhi seluruh kriteria _Form Accessibility_:

- **Struktur Form Semantik:** Menggunakan elemen `<form>` dengan metode `post` dan elemen pendukung seperti `<fieldset>` dan `<legend>` untuk mengelompokkan opsi radio.
- **Labeling Aksesibel (Real Labels):**
  - Setiap bidang input (`text`, `email`, `select`, `textarea`, `radio`, dan `checkbox`) terhubung sempurna dengan tag `<label>` asli via atribut `for` dan `id`.
  - Memudahkan navigasi pembaca layar (_screen reader_) serta pengguna kursor/touchscreen.
- **Validasi Bawaan Browser (Client-Side UX Layer):**
  - Penggunaan atribut `required` pada bidang wajib diisi.
  - Penggunaan `type="email"` untuk validasi format alamat email otomatis.
  - Batasan jumlah teks minimal `minlength="10"` pada area pesan (`<textarea>`).
- **Input Pilihan Terstruktur:**
  - Pilihan subjek pesan menggunakan `<select>` dan `<option>`.
  - Pilihan grup sumber informasi menggunakan `<input type="radio">` dengan `name` yang selaras.
  - Opsi persetujuan syarat & ketentuan menggunakan `<input type="checkbox">`.
- **Tombol Aksi Jelas:** Menggunakan `<button type="submit">` dengan instruksi teks yang deskriptif.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** (Semantik Murni tanpa dependensi eksternal)

---

## 📂 Struktur Kode

```text
├── index.html       # File utama formulir kontak HTML5
└── README.md        # File dokumentasi proyek
```
