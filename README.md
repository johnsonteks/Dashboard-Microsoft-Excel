# 📊 Interactive Excel Dashboard Portfolio

Koleksi proyek dashboard interaktif berbasis **Microsoft Excel** yang dirancang untuk analisis bisnis, pemantauan performa penjualan, dan analitika sumber daya manusia (HR Analytics). Portofolio ini menampilkan penerapan end-to-end data processing, Pivot Table, Pivot Charts, Timeline, Slicers, KPI Cards, serta penyusunan dashboard visual yang interaktif dan dinamis.

---

## 📑 Daftar Studi Kasus

1. [Case Study 1: Supermarket Sales Dashboard](#1-case-study-1-supermarket-sales-dashboard)
2. [Case Study 2: Car Sales Performance Dashboard](#2-case-study-2-car-sales-performance-dashboard)
3. [Case Study 3: Employee Retention & Attrition Risk Analytics](#3-case-study-3-employee-retention--attrition-risk-analytics)

---

## 1. Case Study 1: Supermarket Sales Dashboard

![Supermarket Sales Dashboard](screenshots/supermarket_sales_dashboard.png)

### 📌 Ringkasan Proyek
Menganalisis performa transaksi penjualan supermarket ritel di 3 cabang kota utama (Yangon, Naypyitaw, dan Mandalay) untuk mengevaluasi pendapatan, tren bulanan, kontribusi lini produk, dan kepuasan pelanggan (customer rating).

* **Sumber Dataset:** [Kaggle - Supermarket Sales Cleaned Dataset](https://www.kaggle.com/datasets/muhdaniyal/supermarket-sales-cleaned-dataset)
* **Tema Warna Dashboard:** *Sky Blue Clean Modern*

### 🔑 Metrik Utama (KPIs)
* **Total Transactions:** 1,000 transaksi
* **Total Revenue:** $338,346.12
* **Total COGS (Cost of Goods Sold):** $307,587.38
* **Gross Income:** $15,379.37
* **Total Quantity Sold:** 5,510 unit
* **Average Rating:** 6.97 / 10

### 📈 Visualisasi & Komponen Analisis
* **Monthly Sales Trend (Line Chart):** Pola tren penjualan bulanan dari Januari hingga Maret.
* **Revenue by City / Branch (Column Chart):** Perbandingan pendapatan per cabang (Yangon, Naypyitaw, Mandalay).
* **Revenue by Product Line (Bar Chart):** Pemetaan performa penjualan per kategori produk (Food & Beverages, Sports & Travel, Electronic Accessories, Fashion Accessories, Home & Lifestyle, Health & Beauty).
* **Rating by Product (Bar Chart):** Distribusi skor kepuasan pelanggan terhadap masing-masing lini produk.
* **Interactive Slicers & Timeline:** Filter dinamis berdasarkan `Date (Timeline)`, `City/Branch`, `Customer Type (Member vs Normal)`, dan `Product Line`.

---

## 2. Case Study 2: Car Sales Performance Dashboard

![Car Sales Dashboard](screenshots/car_sales_dashboard.png)

### 📌 Ringkasan Proyek
Dashboard analitika komprehensif untuk memantau efektivitas penjualan mobil di seluruh jaringan dealer dan wilayah (regions). Memungkinkan stakeholder membedah performa volume penjualan, pendapatan kotor, preferensi model mobil, tipe bodi kendaraan, jenis transmisi, hingga karakteristik pelanggan.

* **Sumber Dataset:** [Kaggle - Car Sales Report](https://www.kaggle.com/datasets/missionjee/car-sales-report)
* **Tema Warna Dashboard:** *Forest & Emerald Green Corporate*

### 🔑 Metrik Utama (KPIs)
* **Total Transactions:** 10,393 unit terjual
* **Total Revenue:** $294,029.5K (~$294 Juta)
* **Average Revenue per Car:** $28.3K
* **Average Customer Annual Income:** $832.6K

### 📈 Visualisasi & Fitur Interaktif
* **Switchable Views via Bookmark / Tabs:**
  * **Company Performance:** Menampilkan *Total Sold by Company* dan *Total Revenue by Company* (Chevrolet, Dodge, Ford, Mitsubishi, Toyota, dll.).
  * **Regional Analysis:** Distribusi unit terjual dan pendapatan per wilayah (Aurora, Austin, Greenville, Janesville, Scottsdale, Middletown, Pasco).
  * **Dealer Analysis:** Analisis komparatif unit terjual (*Total Sold by Dealer*) dan pendapatan (*Total Revenue by Dealer*) di seluruh dealer partner.
  * **Types of Cars Breakdown:** Distribusi penjualan berdasarkan *Body Style* (SUV, Hatchback, Sedan, Passenger, Hardtop), *Transmission & Engine* (Double Overhead Camshaft Auto vs Overhead Camshaft Manual), dan *Color*.
* **Interactive Slicers:**
  * Waktu: `Years (2022, 2023)`, `Quarters (Qtr1 - Qtr4)`, `Months (Jan - Dec)`.
  * Geografis & Partner: `Dealer Region`, `Dealer Name`.
  * Kendaraan: `Car Model Slicer` (multi-select filter model mobil).

---

## 3. Case Study 3: Employee Retention & Attrition Risk Analytics

![HR Analytics Dashboard](screenshots/hr_attrition_dashboard.png)

### 📌 Ringkasan Proyek
Analisis prediktif dan deskriptif SDM untuk memitigasi risiko turnover karyawan (*employee attrition*). Dashboard ini memetakan profil risiko karyawan ke dalam tiga tingkatan (*Low Risk [0]*, *Medium Risk [1]*, dan *High Risk [2]*) berdasarkan faktor kepuasan kerja, beban kerja bulanan, masa kerja, latar belakang pendidikan, dan peran kerja.

* **Sumber Dataset:** [Kaggle - HR Analytics: Employee Attrition & Risk Levels](https://www.kaggle.com/datasets/bertnardomariouskono/hr-analytics-employee-attrition-and-risk-levels)
* **Tema Warna Dashboard:** *Deep Purple & Modern Violet*

### 🔑 Metrik Utama (KPIs)
* **Total Employees:** 15,000 karyawan (7,507 Female | 7,493 Male)
* **Attrition Risk Distribution:**
  * **Low Risk (0):** 50.00% (7,500 karyawan)
  * **Medium Risk (1):** 35.00% (5,250 karyawan)
  * **High Risk (2):** 15.00% (2,250 karyawan)
* **Average Monthly Hours:** 170.44 jam/bulan
* **Job Satisfaction Score (JS Score):** 2.91 / 4.00
* **Work-Life Balance Score (WLB Score):** 2.70 / 4.00

### 📈 Visualisasi & Analisis Korelasi
* **Risk Level by Role (Clustered Column Chart):** Analisis risiko turnover di setiap divisi (Analyst, Data Scientist, HR Specialist, Manager, Sales Executive, Software Engineer).
* **Risk Level by Education:** Pemetaan risiko karyawan dari tingkat *Below College*, *College*, *Bachelor*, *Master*, hingga *PhD*.
* **Risk Level by Years at Company (Line Chart):** Tren tingkat risiko berdasarkan kelompok masa kerja (0–5 tahun, 5–10 tahun, hingga 45–50 tahun).
* **Risk Level by Job Satisfaction & Work-Life Balance (Doughnut / Radial Metrics):** Korelasi langsung antara penurunan skor kepuasan kerja & keseimbangan kerja-hidup terhadap peningkatan risiko turnover.
* **Interactive Slicers:** `Job Role`, `Attrition Risk Level`, `Gender`, dan `Education Level`.

---

## 🛠️ Tools & Formula yang Digunakan
* **Microsoft Excel** (Advanced formulas, Pivot Table, Pivot Chart, Slicers, Report Connections, Timeline).
* **Data Cleansing & Formatting:** Text-to-Columns, Date/Time parsing, Currency formatting, Duplicate checks.
* **Dashboard Design & UX:** Custom shape layouting, Flat UI color palette, Grid alignment, Visual hierarchy, Navigation buttons/tabs.

---

## 📁 Struktur Repositori

```text
├── README.md
├── Case-1-Supermarket-Sales/
│   ├── Supermarket_Sales_Dashboard.xlsx
│   └── raw_data/
├── Case-2-Car-Sales/
│   ├── Car_Sales_Performance_Dashboard.xlsx
│   └── raw_data/
├── Case-3-HR-Risk-Analytics/
│   ├── Employee_Attrition_Risk_Dashboard.xlsx
│   └── raw_data/
└── screenshots/
    ├── supermarket_sales_dashboard.png
    ├── car_sales_dashboard.png
    └── hr_attrition_dashboard.png
```

---

## 🚀 Cara Menjalankan File
1. Clone repositori ini:
   ```bash
   git clone https://github.com/<username>/excel-dashboard-portfolio.git
   ```
2. Buka file `.xlsx` menggunakan **Microsoft Excel 2016 atau versi yang lebih baru / Microsoft 365** untuk mendukung fitur *Slicers* dan kalkulasi Pivot Chart secara optimal.
3. Aktifkan makro jika diminta (*jika menggunakan navigasi VBA/Shapes*).
4. Gunakan panel Slicer di sisi atas/kiri untuk mengeksplorasi data secara dinamis.
