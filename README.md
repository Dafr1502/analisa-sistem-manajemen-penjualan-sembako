# 🛒 Analisa Sistem Manajemen Penjualan Sembako

Sembako sales management system analysis using Microsoft Excel. Features data cleaning, automated formulas (VLOOKUP, IF/IFS), Pivot Tables, and an interactive sales dashboard.

![Dashboard Penjualan Sembako](Screenshot%202026-08-17%20231747.png)

---

## 📌 Project Overview
Sistem pelaporan penjualan sembako otomatis menggunakan **Microsoft Excel** sebagai bagian dari *Intensive Bootcamp KarirNex*. Proyek ini berfokus pada pengolahan data transaksi penjualan, pembersihan data (*data cleaning*), otomatisasi kalkulasi harga dan diskon, serta pembuatan dashboard interaktif untuk mendukung analisis kinerja bisnis secara *real-time*.

## 🛠️ Tools & Formula Used
* **Data Cleaning & Transformation:** Memperbaiki format tanggal (*date formatting*) dan menghapus data duplikat (*remove duplicates*).
* **Excel Lookup & Formulas:**
  * `VLOOKUP` & Logika `IF` / `IFS`: Untuk pengkategorian produk, tingkat diskon, dan klasifikasi rating/pelanggan.
  * **Kalkulasi Otomatis:** Perhitungan *Subtotal*, *Discount Amount*, *Total Sales*, *Shipping Fee*, hingga *Grand Total*.
* **Pivot Tables & Pivot Charts:** Agregasi data penjualan berdasarkan performa produk, platform toko, serta analisis korelasi diskon.
* **Interactive Dashboard:** Slicers interaktif (*City*, *Platform*, *Discount (%)*) & KPI Cards.

---

## 📊 Key Insights & Business Findings

### 1. Performa Penjualan & Produk Teratas
* **Total Omzet & Volume:** Mencatatkan total omzet sebesar **IDR 231.538.050** dari **2.000 total pesanan** dengan rata-rata *Customer Rating* berada di angka **2.98**.
* **Produk Unggulan:** Kategori **Susu Bubuk (Brand C & B)** dan **Daging Ayam (Brand C & B)** menjadi penyumbang total penjualan (*Total Sales*) tertinggi.

### 2. Distribusi Platform Penjualan
* **Pangsa Pasar Platform:** Penjualan terdistribusi secara seimbang antara dua platform utama, yaitu **Toko Ungu (51%)** dan **Toko Orange (49%)**.

### 3. Elastisitas Diskon terhadap Penjualan
* **Tren Rata-rata Penjualan:** Tingkat diskon memberikan pengaruh langsung terhadap rata-rata *Total Sales*, di mana pemberian diskon yang tepat terbukti menjaga stabilitas volume transaksi pelanggan.

---

## ❓ Business Question & Findings Breakdown

| No | Pertanyaan Bisnis | Hasil Analisis |
| :---: | :--- | :--- |
| **1** | Rata-rata *Quantity* untuk kota Bandung | **2.86** |
| **2** | Jumlah *Total Sales* dari pembayaran COD | **IDR 32.878.550** |
| **3** | Jumlah jenis platform yang tersedia | **5 Platform** |
| **4** | Jumlah *Grand Total* transaksi di bulan Agustus 2025 | **IDR 19.728.900** |
| **5** | Brand *Telur Ayam* dengan *Quantity* terbanyak di Surabaya (Toko Biru) | **Telur Ayam - Brand A** |
| **6** | Jumlah *Quantity* yang termasuk kategori *Clearance* | **2** |
| **7** | Jumlah *Grand Total* untuk kategori *Rendah* | **IDR 46.423.250** |
| **8** | Rata-rata *Customer Rating* dari perempuan untuk kategori *Sangat Tinggi* | **3.04** |
| **9** | Bulan & tahun dengan *Quantity* terbanyak dari kategori *Tinggi* | **Agustus 2025** |
| **10** | *Disc Category* dengan transaksi terbanyak dibanding rerata *Grand Total* | **Clearance** |

---

## 💡 Key Recommendations
1. **Fokus Inventaris Produk Utama:** Meningkatkan pasokan stok untuk kategori produk pendorong omzet terbesar seperti *Susu Bubuk* dan *Daging Ayam*.
2. **Optimasi Strategi Diskon:** Mengevaluasi efektivitas skema diskon *Clearance* agar tingkat profitabilitas tetap terjaga seiring peningkatan volume penjualan.
3. **Peningkatan Layanan Pelanggan:** Melakukan evaluasi terhadap kepuasan pelanggan guna meningkatkan rata-rata *Customer Rating* yang saat ini berada di angka **2.98**.
