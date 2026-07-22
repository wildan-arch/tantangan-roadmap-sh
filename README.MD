Karena repositori **`tantangan-roadmap-sh`** kamu sekarang berfungsi sebagai **Monorepo** (satu repo besar yang menampung banyak sub-folder proyek), isi file `README.md` utama di luar (root) harus menjadi **daftar isi utama / portal rangkuman** untuk semua tantangan yang kamu kerjakan.

Di dalamnya, kamu **wajib menempelkan link _Project URL_** dari tiap tugas Roadmap.sh agar bot verifikasinya selalu lolos 3 centang hijau!

---

### Isi File `README.md` Utama (Root)

Kamu bisa menyalin (_copy-paste_) template lengkap di bawah ini untuk ditaruh di file `README.md` yang berada **di folder utama `tantangan-roadmap-sh**`:

````markdown
# Roadmap.sh Frontend Challenges 🚀

Repositori ini berisi kumpulan dokumentasi dan penyelesaian tantangan proyek **Frontend Development** dari platform [roadmap.sh](https://roadmap.sh/). Semua proyek dibuat fokus pada struktur **Semantic HTML**, aksesibilitas, serta _clean code_.

---

## 📁 Daftar Proyek & Solusi

|   No   | Nama Proyek             | Teknologi | Link Tugas Roadmap.sh                                                                 |  Status   |
| :----: | :---------------------- | :-------: | :------------------------------------------------------------------------------------ | :-------: |
| **01** | `01-single-page-cv`     |   HTML5   | [Single-Page CV Project](https://roadmap.sh/projects/single-page-cv)                  | Completed |
| **02** | `02-basic-html-website` |   HTML5   | [Basic HTML Website Project](https://roadmap.sh/projects/basic-html-website)          | Completed |
| **03** | `03-comparison-table`   |   HTML5   | [HTML Comparison Table Project](https://roadmap.sh/projects/pricing-comparison-table) | Completed |

---

## 📌 Catatan Verifikasi Roadmap.sh

> _Tautan di bawah ini digunakan oleh bot verifikasi otomatis Roadmap.sh untuk memvalidasi submission:_
>
> - **Comparison Table Project URL:** `https://roadmap.sh/projects/html-comparison-table`
> - **Basic HTML Website Project URL:** `https://roadmap.sh/projects/basic-html-website`
> - **Single-Page CV Project URL:** `https://roadmap.sh/projects/single-page-cv`

---

## 🛠️ Cara Menjalankan Proyek di Lokal

1. **Clone repositori ini:**
   ```bash
   git clone [https://github.com/wildan-arch/tantangan-roadmap-sh.git](https://github.com/wildan-arch/tantangan-roadmap-sh.git)
   ```
````

2. **Masuk ke folder repositori:**

```bash
cd tantangan-roadmap-sh

```

3. **Buka sub-folder proyek yang ingin kamu lihat:**
   Misalnya untuk melihat tugas Comparison Table, masuk ke folder `03-comparison-table` dan buka file `.html`-nya di browser.

---

_Dikembangkan oleh [Wildan Fajar Pamungkas](https://www.google.com/search?q=https://github.com/wildan-arch) - 2026_

```

---

### 💡 Keunggulan Format Ini:

1. **Mencakup Syarat Bot:** Bagian *Catatan Verifikasi* secara eksplisit memuat tautan `project URL` yang dicari oleh bot Roadmap.sh.
2. **Sangat Rapi di Profil GitHub:** Tabel di atas akan membuat repositori utamamu terlihat sangat profesional bagi siapa pun atau HRD yang melihat akun GitHub-mu.
3. **Mudah Ditambah:** Nanti kalau kamu mengerjakan tugas ke-4 (misal: `04-changelog-component`), kamu tinggal menambah baris baru di tabel tersebut!

Setelah menyalin teks ini ke file `README.md` utama, jalankan `git add README.md`, `git commit -m "Update root README"`, dan `git push origin main`. Setelah itu, coba klik **Verify and Submit** lagi di Roadmap.sh!

```
