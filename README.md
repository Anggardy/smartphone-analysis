# 📱 Smartphone Data Analysis: Mid-to-High Range 5G Market

## 📋 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis pasar smartphone 5G pada rentang harga 20.000-50.000. Analisis yang dilakukan menggunakan dataset dari Kaggle berdasarkan harga smartphone di India. Beberapa indikator kunci yang dianalisis dari data ini adalah average rating, harga, dan spesifikasi ponsel.

## ⌨️ Step Analysis
1. Data Collection : Kaggle ()
2. Data Preparation : Formatting data, Cleaning data, check Outlier.
3. EDA: Melihat Top Brand, Analisis korelasi, dan Perbandingan spesifikasi.

## 🛠️ Tech Stack
- Bahasa : Python
- Libraries : Pandas,, NumPy, Matpplotlib, Seaborn, Scipy
- Tool : Google Colab

## 📊 Temuan Utama (Key Insights)
### Ponsel terbaik berdasarkan rating:
![top_brand](/images/brand_compare.png)

Berdasarkan hasil yang ada, dapat dilihat bahwa brand dengan nilai rata-rata rating terbaik didapat oleh Motorola dengan nilai rating rata-rata sebesar 8,55 dibanding dengan Samsung sebesar 8,49. Nilai ini dilihat dari daftar brand yang memiliki jumlah model lebih dari 10 kemudian dilihat rata-ratanya. 

### Melihat analisis korelasi antara harga dan kualitas (rating).
![top_brand](/images/Korelasi.png)
![top_brand](/images/korelasi_scatterplot.png)

Berdasarkan analisis ini, dapat dilihat bahwa nilai harga memiliki hubungan yang sangat erat yakni mencapai 0,59. Hal ini juga diperkuat ketika dilakuakn pengujian p-value yang mendapatkan nilai p-value sebesar 0,000. Bukti lain juga bisa dilihat melalui hubungannya antara avg_rating dan processor_speed dimana nilainya sebesar 0,59 kemudian processor_speed dengan harga yang nilainya 0,55.

## 💡 Rekomendasi Bisnis
1. Berdasarkan data, produk dari brand motorola dan samsung bisa lebih diprioritaskan pada rentang HP mid-range 5g.
2. Selain itu, Xiaomi juga bisa menjadi opsi tambahan karena dapat dilihat bahwa modelnya mencapai 31 jenis model.
3. Tonjolkan beberapa fitur lain yang dapat menambah minat pembeli.
