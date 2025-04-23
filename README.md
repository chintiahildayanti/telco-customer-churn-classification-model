# Analisis Churn Pelanggan Telco 📊

🎯 Objective
Tujuan dari proyek ini adalah untuk membangun model klasifikasi menggunakan algoritma machine learning yang mampu memprediksi kemungkinan seorang pelanggan Telco melakukan churn (berhenti berlangganan). Dengan mengetahui pelanggan yang berpotensi churn, perusahaan dapat mengambil tindakan proaktif untuk mempertahankan pelanggan tersebut.

Secara khusus, proyek ini bertujuan untuk:
- Melakukan eksplorasi data untuk memahami pola perilaku pelanggan.
- Mempersiapkan data agar siap digunakan dalam pemodelan.
- Menerapkan berbagai algoritma supervised learning seperti Decision Tree dan Random Forest.
- Mengevaluasi performa model menggunakan metrik klasifikasi seperti akurasi, precision, recall, dan f1-score.
- Mengidentifikasi model terbaik untuk memprediksi churn pelanggan secara akurat.

## 🧾 Dataset

Dataset berisi informasi demografis, detail akun, dan penggunaan layanan dari pelanggan Telco. Variabel target adalah `Churn`.

### Contoh fitur:
- Demografi pelanggan (gender, senior citizen, pasangan)
- Langganan layanan (layanan internet, streaming, dll.)
- Detail akun (tipe kontrak, metode pembayaran, biaya bulanan)

## 🔧 Langkah-langkah Analisis

1. **Import Library** – Menggunakan pustaka seperti pandas, seaborn, sklearn, dll.
2. **Membaca Dataset** – Membaca data ke dalam DataFrame.
3. **Exploratory Data Analysis (EDA)** – Visualisasi
4. **Pra-pemrosesan Data** – Menangani data kosong, mengecek data duplikat, memilih feature, encoding variabel kategorik, split dataset, smote oversampling.
5. **Pembangunan Model** – Menggunakan algoritma klasifikasi seperti:
   - Decision Tree
   - Random Forest
6. **Evaluasi Model** – Menggunakan metrik:
   - Akurasi
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

## 📈 Hasil

Perbandingan performa model untuk menentukan algoritma terbaik dalam memprediksi churn pelanggan.

## ✅ Kesimpulan

Model machine learning mampu membantu perusahaan Telco mengidentifikasi pelanggan yang berpotensi churn sehingga dapat dilakukan tindakan retensi lebih dini.
dan model Random Forest menjadi model dengan performa terbaik untuk data ini.

## 🚀 Cara Menjalankan

1. Unduh notebook atau clone repositori ini.
2. Buka file `.ipynb` menggunakan Jupyter Notebook atau Google Colab.
3. Jalankan seluruh sel untuk melihat proses analisis dan hasil modeling.
