# E-Commerce Customer Segmentation Analysis

## Latar Belakang Bisnis
Proyek ini bertujuan untuk menganalisis basis pelanggan dari sebuah perusahaan E-Commerce di Brasil (Olist) guna membagi pelanggan ke dalam beberapa segmen berdasarkan total pengeluaran mereka. Hasil segmentasi ini digunakan untuk merumuskan strategi pemasaran yang lebih tepat sasaran.

## Tools & Library yang Digunakan
- Bahasa Pemrograman: Python
- Manipulasi Data: Pandas
- Visualisasi Data: Matplotlib, Seaborn
- Sumber Data: [Olist Brazilian E-Commerce Dataset (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Langkah Kerja (End-to-End)
1. Data Pengumpulan: Menggabungkan 3 tabel _database_ yang terpisah (Customers, Orders, Payments).
2. Pembersihan Data: Menghapus transaksi yang tidak selesai / dibatalkan.
3. Exploratory Data Analysis (EDA): Menghitung total belanja per individu pelanggan.
4. Segmentasi: Membagi pelanggan ke dalam 3 kelas: Sultan (High Value), Reguler (Mid Value), dan Hemat (Low Value).

## Kesimpulan & Rekomendasi Bisnis
Kesimpulan Utama (Key Insights)
Dari hasil eksplorasi dan segmentasi data pelanggan Olist E-Commerce, ada temuan perilaku konsumen yang sangat menarik:
1. Ilusi Kuantitas vs Omzet: Secara jumlah kepala, pelanggan di segmen Hemat (Low Value) sangat mendominasi pasar dengan total lebih dari 60.000 orang. Namun, tulang punggung pendapatan perusahaan justru dipegang oleh segmen Reguler (Mid Value) yang menyumbang porsi omzet terbesar, yaitu 42,7%.
2. Kekuatan Daya Beli Segmen VIP: Kelompok pelanggan Sultan (High Value) ukurannya paling kecil (kurang dari 5.000 orang). Meski begitu, mereka memiliki daya beli yang sangat kuat dan mampu menyumbang lebih dari seperempat total pendapatan perusahaan (25,5%).

Rekomendasi Strategi (Actionable Items)
Karena setiap segmen punya karakteristik belanja yang berbeda, strategi marketing tidak bisa disamaratakan. Berikut rekomendasi untuk tim bisnis:
1. Untuk Segmen Reguler (Fokus: Retensi & Peningkatan Belanja):Sebagai penyumbang omzet terbesar, prioritas utama adalah menjaga mereka tetap berbelanja di platform kita. Tawarkan program loyalty point atau algoritma rekomendasi produk pelengkap (cross-selling) saat mereka berada di halaman checkout.
2. Untuk Segmen Hemat (Fokus: Volume & Up-Selling):Target utamanya adalah "memaksa" mereka membelanjakan uang sedikit lebih banyak di setiap transaksi. Terapkan strategi bundling produk (misal: "Beli 2 Diskon 15%") atau berikan kupon gratis ongkir dengan syarat minimal belanja (di atas rata-rata pengeluaran mereka saat ini) agar perlahan mereka naik kelas ke segmen Reguler.
3. Untuk Segmen Sultan (Fokus: Eksklusivitas):Kehilangan satu pelanggan di segmen ini sama dampaknya dengan kehilangan puluhan pelanggan Hemat. Berikan pengalaman VIP yang personal, seperti Customer Service tanpa antre, akses eksklusif untuk peluncuran produk baru, atau kurasi produk premium bulanan.
