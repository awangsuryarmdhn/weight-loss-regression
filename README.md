# Menebak Berat Badan dari Catatan Harian

Materi *Exploratory Data Analysis* (EDA) dengan Python — penjelasan bahasa Indonesia yang sederhana — atas dataset Kaggle "2018 Calorie, Exercise and Weight Changes" (chrisbow): catatan harian kalori, olahraga, dan berat badan selama ±5 bulan.

## Menjalankan

Paling gampang lewat Google Colab (gratis, langsung di browser, HP pun bisa):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/awangsuryarmdhn/weight-loss-regression/blob/main/analisis-regresi-weight-loss.ipynb)

Buka link itu, tekan **Runtime > Run all**. Data (`diet_data.csv`) ikut ada di repo ini, dan notebook juga bisa mengunduhnya sendiri dari Kaggle kalau file tidak ditemukan.

## Alur EDA di notebook

1. Unduh & intip data asli Kaggle (151 hari -> 140 hari bersih)
2. Bersih-bersih data
3. Grafik: tren berat badan & kalori vs perubahan berat
4. Model: seberapa besar pengaruh kalori (+100 kalori &asymp; +78 gram)
5. Cek ulang: donat, wine, protein — tidak terbukti berpengaruh
6. Olahraga: lari terbukti membantu (&minus;7,9 ons)
7. Hari "kalap makan" (>5000 kalori): berat melonjak lalu luruh dalam 2&ndash;3 hari
8. Model final: menjelaskan 73% naik-turun berat harian

Sumber data: https://www.kaggle.com/datasets/chrisbow/2018-calorie-exercise-and-weight-changes
