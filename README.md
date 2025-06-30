
# 📊 Capstone Project Module 2 – Customer Segmentation Analysis

## 📝 Project Title
**Customer Segmentation and Marketing Strategy for a Supermarket Retail Business**

## 👤 Author
Sarah Agnisa

## 📁 File
`capstone_module2_sarahagnisa.ipynb`

---

## 🔍 Project Overview

Proyek ini bertujuan untuk memahami perilaku pelanggan supermarket melalui analisis data dan memberikan insight strategis yang dapat digunakan untuk meningkatkan efektivitas kampanye pemasaran, meningkatkan loyalitas pelanggan, serta meningkatkan total penjualan.

Pendekatan utama yang digunakan adalah Exploratory Data Analysis (EDA), segmentasi pelanggan, analisis korelasi, serta pembuatan visualisasi untuk mendukung pengambilan keputusan berbasis data.

---

## 🎯 Objectives

- Melakukan eksplorasi data demografis, pengeluaran, dan perilaku belanja pelanggan.
- Menilai efektivitas masing-masing kampanye pemasaran.
- Mengidentifikasi segmen pelanggan potensial.
- Mengusulkan strategi bisnis berbasis hasil analisis dan segmentasi.
- Menyediakan visualisasi data yang informatif untuk mendukung insight yang ditemukan.

---

## 🧾 Dataset Description

Dataset berisi informasi 2240 pelanggan supermarket dengan berbagai atribut, termasuk:

### 🎓 Demografi
- `Age`, `Education`, `Marital_Status`, `Income`, `Kidhome`, `Teenhome`, `Dt_Customer`

### 💳 Pembelian
- `MntWines`, `MntMeatProducts`, `MntFruits`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`

### 🛒 Perilaku Belanja
- `NumDealsPurchases`, `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`, `NumWebVisitsMonth`

### 📢 Respons Kampanye
- `AcceptedCmp1` sampai `AcceptedCmp5`, `Response`

---

## 🧪 Tools & Technologies

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scipy (Pearson correlation, hypothesis testing)
- Tableau (untuk visualisasi lanjutan)

---

## 🧹 Data Preparation

- Konversi kolom tanggal (`Dt_Customer`) menjadi tipe `datetime`.
- Pembuatan fitur baru seperti `Total Spending`, `Total Purchases`, `Total_Kampanye_Respon`.
- Transformasi data menggunakan `.melt()` dan `.groupby()` untuk memudahkan visualisasi.
- Penanganan missing value, pengecekan duplikasi.

---

## 📊 Key Analysis & Insights

### 1. Demografi & Spending
- Pelanggan tanpa anak cenderung memiliki pengeluaran lebih tinggi.
- Education level berpengaruh terhadap pola pengeluaran, pelanggan berpendidikan tinggi memiliki spending lebih besar.

### 2. Campaign Response
- Kampanye terakhir (`Response`) mendapatkan respons paling tinggi.
- Kampanye ke-1 dan ke-2 tidak efektif, perlu direview atau dihentikan.

### 3. Produk
- Wine dan Meat adalah produk dengan pengeluaran terbesar.
- Fruits dan Fish menunjukkan potensi pertumbuhan melalui diskon/edukasi.

### 4. Korelasi
- Korelasi positif antara `Income` dan `Total Spending`, terutama untuk segmen tertentu (dilihat berdasarkan `Education`).
- Analisis Pearson digunakan untuk mengukur kekuatan hubungan antar variabel numerik.

---

## 📈 Visualization Examples

- Barplot pengeluaran berdasarkan `Education` dan `Product Type`.
- Scatterplot hubungan `Income` vs `Total Spending` dengan hue `Education`.
- Heatmap korelasi antar variabel numerik.
- Barplot respons kampanye per kategori.

---

## 🧠 Business Recommendations

- Fokus kampanye pada segmen tanpa anak dan berpendidikan tinggi.
- Optimalkan channel pembelian online dan offline berdasarkan frekuensi transaksi.
- Replikasi format kampanye terakhir yang paling sukses.
- Bundling produk premium untuk meningkatkan nilai transaksi.
- Evaluasi dan segmentasi pelanggan berdasarkan jumlah kampanye yang mereka respon.

---

## 🚀 How to Run

1. Install semua dependensi:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```

2. Jalankan Jupyter Notebook:
   - Buka `capstone_module2_sarahagnisa.ipynb`
   - Jalankan setiap cell dari atas ke bawah secara berurutan

---

## 📊 Tableau Dashboard (Optional)

Dashboard visualisasi lanjutan dapat dilihat menggunakan Tableau Public/Desktop. Disarankan untuk:
- Menganalisis top 10 spender
- Respons kampanye berdasarkan kategori
- Perbandingan pengeluaran per channel atau produk

---

## 📌 Project Limitations

- Dataset adalah data simulasi, bukan real customer data.
- Insight bersifat deskriptif, belum termasuk Machine Learning segmentation atau clustering.

---

## 📝 License

Proyek ini untuk keperluan pembelajaran. Data tidak digunakan untuk kepentingan komersial.

---

## 📬 Contact

📧 sarahagnisa@email.com  
🔗 [LinkedIn](https://linkedin.com/in/sarahagnisa)

---
