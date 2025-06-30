# Capstone2
Purwadhika_Capstone2

# 📊 Capstone Project Module 2 – Customer Segmentation Analysis

## 📝 Project Title
**Customer Segmentation and Marketing Strategy for a Supermarket Retail Business**

## 👤 Author
Sarah Agnisa

## 📁 File
`capstone_module2_sarahagnisa.ipynb`

---

## 📌 Project Overview

Proyek ini bertujuan untuk melakukan analisis eksploratif dan segmentasi pelanggan dari sebuah supermarket besar berdasarkan data transaksi dan karakteristik pelanggan. Hasil analisis digunakan untuk merumuskan **strategi pemasaran yang lebih efektif dan personalisasi produk** berdasarkan perilaku dan demografi pelanggan.

---

## 🧠 Key Objectives

- Menganalisis pola pengeluaran dan pendapatan pelanggan.
- Menentukan hubungan antara karakteristik pelanggan (usia, pendidikan, jumlah anak) dengan perilaku belanja.
- Mengevaluasi efektivitas kampanye pemasaran sebelumnya.
- Memberikan rekomendasi strategis berbasis data untuk meningkatkan loyalitas dan penjualan.

---

## 📚 Dataset Description

Dataset yang digunakan berisi informasi pelanggan dengan fitur-fitur seperti:
- Demografi: `Age`, `Education`, `Marital_Status`, `Income`, `Children`
- Pembelian: `MntWines`, `MntMeatProducts`, `MntGoldProds`, dll.
- Respons terhadap kampanye: `AcceptedCmp1–5`, `Response`
- Channel pembelian: `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`

Sumber: Simulasi data retail (tidak sensitif atau asli).

---

## 🔧 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats` (untuk korelasi & uji statistik)
- `datetime`

---

## 📈 Analysis Sections

1. **Data Cleaning & Preprocessing**  
   - Konversi tanggal, pengecekan missing value, dan pembentukan kolom baru.

2. **Exploratory Data Analysis (EDA)**  
   - Distribusi demografi dan pengeluaran.
   - Korelasi antara `Income`, `Total Spending`, dan `Education`.
   - Analisis channel dan jenis produk.

3. **Campaign Response Analysis**  
   - Performa masing-masing kampanye (`Cmp1–5`, `Response`)
   - Segmentasi berdasarkan jumlah kampanye yang direspon.

4. **Customer Segmentation & Strategic Insight**  
   - Insight berdasarkan jumlah anak, jenis produk, channel, dan education.
   - Rekomendasi bisnis berbasis data.

---

## 📊 Key Visualizations

- Barplot pengeluaran berdasarkan produk dan pendidikan.
- Scatterplot hubungan `Income` dan `Total Spending`.
- Korelasi Pearson antar variabel numerik.
- Barplot respons terhadap masing-masing kampanye.

---

## ✅ Business Recommendations

- Fokus pada segmen pelanggan berpendidikan tinggi dan tanpa anak.
- Replikasi elemen kampanye yang sukses.
- Promosi bundling produk premium (wine, meat, gold).
- Personalization campaign berbasis response history.

---

## 🚀 How to Run

1. Pastikan semua library terinstall:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
