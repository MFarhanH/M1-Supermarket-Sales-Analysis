# Judul Project

Supermarket Sales Analysis

## Repository Outline

```
M1-Supermarket-Sales-Analysis/
├── P0M1_MuhammadFarhan_Hendriyanto.ipynb
├── P0M1_MuhammadFarhan_Hendriyanto_dataset.csv
├── P0M1_MuhammadFarhan_Hendriyanto_dataset.xlsx
├── supermarket_sales - Sheet1.csv
├── Data Supermart Clean.xlsx
└── README.md - Penjelasan gambaran umum project
```

## Problem Background

Dalam dunia ritel modern, pengambilan keputusan terhadap suatu bisnis sangat berpengaruh besar dengan impact yang akan terjadi pada perkembangan bisnis tersebut. Dalam mengambil keputusan bisnis tidak bisa hanya dengan mengandalkan intuisi ataupun feeling saja, tetapi juga harus didasari oleh data, informasi dan analisis yang tajam serta akurat. Supermarket merupakan salah satu ritel yang dinamis, menghadapi tantangan dalam memahami perilaku konsumen, mengelola peforma penjualan, dan mengoptimalkan strategi pemasaran. Pada analisis kali ini, terdapat seorang client yang merupakan manager sales & marketing dari supermarket yang memiliki jaringan yang cukup besar. Beliau ingin melihat bagaimana pola penjualan, trend, dan performa tiap cabang yang ada pada perusahaanya tersebut. Tujuannya agar beliau bisa meningkatkan penjualan penjualan keseluruhan tiap cabangnya sebesar 15% dari penjualan sebelumnya dalam kurun waktu 1 bulan setelah penjualan terakhir, agar bisa melakukan ekspansi cabang secara strategis. Perusahaannya sudah menerapkan digitalisasi data dari transaksinya, namun sampai saat ini masih belum ada analisis mendalam yang menjawab pertanyaan penting seperti berikut: 

- Kapan waktu tertinggi dan terendah total penjualan terjadi? 

- Bagaimana persebaran gender customer yang sudah menjadi member? 

- Kategori produk apa yang paling banyak terjual? 

- Kota mana yang memiliki performa penjualan terbaik? 

- Cabang mana yang mempunyai penjualan terendah? 

- Apakah gender mempengaruhi penjualan?

## Project Output
Output dari project ini adalah Membuat dasbor penjualan dari supermarket store berdasarkan problem statement yang telah dibuat.

## Data

Link data: https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales

Data terdiri dari beberapa kolom dengan nama sebagai berikut:

- Branch: Lokasi cabang supermarket (misalnya, Yangon, Naypyitaw, Mandalay).
- City: Kota tempat cabang supermarket berada.
- Customer Type: Menunjukkan apakah pelanggan merupakan 'Member' (anggota) atau 'Normal' (biasa).
- Gender: Jenis kelamin pelanggan.
- Product Line: Kategori produk yang dijual (misalnya, Kesehatan & Kecantikan, Aksesori Elektronik, Rumah & Gaya Hidup).
- Unit Price: Harga per unit produk.
- Quantity: Jumlah barang yang dibeli.
- Tax 5%: Jumlah pajak yang dikenakan pada transaksi dengan tarif 5%.
- Total: Total jumlah transaksi termasuk pajak.
- Date: Tanggal transaksi.
- Time: Waktu transaksi.
- Payment: Metode pembayaran yang digunakan (misalnya, Tunai, Dompet Digital, Kartu Kredit).
- COGS: Biaya pokok penjualan, yaitu biaya dasar dari produk yang dijual.
- Gross Margin Percentage: Persentase keuntungan tetap dari setiap penjualan (4,7619%).
- Gross Income: Keuntungan yang diperoleh dari transaksi.
- Rating: Penilaian kepuasan pelanggan (skala 1 sampai 10).

  # Column Non-Null Count Dtype

  ```
  <class 'pandas.core.frame.DataFrame'>
  RangeIndex: 1002 entries, 0 to 1001
  Data columns (total 17 columns):
  #   Column                   Non-Null Count  Dtype  
  ---  ------                   --------------  -----  
  0   Invoice ID               1002 non-null   object 
  1   Branch                   1002 non-null   object 
  2   City                     1001 non-null   object 
  3   Customer type            1001 non-null   object 
  4   Gender                   1002 non-null   object 
  5   Product line             1002 non-null   object 
  6   Unit price               1001 non-null   float64
  7   Quantity                 1002 non-null   int64  
  8   Tax 5%                   1001 non-null   float64
  9   Total                    1002 non-null   object 
  10  Date                     1002 non-null   object 
  11  Time                     1002 non-null   object 
  12  Payment                  1002 non-null   object 
  13  cogs                     1001 non-null   float64
  14  gross margin percentage  1001 non-null   object 
  15  gross income             1001 non-null   float64
  16  Rating                   1001 non-null   float64
  dtypes: float64(5), int64(1), object(11)
  memory usage: 133.2+ KB
  ```

## Method

Metode yang dipakai adalah analisis deskriptif dan analisis inferensial

## Stacks

- Bahasa pemrograman: 
  - Python
- Tools: 
  - VsCode
  - Tableau
- Library: 
  - Pandas 
  - Plotly Express 
  - Matplotlib
  - Scipy

## Reference

Link Dashboard: https://public.tableau.com/views/P0M1_MuhammadFarhanHendriyanto/MainDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---
