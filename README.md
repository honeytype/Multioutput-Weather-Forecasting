# 🌦️ Multioutput Weather Forecasting using Hybrid Model for Extreme Weather Prediction
Proyek ini mengembangkan model **Deep Learning hybrid GRU-LSTM** untuk **memprediksi beberapa variabel cuaca secara multioutput**, yaitu suhu minimum, suhu maksimum, curah hujan, dan kecepatan angin.  
Dataset yang digunakan merupakan data cuaca harian dari **Stasiun Klimatologi BMKG Jawa Barat (Bogor)** untuk mendukung analisis dan peringatan dini cuaca ekstrem.

---
## 📘 Deskripsi Proyek

Proyek ini bertujuan untuk meningkatkan akurasi peramalan cuaca pada setiap variabel menggunakan pendekatan **hybrid GRU-LSTM**, yang menggabungkan keunggulan:
- **GRU (Gated Recurrent Unit)** dalam menghasilkan prediksi yang efisien dan akurat.  
- **LSTM (Long Short-Term Memory)** dalam menangkap pola jangka panjang pada data deret waktu (*time series*).  

Model ini dibandingkan dengan model **GRU tunggal** dan **LSTM tunggal** untuk memperoleh performa terbaik berdasarkan metrik evaluasi seperti **MAE**, **RMSE**, dan **R² Score**.

---
## 🚀 Cara Menjalankan
1. Buka **[Google Colab](https://colab.research.google.com/)**.  
2. Unggah salah satu file notebook:  
   - `GRU.ipynb`  
   - `LSTM.ipynb`  
   - `GRULSTM.ipynb`  
3. Unggah juga file dataset `Dataset.csv` ke sesi Colab.  
   - Caranya: klik **📁 Files** → **Upload** → pilih file dataset.  
4. Jalankan setiap cell dari atas ke bawah dengan klik ▶️ di sisi kiri cell.  
5. Tunggu hingga proses training selesai, lalu lihat hasil visualisasi dan evaluasi model di bagian akhir notebook.

---

## 📊 Visualisasi Hasil
Visualisasi hasil prediksi dapat diakses melalui dashboard interaktif berikut:  
👉 [**Weather Forecasting Dashboard**](https://lookerstudio.google.com/reporting/f0ae3f6c-a580-47b8-a0f1-d904fef3b061)

Dashboard ini menampilkan perbandingan hasil prediksi terhadap data aktual serta performa dari masing-masing model.
