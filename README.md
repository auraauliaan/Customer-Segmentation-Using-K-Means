# Customer Segmentation Using K-Means

Repositori ini dibuat untuk memenuhi Tugas Besar mata kuliah **Machine Learning**. Proyek ini bertujuan untuk melakukan segmentasi pelanggan menggunakan algoritma **K-Means Clustering** berdasarkan atribut perilaku pelanggan.

Kelompok 3 dengan anggota sebagai berikut : 
1. AURA AULIA A.H.P 		(1206230003)
2. JONATHAN MANGIRING P	(1206230051)
3. NOVITA CHELSEA LODAR	(1206230052)

## 📁 Struktur Repository

- [`Copy_of_Tubes_ML.ipynb`](https://github.com/auraauliaan/Customer-Segmentation-Using-K-Means/blob/main/Copy_of_Tubes_ML.ipynb) – Notebook berisi implementasi K-Means Clustering.
- [`marketing_campaign.csv`](https://github.com/auraauliaan/Customer-Segmentation-Using-K-Means/blob/main/marketing_campaign.csv) – Dataset yang digunakan untuk analisis, berasal dari [Kaggle: Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis).
- [`README.md`](https://github.com/auraauliaan/Customer-Segmentation-Using-K-Means/blob/main/README.md) – Dokumentasi proyek.

## 📊 Deskripsi Dataset

Dataset berisi informasi demografi dan perilaku pembelian pelanggan. Berikut penjelasan setiap fitur:

| **Fitur**               | **Deskripsi**                                                                 |
|------------------------|-------------------------------------------------------------------------------|
| `ID`                   | ID unik untuk setiap pelanggan                                                |
| `Year_Birth`           | Tahun kelahiran pelanggan                                                     |
| `Education`            | Tingkat pendidikan pelanggan                                                  |
| `Marital_Status`       | Status pernikahan pelanggan                                                   |
| `Income`               | Pendapatan tahunan rumah tangga pelanggan                                     |
| `Kidhome`              | Jumlah anak kecil di rumah pelanggan                                          |
| `Teenhome`             | Jumlah remaja di rumah pelanggan                                              |
| `Dt_Customer`          | Tanggal pertama kali pelanggan bergabung                                      |
| `Recency`              | Jumlah hari sejak pembelian terakhir                                          |
| `Complain`             | 1 jika pelanggan pernah komplain dalam 2 tahun terakhir, 0 jika tidak         |
| `MntWines`             | Total pengeluaran untuk anggur dalam 2 tahun terakhir                         |
| `MntFruits`            | Total pengeluaran untuk buah dalam 2 tahun terakhir                           |
| `MntMeatProducts`      | Total pengeluaran untuk daging dalam 2 tahun terakhir                         |
| `MntFishProducts`      | Total pengeluaran untuk ikan dalam 2 tahun terakhir                           |
| `MntSweetProducts`     | Total pengeluaran untuk makanan manis dalam 2 tahun terakhir                  |
| `MntGoldProds`         | Total pengeluaran untuk produk emas dalam 2 tahun terakhir                    |
| `NumDealsPurchases`    | Jumlah pembelian dengan diskon                                                |
| `AcceptedCmp1`         | 1 jika pelanggan menerima tawaran kampanye ke-1, 0 jika tidak                 |
| `AcceptedCmp2`         | 1 jika pelanggan menerima tawaran kampanye ke-2, 0 jika tidak                 |
| `AcceptedCmp3`         | 1 jika pelanggan menerima tawaran kampanye ke-3, 0 jika tidak                 |
| `AcceptedCmp4`         | 1 jika pelanggan menerima tawaran kampanye ke-4, 0 jika tidak                 |
| `AcceptedCmp5`         | 1 jika pelanggan menerima tawaran kampanye ke-5, 0 jika tidak                 |
| `Response`             | 1 jika pelanggan menerima tawaran kampanye terakhir, 0 jika tidak             |
| `NumWebPurchases`      | Jumlah pembelian melalui situs web                                            |
| `NumCatalogPurchases`  | Jumlah pembelian menggunakan katalog                                          |
| `NumStorePurchases`    | Jumlah pembelian langsung di toko                                             |
| `NumWebVisitsMonth`    | Jumlah kunjungan ke situs dalam sebulan terakhir                              |
| `Z_CostContact`        | Variabel dummy (semua bernilai sama, diabaikan)                              |
| `Z_Revenue`            | Variabel dummy (semua bernilai sama, diabaikan)                              |

## 🧠 Algoritma

Algoritma utama yang digunakan:
- **K-Means Clustering**
  - Inisialisasi centroid
  - Menentukan klaster berdasarkan jarak Euclidean
  - Pembaruan centroid hingga konvergen

## 🎯 Tujuan Analisis

- Mengelompokkan pelanggan menjadi segmen-segmen berdasarkan perilaku belanja
- Mendukung pengambilan keputusan strategis dalam pemasaran

## 🚀 Cara Menjalankan

1. Buka file notebook [`Copy_of_Tubes_ML.ipynb`](https://github.com/auraauliaan/Customer-Segmentation-Using-K-Means/blob/main/Copy_of_Tubes_ML.ipynb) di Jupyter Notebook atau Google Colab.
2. Pastikan file [`marketing_campaign.csv`](https://github.com/auraauliaan/Customer-Segmentation-Using-K-Means/blob/main/marketing_campaign.csv) tersedia dalam direktori kerja.
3. Jalankan setiap cell secara berurutan.

## 📦 File Tambahan

1. 💻 Kaggle Dataset: [Customer Personality Analysis – by Imakash3011](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  
2. ☁️ Google Colab: [Link Colab](https://colab.research.google.com/drive/1fH8XSXyUS_8t71VUiP7RHPAcswP1QC6Z#scrollTo=jaglmAG8w6j7)  
3. 📄 Laporan: *([LAPORAN ML Kelompok 3](https://github.com/auraauliaan/Customer-Segmentation-Using-K-Means/blob/main/LAPORAN%20ML%20Kelompok%203.pdf))*  
4. 🎥 Link YouTube: [Youtube](https://youtu.be/vfCgZmcntyU?si=dvdAsgwybFcMJd4v)
