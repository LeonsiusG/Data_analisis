1. Business Question

Tujuan utama dari analisis ini adalah menjawab beberapa pertanyaan bisnis berikut:
Siapa pelanggan terbaik berdasarkan perilaku pembelian (RFM Analysis)?
Bagaimana tren penjualan tiap bulan?
Apakah anggaran iklan (Ad Budget) berpengaruh terhadap total penjualan?
Variabel apa saja yang memiliki hubungan kuat terhadap penjualan?

2. Data Wrangling

Menghapus data tidak valid
Menghapus data dengan Price_Per_Unit <= 0

Konversi tipe data
Kolom Order_Date diubah menjadi format datetime

Feature Engineering
Membuat kolom Month dari Order_Date untuk analisis bulanan

RFM Analysis Preparation
Menghitung:
Recency (seberapa baru transaksi terakhir)
Frequency (jumlah transaksi)
Monetary (total pembelian)

3. Insights

Grafik line menunjukkan fluktuasi penjualan tiap bulan.

Dapat digunakan untuk mengidentifikasi:
Musim dengan penjualan tinggi (peak season)
Penurunan performa penjualan

RFM Analysis
Segmentasi pelanggan berdasarkan:
Recency: Seberapa baru pelanggan bertransaksi
Frequency: Seberapa sering pelanggan membeli
Monetary: Berapa banyak uang yang dibelanjakan
Pelanggan dengan skor tinggi (contoh: 007):
Pelanggan paling loyal dan bernilai tinggi

4. Recommendation

Strategi Marketing:
Tingkatkan anggaran iklan jika terbukti berpengaruh positif
Fokus pada channel iklan yang paling efektif

Customer Retention
Berikan reward atau promo khusus untuk pelanggan dengan skor RFM tinggi
Lakukan re-engagement untuk pelanggan dengan Recency rendah

Optimasi Produk
Fokus pada produk dengan kontribusi penjualan tinggi
Evaluasi produk dengan performa rendah