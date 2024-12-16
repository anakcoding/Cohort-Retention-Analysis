# Cohort Retention Analysis

## Deskripsi Bisnis
Sejak didirikan beberapa tahun yang lalu, toko perhiasan online ini telah mengalami perkembangan yang signifikan dan konsisten. Sebagai sebuah usaha berskala menengah, toko ini berkomitmen untuk menghadirkan produk-produk perhiasan berkualitas tinggi yang mencakup cincin, gelang, anting, kalung, liontin, dan beragam aksesori lainnya.

## Tujuan Analisis
Tujuan utama dari analisis cohort retention untuk Toko Perhiasan Online adalah untuk memahami pola retensi pelanggan berdasarkan kelompok waktu pembelian.

## Problem Statement

Bisnis perhiasan sangat bergantung pada loyalitas pelanggan, tren musiman, dan pemasaran yang tepat sasaran untuk meningkatkan penjualan. Namun, memahami bagaimana kelompok pelanggan tertentu (kohort) berperilaku dari waktu ke waktu sangat penting untuk mengidentifikasi pola retensi, segmen pelanggan bernilai tinggi, dan peluang pertumbuhan.

Dengan menggunakan dataset yang diberikan, proyek ini bertujuan untuk melakukan analisis kohort untuk menjawab pertanyaan utama berikut:
1. Berapa persentase pelanggan yang kembali melakukan pembelian setelah transaksi pertama mereka? Bagaimana tingkat retensi ini bervariasi antar kohort (misalnya, berdasarkan quartil saat mereka menjadi pelanggan)?

2. Apakah pelanggan yang membeli kategori produk tertentu (misalnya, cincin tunangan, kalung) menunjukkan tingkat retensi atau pola pengeluaran yang berbeda?

## Data
Dataset ini berisi pembelian produk perhiasan dari sebuah toko perhiasan online berskala menengah, yang mencakup periode waktu dua tahun dan terdiri dari 95.911 produk yang dibeli. Setiap baris dalam dataset ini mewakili satu produk yang dibeli, dan produk-produk dari satu pesanan yang sama dapat diidentifikasi melalui ID pesanan (`order_id`).

Dataset ini mencakup informasi seperti:

- `date`: Tanggal pembelian produk.

- `order_id`: Nomor identifikasi unik untuk setiap pesanan.

- `product_id`: Nomor identifikasi unik untuk setiap produk.

- `quantity`: Jumlah unit produk yang dibeli dalam satu pesanan.

- `category_id`: Nomor identifikasi unik untuk kategori produk.

- `category_alias`: Nama atau alias dari kategori produk.

- `brand_id`: Nomor identifikasi unik untuk merek produk.

- `price`: Harga produk yang dibeli.

- `user_id`: Nomor identifikasi unik untuk setiap pengguna.

- `gender`: Jenis kelamin pengguna (misalnya, pria atau wanita).

- `color`: Warna produk perhiasan.

- `material`: Bahan dari produk perhiasan (misalnya, emas, perak, dsb).

- `stone`: Jenis batu permata yang digunakan dalam produk perhiasan.

(BELUM TERMASUK KOLOM TAMBAHAN YANG AKAN DI INPUT PADA TAHAP DATA ANALYSIS)
