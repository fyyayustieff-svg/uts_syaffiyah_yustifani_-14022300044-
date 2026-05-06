Analisis Komentar Pengguna Aplikasi sentuh tanahku
Tugas UTS Big Data
Identitas Mahasiswa

    Nama : Syaffiyah yustifani
    NIM : 14022300044
    Program Studi : Sistem Informasi

Deskripsi Penelitian

Project ini dibuat untuk menganalisis komentar pengguna aplikasi Sentuh Tanahku yang tersedia di Google Play Store.

Analisis dilakukan untuk mengetahui:

bahasa yang paling sering digunakan oleh pengguna,
jenis gaya bahasa dalam komentar pengguna,
sentimen komentar (positif, negatif, atau netral),
serta topik yang paling sering dibahas terkait layanan pertanahan dalam aplikasi.

Hasil dari penelitian ini diharapkan dapat memberikan gambaran mengenai persepsi dan pengalaman pengguna, serta menjadi bahan evaluasi untuk meningkatkan kualitas layanan aplikasi Sentuh Tanahku di masa mendatang.

Pengambilan Dataset

Dataset diambil menggunakan Python dan library:

google-play-scraper

Jumlah data yang digunakan:

    100 komentar pengguna terbaru

Kolom data yang diperoleh:

    userName
    score
    at
    content

Metode Analisis

Analisis data dilakukan menggunakan pendekatan NLP (Natural Language Processing).
Library yang digunakan

    pandas
    matplotlib
    langdetect
    google-play-scraper

Analisis yang dilakukan

    Deteksi bahasa komentar
    Klasifikasi gaya bahasa
    Analisis sentimen komentar
    Pengelompokan topik komentar

Kategori Gaya Bahasa

Komentar pengguna dibagi menjadi beberapa kategori:

    Indonesia Umum
    Gaul
    Sunda
    Inggris

Kategori Sentimen

Hasil sentimen dibagi menjadi:

    Positif
    Negatif
    Netral

Hasil File Analisis

File hasil yang dihasilkan:

    ulasan_google_play.csv
    hasil_sentimen.csv
    hasil_analisis_lengkap.csv

Grafik hasil analisis:

    grafik_sentimen.png
    grafik_gaya_bahasa.png
    grafik_topik_komentar.png

Kesimpulan

Berdasarkan hasil analisis, mayoritas pengguna menggunakan Bahasa Indonesia dalam memberikan komentar pada aplikasi Sentuh Tanahku.

Sebagian besar komentar berisi kritik dan saran mengenai:

kendala login akun,
error atau gangguan pada aplikasi,
kesulitan dalam mengakses informasi sertifikat tanah,
serta kecepatan dan kejelasan layanan.

Namun, terdapat juga komentar positif yang menyatakan bahwa aplikasi ini membantu mempermudah masyarakat dalam mengakses layanan pertanahan secara online.

Tools

    Google Colab
    Python
    Pandas
    Matplotlib
    Google Play Scraper
    Langdetect

