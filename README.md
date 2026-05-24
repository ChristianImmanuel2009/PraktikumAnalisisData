# Praktikum Analisis dan Visualisasi Data

## Analisis Performa Penjualan E-commerce

### Deskripsi Praktikum

Praktikum ini dilakukan untuk menganalisis performa penjualan pada data E-commerce menggunakan Python dan beberapa library seperti Pandas, NumPy, Matplotlib, dan Seaborn. Analisis dilakukan untuk memahami pola penjualan, mengidentifikasi produk yang kurang optimal, serta memberikan rekomendasi berdasarkan hasil visualisasi data.

---

## Business Question

Pada praktikum ini terdapat beberapa pertanyaan bisnis yang ingin dijawab:

1. Produk apa yang mengalami underperform?
2. Bagaimana segmentasi pelanggan menggunakan metode RFM Analysis?
3. Kategori produk mana yang memiliki efisiensi paling tinggi?
4. Apakah budget iklan mempengaruhi total penjualan?

---

## Data Wrangling

Sebelum data dianalisis, dilakukan proses pembersihan dan pemeriksaan data terlebih dahulu.

Tahapan yang dilakukan:

1. Mengimpor dataset menggunakan Pandas
2. Memeriksa struktur data menggunakan `df.info()`
3. Memeriksa data kosong menggunakan `df.isnull().sum()`
4. Mengubah tipe data kolom tanggal menggunakan `pd.to_datetime()`
5. Menghapus data anomali seperti harga yang kurang dari atau sama dengan nol

Tujuan dari proses ini adalah agar data yang digunakan lebih bersih dan menghasilkan analisis yang lebih akurat.

---

## Hasil Visualisasi dan Analisis

### Analisis Produk Underperform

Visualisasi menggunakan Scatter Plot dilakukan dengan:

- Sumbu X = Harga per unit
- Sumbu Y = Jumlah pembelian (Quantity)

Tujuan visualisasi ini adalah untuk mengetahui apakah harga produk yang tinggi memengaruhi jumlah pembelian.

### Insight

Berdasarkan hasil scatter plot yang diperoleh, terlihat bahwa beberapa produk dengan harga per unit yang tinggi cenderung memiliki jumlah pembelian yang lebih rendah.

Hal ini menunjukkan bahwa harga dapat menjadi salah satu faktor yang memengaruhi keputusan pelanggan dalam melakukan pembelian. Produk dengan harga tinggi berpotensi mengalami penurunan volume penjualan apabila tidak diimbangi dengan strategi pemasaran atau nilai tambah produk.

---

## Recommendation

Berdasarkan hasil analisis yang dilakukan, terdapat beberapa rekomendasi yang dapat diberikan:

1. Melakukan evaluasi terhadap produk dengan volume penjualan rendah
2. Memberikan promo atau diskon pada produk yang mengalami underperform
3. Memfokuskan pemasaran pada kategori dengan performa lebih baik
4. Mengoptimalkan strategi pemasaran agar dapat meningkatkan penjualan
5. Melakukan evaluasi terhadap hubungan antara harga produk dan minat pelanggan

---

## Kesimpulan

Berdasarkan analisis yang telah dilakukan, dapat disimpulkan bahwa visualisasi data dapat membantu memahami pola penjualan dan perilaku pelanggan. Dari hasil analisis juga terlihat bahwa harga produk dapat memengaruhi jumlah pembelian. Oleh karena itu, perusahaan perlu mempertimbangkan strategi harga dan pemasaran agar penjualan dapat meningkat.
