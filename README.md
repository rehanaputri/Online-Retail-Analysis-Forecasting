# Online-Retail-Analysis-Forecasting
	Analisis data transaksi online retail, RFM segmentation, dan perbandingan forecasting (ARIMA vs Prophet)

# 1. Judul Proyek : 
	Analisis dan Prediksi Penjualan Online Retail untuk Optimalisasi Strategi Bisnis


# 2. Deskripsi Singkat : 
	Proyek ini bertujuan untuk menganalisis data transaksi penjualan dari sebuah toko ritel online berbasis Inggris yang beroperasi antara tahun 2010–2011. Analisis dilakukan untuk memahami pola perilaku pelanggan, tren penjualan produk, serta melakukan peramalan (forecasting) pendapatan masa depan guna mendukung pengambilan keputusan bisnis yang lebih strategis.


# 3. Rumusan Masalah : 
	• Bagaimana pola penjualan dan perilaku pelanggan dalam dataset Online Retail selama periode observasi?
	• Produk apa yang memiliki kontribusi penjualan tertinggi, dan negara mana yang paling dominan dalam transaksi?
	• Siapa pelanggan yang paling bernilai (loyal dan berkontribusi besar terhadap revenue)?
	• Bagaimana tren pendapatan per bulan, dan bagaimana perkiraan pendapatan untuk periode mendatang (forecasting)?


# 4. Tujuan Proyek : 
	• Mengidentifikasi tren dan pola penjualan produk dari data historis.
	• Menemukan pelanggan dengan kontribusi terbesar terhadap revenue perusahaan.
	• Mengetahui faktor-faktor yang memengaruhi performa penjualan.
	• Melakukan forecasting pendapatan masa depan berdasarkan tren historis untuk mendukung strategi bisnis.


# 5. Dataset : 
	Sumber: [Online Retail Dataset - UCI Machine Learning Repository / Kaggle]
	File: Online Retail.xlsx
	Deskripsi Kolom Utama:
	Kolom	Deskripsi
	InvoiceNo	Nomor faktur transaksi
	StockCode	Kode produk
	Description	Deskripsi produk
	Quantity	Jumlah unit yang dibeli
	InvoiceDate	Tanggal dan waktu transaksi
	UnitPrice	Harga per unit produk
	CustomerID	ID pelanggan
	Country	Negara asal pelanggan

## Alasan Pemilihan Dataset:
		• Dataset ini nyata dan populer di dunia analisis bisnis, sering digunakan untuk studi kasus customer segmentation, sales analysis, hingga revenue forecasting.
		• Data transaksi ritel mencerminkan permasalahan umum dalam dunia kerja sebagai Business Analyst dan Data Analyst: analisis tren, perilaku pelanggan, dan prediksi pendapatan.
		• Format dataset (transaksi individual) sangat cocok untuk menunjukkan kemampuan analisis data lengkap — dari data wrangling hingga predictive modeling.


# 6. Langkah Analisis (Metodologi) : 
	Tahap	Jenis Analisis	: 
		1️⃣ Descriptive Analysis	Analisis tren penjualan berdasarkan waktu, negara, dan produk. Menentukan top-selling products dan top customers.	
		2️⃣ Diagnostic Analysis	Mengidentifikasi penyebab naik turunnya revenue, serta analisis kontribusi pelanggan dan negara terhadap total penjualan.	
		3️⃣ Predictive Analysis (Forecasting)	Membangun model peramalan (contoh: ARIMA, Prophet, atau LSTM) untuk memprediksi revenue bulanan di masa depan.	


# 7. Tools & Libraries : 
	• Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
	• Jupyter Notebook – untuk eksplorasi & analisis data
	• Power BI / Tableau / Streamlit – untuk visualisasi dashboard interaktif
	• Statsmodels / Prophet – untuk forecasting


# 8. Output yang Diharapkan
	• Dashboard Interaktif menampilkan:
		• Tren penjualan per bulan
		• Top produk dan pelanggan
		• Analisis negara penyumbang revenue terbanyak
	• Laporan Analisis Bisnis berisi insight penting dan rekomendasi
	• Model Forecasting untuk memprediksi revenue 3–6 bulan ke depan



<img width="1136" height="2371" alt="image" src="https://github.com/user-attachments/assets/a29f386c-0d10-44ed-ae76-7ef0b39a102f" />
