# EDA: Harga Rumah di Jakarta

Materi *Exploratory Data Analysis* (EDA) dengan Python — penjelasan bahasa Indonesia yang sederhana — atas dataset Kaggle "Jakarta House Price Dataset" (abiyyurasyiq): 10.000 listing rumah di Jakarta (harga, wilayah, luas tanah, luas bangunan, jumlah kamar).

## Menjalankan

Paling gampang lewat Google Colab (gratis, langsung di browser, HP pun bisa):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/awangsuryarmdhn/weight-loss-regression/blob/main/eda-harga-rumah-jakarta.ipynb)

Buka link itu, tekan **Runtime > Run all**. Data diunduh otomatis dari Kaggle saat dijalankan.

## Alur EDA di notebook

1. Unduh & intip data (10.000 -> 9.992 baris bersih)
2. Bersih-bersih data
3. Peta korelasi: luas tanah (0,70) & luas bangunan (0,63) paling menentukan harga
4. Sebaran harga: median Rp 4,5 miliar
5. Beda wilayah: Jakarta Selatan Rp 8,8 M ... Jakarta Timur Rp 2,45 M
6. Model sederhana: tiap +1 m2 luas bangunan &asymp; +Rp 35 juta (R&sup2; 39%)
7. Model lengkap (+ luas tanah, kamar): R&sup2; 52%

Sumber data: https://www.kaggle.com/datasets/abiyyurasyiq/jakarta-house-price-dataset
