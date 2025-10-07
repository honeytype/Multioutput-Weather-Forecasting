# 🌦️ Multioutput Weather Forecasting

Proyek ini mengembangkan model **Deep Learning hybrid GRU-LSTM** untuk **memprediksi beberapa variabel cuaca secara multioutput** yakni suhu minimum, suhu maksimum, curah hujan, dan kecepatan angin. Dataset yang digunakan merupakan data cuaca harian dari **Stasiun Klimatologi Jawa Barat (BMKG) Bogor ** untuk mendukung analisis dan peringatan dini cuaca ekstrem.

---

## 📘 Deskripsi Proyek

Proyek ini bertujuan untuk meningkatkan akurasi peramalan cuaca tiap variabel menggunakan pendekatan **hybrid GRU-LSTM**, yang menggabungkan keunggulan:
- **GRU (Gated Recurrent Unit)** untuk memperoleh akurasi yang tinggi.
- **LSTM (Long Short-Term Memory)** untuk menangkap pola jangka panjang pada data deret waktu (time series).

Model ini akan dibandingkan dengan model GRU tunggal dan LSTM tunggal untuk melihat performa terbaik berdasarkan metrik evaluasi seperti **MAE**, **RMSE**, dan **R² Score**.

---

## ⚙️ Fitur

- Prediksi multioutput (suhu minimum, suhu maksimum, curah hujan, kecepatan angin).  
- Eksperimen perbandingan performa antara model GRU, LSTM, dan GRU-LSTM.  
- Data Preprocessing (Handling Missing Values, handling outlier,EDA, Data Normalization).  
- Visualisasi hasil prediksi melalui dashboard **Looker Studio**.

---

## 🚀 Cara Menjalankan Proyek

1. Buka **[Google Colab](https://colab.research.google.com/)**.  
2. Unggah salah satu file notebook (`GRU.ipynb`, `LSTM.ipynb`, atau `GRULSTM.ipynb`).  
3. Unggah juga file dataset `Dataset.csv` ke sesi Colab.  
   - Caranya: klik **📁 (Files)** → **Upload** → pilih file dataset.  
4. Jalankan setiap cell dari atas ke bawah dengan klik ▶️ di sisi kiri cell.  
5. Tunggu hingga proses training selesai, lalu lihat hasil visualisasi dan evaluasi model di bagian akhir notebook.

💡 **Tips:**  
Jika dataset berada di Google Drive, kamu bisa menautkannya langsung menggunakan kode berikut di Colab:
```python
from google.colab import drive
drive.mount('/content/drive')

## 📊 Visualisasi Hasil

Visualisasi hasil prediksi dapat diakses melalui dashboard interaktif berikut:
👉 Weather Forecasting Dashboard (Looker Studio)

Dashboard ini menampilkan perbandingan hasil prediksi terhadap data aktual serta performa dari masing-masing model.
