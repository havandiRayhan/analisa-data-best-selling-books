Laporan Analisis Data Buku Best Seller

📌 Deskripsi Proyek

Proyek ini menyajikan hasil Analisis Data Eksploratif (EDA) terhadap dataset buku-buku best seller. Tujuan utama dari analisis ini adalah untuk memahami karakteristik data, melakukan pembersihan terhadap data yang tidak lengkap, serta menggali insight terkait buku dan penulis dengan penjualan tertinggi. Selain itu, proyek ini juga membandingkan tren buku berdasarkan tahun terbitnya.

🗂️ Informasi Data

Sumber Data: Dataset Penjualan Buku (data_buku).
Fokus Analisis: Pembersihan data, Tren Penjualan, Penulis Terlaris, dan Rentang Tahun Terbit.

🧹 Proses Data Cleaning

Sebelum analisis lanjutan, tahap pengecekan dan pembersihan data dilakukan untuk memastikan akurasi hasil.

- Ditemukan adanya kekosongan data (missing values) pada kolom Genre dalam dataset.
- Seluruh nilai yang kosong pada kolom Genre diganti secara serentak dengan label "UNKNOWN".
- Pendekatan penggantian label ini dilakukan untuk menghindari penghapusan baris data yang memuat informasi penting lainnya, seperti judul   dan angka penjualan.
- Melalui metode ini, integritas jumlah data tetap terjaga 100% dan analisis komprehensif tetap dapat dijalankan dengan baik.

📊 Analisis dan Visualisasi Utama

Data diekstraksi ke dalam beberapa metrik dan komparasi utama:

- Penulis & Buku Terlaris: Memetakan daftar 10 Buku dengan Penjualan Tertinggi dan 10 Penulis dengan Total Penjualan Tertinggi secara global.
- Tren Tahun Terbit: Membagi data ke dalam dua kelompok analisis komparasi, yaitu Karya Klasik (10 Buku Tertua) dan Literatur Modern (10 Buku Terbaru).
- Performa Genre: Menyajikan grafik yang menganalisis total penjualan buku berdasarkan genre (Top 10) dan rata-rata penjualan per genre (Top 10). Visualisasi menunjukkan genre Fantasy memimpin angka total penjualan , sementara genre Novella mencetak rata-rata penjualan tertinggi.

💡 Kesimpulan

Dari keseluruhan proses analisis, ditarik beberapa kesimpulan utama:

1. Dataset telah berhasil dibersihkan dari missing value, sehingga analisis dapat berjalan dengan valid.
2. Kesuksesan literatur terbukti tidak dibatasi oleh zaman. Baik literatur klasik yang berusia ratusan tahun maupun karya fiksi kontemporer memiliki pasarnya masing-masing yang sangat masif.
3. Akumulasi penjualan tertinggi secara umum dipegang oleh penulis yang berhasil membangun semesta fiksi atau merilis buku dalam format berseri. Format ini terbukti mampu mengikat pembaca untuk terus membeli karya-karya selanjutnya.
