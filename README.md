# PRAKTIKUM_AI_WORKFLOW
Taslim Nuralim 2306032
Analisis dan Prediksi Penjualan Produk dengan Kecerdasan Buatan
Deskripsi Proyek
Proyek ini bertujuan untuk menerapkan kecerdasan buatan (AI) dalam menganalisis dan memprediksi penjualan produk. Proses yang dilakukan mencakup pembuatan dataset, pembersihan data, pelatihan model AI menggunakan algoritma Decision Tree Classifier, serta visualisasi hasil prediksi.

Tahapan Implementasi
Pembuatan Dataset

Dataset disusun dalam format CSV yang berisi informasi produk, jumlah penjualan, stok, dan harga satuan.
Pembersihan dan Pengolahan Data

Data diperiksa dan diproses untuk memastikan kelengkapan serta kesiapan sebelum digunakan dalam pelatihan model AI.
Pelatihan Model AI

Model Decision Tree Classifier diterapkan untuk memprediksi apakah suatu produk perlu di-restock berdasarkan data penjualan yang tersedia.
Prediksi dan Visualisasi

Model yang telah dilatih digunakan untuk membuat prediksi, serta menyajikan visualisasi hubungan antara jumlah terjual, stok, dan keuntungan.
Cara Menjalankan Kode di Google Colab
Membuka Google Colab

Akses Google Colab melalui peramban.
Pilih opsi "Unggah", lalu unggah file praktikum_ai.ipynb.
Menjalankan Notebook

Jalankan setiap sel kode secara berurutan.
Jika terdapat dependensi tambahan yang diperlukan, instal dengan perintah berikut:
python
Copy
Edit
!pip install scikit-learn
Mengakses File di Google Drive (Opsional)

Jika dataset atau model tersimpan di Google Drive, hubungkan akun dengan perintah berikut:
python
Copy
Edit
from google.colab import drive
drive.mount('/content/drive')
