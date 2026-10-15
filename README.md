# Menebak Berat Badan dari Catatan Harian

Materi *predictive analytics* (analitik prediktif) dengan Python — penjelasan bahasa Indonesia yang sederhana — atas dataset Kaggle "2018 Calorie, Exercise and Weight Changes" (chrisbow): catatan harian kalori, olahraga, dan berat badan selama ±5 bulan.

## Menjalankan

Paling gampang lewat Google Colab (gratis, langsung di browser, HP pun bisa):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/awangsuryarmdhn/weight-loss-regression/blob/main/analisis-regresi-weight-loss.ipynb)

Buka link itu, tekan **Runtime > Run all**. Data (`diet_data.csv`) ikut ada di repo ini, dan notebook juga bisa mengunduhnya sendiri dari Kaggle kalau file tidak ditemukan.

## Alur di notebook

1. Siapkan data (ambil, intip, bersihkan: 151 hari -> 140 hari)
2. Bangun model (tren, korelasi, regresi: +100 kalori &asymp; +78 gram)
3. Uji & evaluasi (donat/wine/protein tidak terbukti; lari &minus;7,9 ons terbukti; R&sup2; 73%)
4. Coba meramal (pakai model untuk prediksi besok)
5. Simpulkan

Sumber data: https://www.kaggle.com/datasets/chrisbow/2018-calorie-exercise-and-weight-changes
