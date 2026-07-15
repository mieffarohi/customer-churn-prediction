# 📉 Fixed Broadband Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

## 📌 Project Overview

Customer churn merupakan salah satu tantangan terbesar dalam industri telekomunikasi. Kehilangan pelanggan tidak hanya berdampak pada penurunan pendapatan, tetapi juga meningkatkan biaya akuisisi pelanggan baru. Oleh karena itu, perusahaan perlu mengidentifikasi pelanggan yang berpotensi berhenti menggunakan layanan sejak dini agar dapat melakukan strategi retensi yang lebih efektif.

Pada proyek ini dilakukan pembangunan model **Machine Learning** untuk memprediksi kemungkinan pelanggan melakukan **churn** berdasarkan karakteristik pelanggan, paket layanan, kontrak, hingga riwayat penggunaan layanan internet.

---

## 🎯 Objectives

- Melakukan eksplorasi data pelanggan fixed broadband.
- Mengidentifikasi faktor-faktor yang memengaruhi customer churn.
- Membangun model prediksi churn menggunakan Machine Learning.
- Mengevaluasi performa model menggunakan beberapa metrik klasifikasi.
- Memberikan insight dan rekomendasi bisnis untuk meningkatkan retensi pelanggan.

---

## 📊 Dataset

Dataset yang digunakan merupakan **data sintetis pelanggan Fixed Broadband** dengan total sekitar **1.200 pelanggan**.

### Variabel yang digunakan

- Region
- Contract Type
- Service Package
- Internet Speed
- Monthly Charge
- Downtime Hours
- Tenure
- AutoPay
- Churn (Target)

**Target**

- **0** : Pelanggan aktif
- **1** : Pelanggan churn

---

## 🛠️ Tools & Library

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 🔍 Tahapan Analisis

## 1. Exploratory Data Analysis (EDA)

Tahapan yang dilakukan:

- Pemeriksaan missing value
- Pemeriksaan data duplikat
- Deteksi outlier menggunakan metode IQR
- Analisis distribusi data
- Analisis hubungan antar variabel
- Analisis korelasi

---

## 2. Feature Engineering

Beberapa proses yang dilakukan antara lain:

- Encoding variabel kategorikal
- Persiapan data untuk model
- Pembagian data training dan testing

---

## 3. Model Development

Model yang digunakan:

- **Random Forest Classifier**

Optimasi model dilakukan menggunakan:

- **GridSearchCV**

---

## 4. Evaluasi Model

Evaluasi dilakukan menggunakan metrik:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

### Hasil Evaluasi

Model memperoleh nilai **ROC-AUC sebesar 0,58**.

Hasil tersebut menunjukkan bahwa model sudah mampu mengenali pola dasar customer churn, namun masih memiliki ruang untuk ditingkatkan melalui penambahan fitur, penyeimbangan data, maupun penggunaan algoritma lain.

---

# 📈 Insight Bisnis

Berdasarkan hasil analisis diperoleh beberapa insight penting:

- Pelanggan dengan **kontrak bulanan (Monthly)** memiliki risiko churn lebih tinggi dibandingkan kontrak tahunan.
- Pelanggan yang **tidak menggunakan AutoPay** cenderung lebih sering melakukan churn.
- Paket internet dengan kecepatan tinggi memiliki biaya bulanan yang lebih besar.
- Jenis kontrak dan metode pembayaran memberikan pengaruh yang lebih besar dibandingkan wilayah pelanggan.

---

# 💡 Rekomendasi

Beberapa rekomendasi yang dapat diterapkan perusahaan antara lain:

- Mendorong pelanggan beralih dari kontrak bulanan ke kontrak tahunan melalui program promosi.
- Meningkatkan adopsi fitur AutoPay dengan pemberian insentif.
- Menjalankan program retensi kepada pelanggan dengan risiko churn tinggi.
- Meminimalkan downtime layanan untuk meningkatkan kepuasan pelanggan.

---

# 📚 Skill yang Ditunjukkan

Melalui proyek ini, beberapa kemampuan yang ditunjukkan meliputi:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Classification
- Hyperparameter Tuning
- Model Evaluation
- Business Insight
- Data Visualization

---

# 📂 Struktur Repository

```
customer-churn-prediction/
│
├── customer_churn_prediction.ipynb
├── broadband_churn_data.csv
└── README.md
```



# 👨‍💻 Author

**Ahmad Miftahul Farohi**

[linkedin.com/in/ahmad-miftahul-farohi](https://www.linkedin.com/in/ahmad-miftahul-farohi/)
