# Analisis Pola Pembelian Konsumen Menggunakan Algoritma Apriori pada Dataset Online Retail

## Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis pola pembelian konsumen menggunakan teknik **Association Rule Mining** dengan **Algoritma Apriori** pada dataset *Online Retail*. Analisis dilakukan untuk menemukan hubungan antar produk yang sering dibeli secara bersamaan sehingga dapat digunakan sebagai dasar pengambilan keputusan bisnis, seperti **product bundling**, **cross-selling**, dan **rekomendasi produk**.

## Analisis yang Dilakukan

Tahapan analisis dilakukan menggunakan metode **CRISP-DM (Cross Industry Standard Process for Data Mining)**, yang meliputi:

### 1. Business Understanding
Menentukan tujuan analisis untuk menemukan pola pembelian konsumen dan menghasilkan rekomendasi strategi pemasaran yang lebih efektif.

### 2. Data Understanding
Melakukan eksplorasi data untuk memahami struktur dataset, jumlah transaksi, serta karakteristik produk yang tersedia.

### 3. Data Preparation
Membersihkan data dengan menghapus nilai kosong (*missing values*), transaksi pembatalan (*cancelled transactions*), dan data yang tidak valid agar siap digunakan dalam proses analisis.

### 4. Modeling
Menerapkan Algoritma Apriori untuk menghasilkan *frequent itemsets* dan *association rules* berdasarkan pola pembelian konsumen.

### 5. Evaluation
Mengevaluasi hasil aturan asosiasi menggunakan metrik **Support**, **Confidence**, dan **Lift Ratio** untuk menentukan kekuatan hubungan antar produk.

### 6. Deployment
Menyajikan hasil analisis dalam bentuk visualisasi dan rekomendasi bisnis yang dapat digunakan untuk mendukung pengambilan keputusan.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Mlxtend

## Metode

- CRISP-DM
- Association Rule Mining
- Apriori Algorithm

## Hasil Analisis

| Metrik | Hasil |
|---------|---------|
| Frequent Itemsets | 1.102 |
| Association Rules (Lift > 1) | 174 |
| Average Confidence | 61,90% |
| Average Lift Ratio | 21,35 |

## Insight Utama

- Ditemukan berbagai kombinasi produk yang sering dibeli secara bersamaan oleh pelanggan.
- Aturan asosiasi yang dihasilkan memiliki nilai **Lift > 1**, yang menunjukkan adanya hubungan positif antar produk.
- Hasil analisis dapat dimanfaatkan untuk strategi **cross-selling**, **product bundling**, dan **sistem rekomendasi produk**.
- Pola pembelian yang ditemukan dapat membantu perusahaan meningkatkan efektivitas promosi dan penjualan.

## Portofolio

🌐 https://sites.google.com/view/asosiasi-data-mining

## Video Presentasi

🔗 Tambahkan link YouTube di sini

## Dataset

📊 https://www.kaggle.com/code/riskypradipapurba/laporan-analisis-data-penjualan-retail-online

---

**Author:** Revani Nurul Fadilla

**Program Studi:** Sistem Informasi 
