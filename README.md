# 🎄📊 Christmas Sales Insights  

Repositori ini berisi analisis data penjualan periode Natal yang bersumber dari dataset publik di **Kaggle**. Analisis dilakukan untuk mengeksplorasi tren penjualan, perilaku konsumen, serta kinerja operasional dalam konteks simulasi bisnis. Meskipun bukan data riil perusahaan, proyek ini dirancang untuk memberikan gambaran komprehensif terkait pemanfaatan data dalam pengambilan keputusan strategis.  

---

## 🎯 Tujuan  
1. Sebagai arsip dan portofolio pribadi dalam menerapkan konsep-konsep analisis data bisnis.  
2. Memberikan contoh praktis penerapan metode analisis data untuk menghasilkan insight yang relevan.  

---

## 📂 Struktur Proyek  
```
│
├── Data/
│ └── Christmas_Sales.csv  # Dataset utama yang digunakan
│
└── Notebooks/
  ├── 01_Sales_Performance_&Customer_Behavior.ipynb
  ├── 02_Payment_Method_Trends_and_Preferences.ipynb
  ├── 03_Shipping&Delivery_Performance.ipynb
  ├── 04_Transaction_Return_Patterns.ipynb
  └── 05_GiftWrap_Usage&_Customer_Insights.ipynb
```
---

## 📊 Cakupan Analisis  

Proyek ini mencakup lima area utama analisis:  

- **Sales Performance Analysis and Customer Behavior**  
  Mengevaluasi tren penjualan dari waktu ke waktu, kontribusi per kategori, kanal, dan wilayah, serta mengidentifikasi perilaku konsumen melalui segmentasi demografi, preferensi produk, hingga metode pembayaran yang digunakan.  

- **Payment Method Trends and Preferences**  
  Memetakan tren penggunaan metode pembayaran, baik dari sisi volume maupun nilai transaksi, serta mengukur kepuasan pelanggan terhadap tiap metode pembayaran.  

- **Shipping & Delivery Performance**  
  Berfokus pada evaluasi efektivitas pengiriman, membandingkan metode pengiriman, serta melihat pengaruh faktor eksternal seperti cuaca dan event khusus terhadap lead time dan kinerja distribusi.  

- **Transaction Return Patterns**  
  Mengkaji pola retur transaksi berdasarkan kanal, kategori produk, demografi pelanggan, serta metode pembayaran dan pengiriman, untuk mengidentifikasi area dengan tingkat retur tinggi.  

- **GiftWrap Usage & Customer Insights**  
  Menyoroti pola penggunaan layanan gift wrap, termasuk pengaruh momen khusus, promo, dan preferensi demografi pelanggan, serta distribusinya berdasarkan kategori produk dan lokasi.  
 

---

## 📋 Dataset  

Dataset bersumber dari Kaggle: [Christmas Sales and Trends](https://www.kaggle.com/datasets/ibikunlegabriel/christmas-sales-and-trends)\
Data ini merepresentasikan penjualan toko pada periode musim Natal (November–Desember) dari tahun 2018 hingga 2023 
- Ukuran Data: 10.000 baris, 24 kolom  
- Karakteristik Data: berisi transaksi penjualan periode Natal, mencakup informasi produk, pelanggan, pengiriman, dan metode pembayaran.  
- Struktur Kolom:
  - Data Transaksi Penjualan (`TransactionID`, `Date`, `Quantity`, `TotalPrice`, `UnitPrice`, `Discount`, `Profit`, `ReturnFlag`)
  - Informasi Produk dan Kategorisasi (`ProductID`, `ProductName`, `Category`, `SubCategory`, `Brand`)
  - Informasi Pelanggan (`CustomerID`, `Gender`, `Age`, `AgeSegment`, `Location`)
  - Pengiriman dan Logistik (`Channel`, `ShippingMethod`, `DeliveryTime`, `Region`)  
  - Metode Pembayaran dan Layanan Tambahan ( `PaymentMethod`, `GiftWrap`)

---

## 🔧 Teknologi dan Tools  
- Bahasa Pemrograman: `Python`  
- Analisis Data: `Pandas`, `NumPy`  
- Visualisasi: `Matplotlib`, `Seaborn`  
- Lingkungan: `Jupyter Notebook`  

---
 
