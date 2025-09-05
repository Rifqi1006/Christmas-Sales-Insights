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

Proyek ini mencakup enam area utama analisis:  

1. **Sales Performance Analysis & Customer Behavior**  
   - Tren penjualan bulanan dan tahunan  
   - Total penjualan per kategori produk  
   - Perbandingan kanal penjualan: Online vs Offline  
   - Evolusi penjualan Online vs Offline per kategori produk  
   - Pola penjualan musiman per kategori produk  
   - Distribusi penjualan berdasarkan Store ID  
   - Kontribusi penjualan berdasarkan kategori produk dan wilayah  
   - Dampak event khusus terhadap penjualan  
   - Incremental sales akibat promosi  

2. **Market & Consumer Analysis**  
   - Segmentasi pelanggan (usia, gender, wilayah)  
   - Preferensi produk berdasarkan kategori usia  
   - Rata-rata pembelian berdasarkan kategori usia  
   - Metode pembayaran populer berdasarkan kategori usia  

3. **Shipping & Delivery Performance**  
   - Analisis kinerja pengiriman keseluruhan  
   - Analisis kinerja berdasarkan metode pengiriman  
   - Analisis dampak cuaca pada pengiriman  
   - Analisis dampak event pada pengiriman  
   - Analisis tren lead time dari waktu ke waktu  

4. **Payment Method Trends and Preferences**  
   - Persentase penggunaan tiap metode pembayaran  
   - Nilai transaksi per metode pembayaran  
   - Tren frekuensi per metode pembayaran (tahunan)  
   - Tren nilai transaksi per metode pembayaran (tahunan)  
   - Rata-rata customer satisfaction per metode pembayaran  

5. **GiftWrap Usage & Customer Insights**  
   - Persentase transaksi dengan gift wrap vs tanpa gift wrap  
   - Tren penggunaan gift wrap berdasarkan channel penjualan  
   - Persentase penggunaan gift wrap pada momen khusus  
   - Persentase penggunaan gift wrap saat ada promo atau diskon  
   - Segmen usia dan gender pengguna gift wrap  
   - Tingkat penggunaan gift wrap berdasarkan lokasi pelanggan  
   - Tingkat penggunaan gift wrap berdasarkan Store ID  
   - Persentase penggunaan gift wrap berdasarkan kategori produk  

6. **Transaction Return Patterns**  
   - Perbandingan transaksi berhasil vs return  
   - Performa retur berdasarkan channel penjualan  
   - Persentase retur berdasarkan kategori produk  
   - Persentase retur berdasarkan segmen usia dan gender  
   - Tingkat retur pembelian berdasarkan lokasi  
   - Tingkat retur pembelian berdasarkan Store ID  
   - Persentase retur berdasarkan metode pembayaran  
   - Persentase retur berdasarkan waktu dan metode pengiriman  

---

## 📋 Dataset  

Dataset bersumber dari Kaggle: [Christmas Sales and Trends](https://www.kaggle.com/datasets/ibikunlegabriel/christmas-sales-and-trends)  
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
 
