# ecommerce-shipping-delay-analysis
Analisis faktor keterlambatan pengiriman e-commerce menggunakan machine learning (CRISP-DM)

# 📦 E-Commerce Shipping Delay Analysis

Proyek ini menganalisis faktor-faktor yang mempengaruhi keterlambatan pengiriman barang pada platform e-commerce menggunakan machine learning.

---

## 🎯 Tujuan
Mengidentifikasi variabel utama yang menyebabkan keterlambatan pengiriman, sehingga dapat memberikan insight bisnis untuk meningkatkan ketepatan waktu pengiriman.

---

## 📂 Dataset
- **Sumber:** [Shipping Data](https://raw.githubusercontent.com/arubhasy/dataset/main/Shipping_Data.csv)
- **Jumlah data:** 10.999 baris, 12 kolom
- **Fitur utama:** Warehouse block, Mode of shipment, Customer care calls, Customer rating, Cost of product, Discount offered, Weight in gms

---

## 🔍 Tahapan Analisis
Proyek ini mengikuti metodologi **CRISP-DM** dengan 9 tahapan:

1. 📥 **Data Collection** — identifikasi kebutuhan dan pengumpulan data
2. 🔍 **Data Understanding** — menelaah struktur dan karakteristik data
3. ✅ **Data Validation** — memvalidasi kualitas dan integritas data
4. 🎯 **Data Object Definition** — menentukan objek dan target analisis
5. 🧹 **Data Cleaning** — menangani missing values dan data tidak konsisten
6. 🔧 **Data Construction** — rekonstruksi dan transformasi fitur data
7. 🏷️ **Data Labeling** — menentukan label untuk keperluan modeling
8. 🤖 **Modeling** — membangun model Decision Tree, Random Forest, dll
9. 📏 **Model Evaluation** — mengevaluasi performa dan akurasi model

---

## 💡 Hasil & Kesimpulan
Berdasarkan analisis Feature Importance menggunakan Decision Tree:

- 🥇 **Discount Offered** — faktor paling berpengaruh terhadap keterlambatan pengiriman
- 🥈 **Weight in gms** — berat produk turut mempengaruhi ketepatan pengiriman
- 🥉 **Cost of the Product** — biaya produk menjadi faktor ketiga yang signifikan

> Semakin besar diskon yang diberikan, semakin tinggi kemungkinan pengiriman terlambat.

---

## 🛠️ Tools & Library
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)

---

## 👩‍💻 Author
**Nikmatul Khasanah**
[![GitHub](https://img.shields.io/badge/GitHub-niknycto-181717?style=flat&logo=github)](https://github.com/niknycto)
