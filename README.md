# Analisis Komentar Pengguna Aplikasi Sentuh Tanahku
## Tugas UTS Big Data

### Identitas Mahasiswa
* **Nama :** Syaffiyah yustifani
* **NIM :** 14022300044
* **Program Studi :** Sistem Informasi

---

### Deskripsi Penelitian
Project ini dibuat untuk menganalisis komentar pengguna aplikasi **Sentuh Tanahku** yang tersedia di Google Play Store.

**Tujuan Analisis:**
* Mengetahui bahasa yang paling sering digunakan pengguna.
* Mengklasifikasikan jenis gaya bahasa komentar.
* Menentukan sentimen komentar (positif, negatif, atau netral).
* Mengidentifikasi topik yang paling sering dibahas pengguna aplikasi.

---

### Pengambilan Dataset
Dataset dikumpulkan secara otomatis dengan ketentuan:
* **Tools:** Python & Library `google-play-scraper`.
* **Jumlah Data:** 100 komentar terbaru.
* **Atribut Data:** `userName`, `score`, `at`, `content`.

---

### Metode Analisis
Proses pengolahan data menggunakan pendekatan **NLP (Natural Language Processing)** dengan tahapan:
1. **Deteksi Bahasa Komentar:** Mengidentifikasi bahasa yang digunakan pengguna.
2. **Klasifikasi Gaya Bahasa:** Mengelompokkan jenis bahasa (Indonesia Umum, Gaul, Sunda, dll).
3. **Analisis Sentimen:** Menilai apakah komentar bersifat positif, negatif, atau netral.
4. **Pengelompokan Topik:** Menentukan isu utama terkait layanan pertanahan.

---

### Kategori Hasil Analisis

#### 1. Kategori Gaya Bahasa
* **Indonesia Umum**
* **Gaul**
* **Sunda**
* **Inggris**

#### 2. Kategori Sentimen
* **Positif:** Kepuasan pengguna terhadap layanan.
* **Netral:** Pertanyaan atau saran penggunaan.
* **Negatif:** Keluhan teknis atau kendala aplikasi.

---

### Hasil File & Output
| Jenis Output | Nama File |
| :--- | :--- |
| **Dataset Mentah** | `ulasan_google_play.csv` |
| **Data Terolah** | `hasil_sentimen.csv`, `hasil_analisis_lengkap.csv` |
| **Visualisasi (PNG)** | `grafik_sentimen.png`, `grafik_gaya_bahasa.png`, `grafik_topik_komentar.png` |

---

### Kesimpulan
Berdasarkan hasil analisis, mayoritas pengguna menggunakan **Bahasa Indonesia**. Sebagian besar komentar berisi kritik dan saran mengenai:
* **Masalah login akun & error aplikasi.**
* **Pendaftaran tanah & akses layanan pertanahan.**
* *Catatan:* Terdapat sentimen positif bagi pengguna yang merasa terbantu dalam pengecekan berkas tanah secara digital.

---

### Tools & Library
* **Environment:** Google Colab
* **Bahasa:** Python
* **Library:** `Pandas`, `Matplotlib`, `Langdetect`, `Google Play Scraper`
*
