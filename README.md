# Adidas US Sales Performance Dashboard

## Project Overview
Dashboard ini dibuat untuk menganalisis performa penjualan Adidas di United States berdasarkan revenue, profit, units sold, operating margin, region, product, retailer, dan sales method.

## Business Objective
Tujuan dari project ini adalah:
- Menganalisis performa penjualan Adidas berdasarkan wilayah, produk, dan retailer
- Mengidentifikasi produk dan retailer dengan kontribusi penjualan tertinggi
- Melihat tren penjualan dari waktu ke waktu
- Memberikan rekomendasi bisnis berdasarkan insight dari dashboard

## Dataset
Dataset yang digunakan berisi data penjualan Adidas di United States, mencakup informasi transaksi, lokasi, produk, retailer, metode penjualan, jumlah unit terjual, total sales, operating profit, dan operating margin.

## Data Dictionary

| Column Name | Description | Data Type |
|---|---|---|
| Retailer | Nama retailer yang menjual produk Adidas | Text |
| Retailer ID | ID unik untuk retailer | Number/Text |
| Invoice Date | Tanggal transaksi penjualan | Date |
| Region | Wilayah penjualan di United States | Text |
| State | Negara bagian tempat transaksi terjadi | Text |
| City | Kota tempat transaksi terjadi | Text |
| Product | Jenis produk Adidas yang dijual | Text |
| Price per Unit | Harga per unit produk | Currency |
| Units Sold | Jumlah unit produk yang terjual | Number |
| Total Sales | Total pendapatan dari transaksi | Currency |
| Operating Profit | Profit operasional dari transaksi | Currency |
| Operating Margin | Persentase margin operasional | Percentage |
| Sales Method | Metode/channel penjualan, seperti Online, Outlet, atau In-store | Text |

## Key Metrics

| Metric | Formula | Description |
|---|---|---|
| Total Revenue | SUM(Total Sales) | Total pendapatan dari seluruh transaksi |
| Total Units Sold | SUM(Units Sold) | Total produk yang terjual |
| Total Profit | SUM(Operating Profit) | Total profit operasional |
| Average Operating Margin | AVG(Operating Margin) | Rata-rata margin operasional |

## Tools Used
- Tableau
- Excel / CSV
- Data Visualization
- Business Intelligence

## Dashboard Preview

![Dashboard Preview](images/dashboard-preview.png)

## Dashboard Features
Dashboard ini terdiri dari beberapa visualisasi utama:
- KPI cards untuk Total Revenue, Total Units Sold, Total Profit, dan Average Operating Margin
- Sales trend berdasarkan waktu
- Distribusi penjualan berdasarkan state dan region
- Analisis penjualan berdasarkan produk
- Analisis penjualan berdasarkan retailer

## Key Insights

- Dashboard menunjukkan performa penjualan Adidas yang kuat dengan total revenue sebesar $899.9M, total profit $332.1M, dan average operating margin 42.30%.
- Produk kategori footwear menjadi salah satu kontributor utama terhadap total penjualan, menunjukkan tingginya permintaan pada kategori tersebut.
- Retailer utama seperti West Gear, Foot Locker, dan Sports Direct memiliki kontribusi penjualan terbesar dibandingkan retailer lainnya.

## Business Recommendations
- Fokuskan strategi penjualan dan promosi pada produk dengan performa terbaik untuk meningkatkan pendapatan secara berkelanjutan.
- Perkuat kerja sama dengan retailer yang memiliki kontribusi penjualan tinggi agar distribusi dan campaign lebih efektif.
- Lakukan evaluasi terhadap region, state, atau retailer dengan performa rendah untuk menemukan peluang peningkatan penjualan.
