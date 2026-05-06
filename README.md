# Analisis Komentar Pengguna Aplikasi Sentuh Tanahku
## Tugas UTS Big Data

### Identitas Mahasiswa
* **Nama :** Syaffiyah yustifani
* **NIM :** 14022300044
* **Program Studi :** Sistem Informasi

---

### Deskripsi Penelitian
Project ini dibuat untuk menganalisis komentar pengguna aplikasi **Sentuh Tanahku** yang tersedia di Google Play Store. 

Analisis dilakukan untuk mengetahui:
* Bahasa yang paling sering digunakan pengguna.
* Jenis gaya bahasa dalam komentar.
* Sentimen komentar (positif, negatif, atau netral).
* Topik yang sering dibahas terkait layanan aplikasi.

---

### Pengambilan Dataset
Dataset diambil menggunakan Python dengan library `google-play-scraper`.

* **Jumlah Data:** 100 komentar terbaru.
* **Kolom Data:** `userName`, `score`, `at`, dan `content`.

---

### Metode & Library
Analisis data dilakukan menggunakan pendekatan **NLP (Natural Language Processing)** dengan bantuan library berikut:
* `pandas` (Olah data)
* `matplotlib` (Visualisasi grafik)
* `langdetect` (Deteksi bahasa)
* `google-play-scraper` (Scraping data)

---

### Hasil Analisis

#### Kategori Gaya Bahasa & Sentimen
* **Gaya Bahasa:** Indonesia Umum, Gaul, Sunda, dan Inggris.
* **Sentimen:** Positif, Negatif, dan Netral.

#### Daftar File & Output
| Nama File | Keterangan |
| :--- | :--- |
| `ulasan_google_play.csv` | Dataset mentah dari Play Store |
| `hasil_analisis_lengkap.csv` | Data hasil pemrosesan NLP |
| `grafik_gaya_bahasa.png` | Visualisasi distribusi bahasa |
| `grafik_topik_komentar.png` | Visualisasi topik utama |

---

### Kesimpulan
Berdasarkan hasil analisis, mayoritas pengguna menggunakan Bahasa Indonesia. Sebagian besar komentar berisi kritik dan saran mengenai **login akun, error aplikasi, pendaftaran tanah, serta akses layanan.** Namun, terdapat juga komentar positif yang menyatakan aplikasi membantu proses administrasi secara digital.

**Tools yang digunakan:** Google Colab, Python, Pandas, Matplotlib.
