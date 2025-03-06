# PRAKTIKUM_AI_WORKFLOW
Taslim Nuralim 2306032
# Analisis dan Prediksi Penjualan Produk dengan Kecerdasan Buatan

## Deskripsi Proyek
Proyek ini bertujuan untuk menerapkan kecerdasan buatan (AI) dalam menganalisis dan memprediksi penjualan produk. Proses yang dilakukan meliputi pembuatan dataset, pembersihan data, pelatihan model AI menggunakan algoritma *Decision Tree Classifier*, serta visualisasi hasil prediksi.

## Tahapan Implementasi

### 1. Pembuatan Dataset
- Dataset dibuat dalam format CSV dan berisi informasi produk, jumlah penjualan, stok, serta harga satuan.

### 2. Pembersihan dan Pengolahan Data
- Memastikan data dalam kondisi bersih, lengkap, dan siap digunakan untuk pelatihan model AI.

### 3. Pelatihan Model AI
- Menggunakan algoritma *Decision Tree Classifier* untuk memprediksi apakah suatu produk perlu di-*restock* berdasarkan data penjualan yang tersedia.

### 4. Prediksi dan Visualisasi
- Model yang telah dilatih digunakan untuk melakukan prediksi.
- Visualisasi disajikan untuk menampilkan hubungan antara jumlah terjual, stok, dan keuntungan.

## Cara Menjalankan Kode di Google Colab

### 1. Membuka Google Colab
- Akses Google Colab melalui peramban.
- Pilih opsi **"Unggah"** dan unggah file `praktikum_ai.ipynb`.

### 2. Menjalankan Notebook
- Jalankan setiap sel kode secara berurutan.
- Jika terdapat dependensi tambahan yang diperlukan, instal dengan perintah berikut:
  ```python
  !pip install scikit-learn
  ```

### 3. Mengakses File di Google Drive (Opsional)
- Jika dataset atau model tersimpan di Google Drive, hubungkan akun dengan perintah berikut:
  ```python
  from google.colab import drive
  drive.mount('/content/drive')
  ```

## Teknologi yang Digunakan
- Python
- Pandas
- Scikit-learn
- Matplotlib/Seaborn (untuk visualisasi data)
