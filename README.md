# 🌦️ Multioutput Weather Forecasting

Proyek ini mengembangkan model **Deep Learning hybrid GRU-LSTM** untuk **memprediksi beberapa variabel cuaca sekaligus (multioutput)** yakni suhu minimum, suhu maksimum, curah hujan, dan kecepatan angin. Proyek ini menggunakan data cuaca dari **Stasiun Klimatologi Jawa Barat (BMKG)** untuk mendukung analisis dan peringatan dini cuaca ekstrem.

---

## 📘 Deskripsi Proyek

Proyek ini bertujuan untuk meningkatkan akurasi prediksi cuaca masing masing variabel menggunakan pendekatan **hybrid GRU-LSTM**, yang menggabungkan keunggulan:
- **GRU (Gated Recurrent Unit)** dalam akurasi yang tinggi.
- **LSTM (Long Short-Term Memory)** dalam menangkap pola jangka panjang pada data deret waktu (time series).

Model ini dibandingkan dengan model GRU tunggal dan LSTM tunggal untuk melihat performa terbaik berdasarkan metrik evaluasi seperti **MAE**, **RMSE**, dan **R² Score**.

---

## ⚙️ Fitur

- Prediksi multioutput (suhu minimum, suhu maksimum, curah hujan, kecepatan angin).  
- Eksperimen perbandingan performa antara model GRU, LSTM, dan GRU-LSTM.  
- Data Preprocessing (Handling Missing Values, handling outlier,EDA, Data Normalization).  
- Visualisasi hasil prediksi melalui dashboard **Looker Studio**.

---

## 🧰 Teknologi yang Digunakan

- Python  
- TensorFlow / Keras  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Looker Studio  

---

## 📂 Struktur Repository
