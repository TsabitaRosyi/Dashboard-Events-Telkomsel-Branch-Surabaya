# 📊 Dashboard Events Telkomsel Branch Surabaya

### Business Intelligence | Python ETL & Looker Studio Dashboard

<img width="1248" height="944" alt="Screenshot 2026-11-01 184215" src="https://github.com/user-attachments/assets/73956bf2-cb11-4d08-b2c9-05fc472f8ab1" />


## 📌 Project Overview

Proyek **Business Intelligence Dashboard Events Telkomsel Branch Surabaya** merupakan proyek yang dikerjakan selama program **Magang Mandiri di Telkomsel Branch Surabaya**. Proyek ini berfokus pada pengolahan dan visualisasi data events (acara atau aktivitas lapangan) untuk membantu proses monitoring aktivitas operasional dan performa penjualan.

Permasalahan utama yang dihadapi adalah data operasional yang tersebar dalam beberapa file Excel bulanan sehingga proses pengolahan, pemantauan, dan analisis membutuhkan waktu lebih lama.

Untuk mengatasi permasalahan tersebut, dilakukan proses **Extract, Transform, Load (ETL)** menggunakan Python guna mengintegrasikan data bulanan menjadi satu dataset yang terstruktur. Dataset tersebut kemudian digunakan sebagai sumber data untuk membangun dashboard interaktif menggunakan **Looker Studio**.

Dashboard dirancang untuk membantu manajemen memantau persebaran Digital Seller (DS) serta membandingkan rencana dan realisasi aktivitas events di wilayah Surabaya dan Madura.

Proyek ini juga digunakan sebagai bahan **rekognisi Mata Kuliah Kecerdasan Bisnis**.


---

## 🎯 Background

Telkomsel Branch Surabaya mengelola berbagai data operasional dan penjualan yang digunakan untuk mendukung aktivitas bisnis. Salah satunya adalah data events yang berisi informasi mengenai rencana dan realisasi aktivitas lapangan.

Data tersebut tersedia dalam beberapa file Excel berdasarkan periode bulanan. Kondisi ini menyebabkan beberapa tantangan, antara lain:

- Data tersebar dalam beberapa file sehingga membutuhkan proses integrasi sebelum dianalisis.
- Proses monitoring performa events belum tersaji dalam satu tampilan visual yang terpusat.
- Perbandingan antara rencana (Plan) dan realisasi (Actual) membutuhkan pengolahan data terlebih dahulu.
- Pemantauan persebaran Digital Seller berdasarkan wilayah membutuhkan penyajian data geografis yang lebih informatif.

Berdasarkan diskusi dengan mentor, diperlukan sebuah dashboard interaktif yang dapat menyajikan informasi operasional secara ringkas, visual, dan mudah dipahami.

Oleh karena itu, dikembangkan solusi Business Intelligence dengan mengintegrasikan data menggunakan Python dan menyajikannya melalui Looker Studio.

## 🎯 Project Objectives

Tujuan utama proyek ini adalah:

1. Mengintegrasikan data events bulanan periode Januari–September 2024 ke dalam satu dataset.
2. Melakukan proses data cleaning dan preprocessing menggunakan Python.
3. Menerapkan konsep ETL (Extract, Transform, Load) untuk menghasilkan dataset yang terstruktur dan siap dianalisis.
4. Membangun dashboard interaktif menggunakan Looker Studio.
5. Memvisualisasikan persebaran Digital Seller berdasarkan wilayah operasional.
6. Membandingkan jumlah Plan Event dan Actual Event untuk mengevaluasi realisasi aktivitas lapangan.
7. Menghasilkan insight dan rekomendasi yang dapat mendukung proses pengambilan keputusan bisnis.

---

## 🖥️ Dashboard Preview

### Dashboard Events by Telkomsel Branch Surabaya

Dashboard dikembangkan menggunakan Looker Studio dengan tiga visualisasi utama.

<p align="center">
  <img src="images/dashboard-events.png" alt="Dashboard Events Telkomsel Branch Surabaya" width="100%">
</p>

### Dashboard Components

| Visualisasi | Deskripsi |
|---|---|
| **Geo Map** | Menampilkan persebaran DS Total berdasarkan kota di wilayah Surabaya dan Madura, dengan rentang nilai 213–1.794. |
| **Pie Chart** | Menunjukkan proporsi jumlah Digital Seller berdasarkan masing-masing kota. |
| **Bar Chart** | Membandingkan jumlah Plan Event dan Actual Event pada setiap kota untuk melihat tingkat realisasi aktivitas. |

**Dashboard Access:** 

[🔗 View Looker Studio Dashboard](MASUKKAN_LINK_DASHBOARD_DI_SINI)

*Catatan: Ganti link di atas dengan tautan dashboard apabila diperbolehkan untuk dipublikasikan.*

---

## 💡 Key Insights

Berdasarkan hasil visualisasi dashboard, diperoleh beberapa insight utama:

### 1. Distribution of Digital Sellers

Kota Surabaya mendominasi jumlah Digital Seller dengan kontribusi sekitar **61,7%** dari keseluruhan persebaran yang ditampilkan.

Distribusi berdasarkan kota:

| Kota | Kontribusi |
|---|---:|
| Surabaya | 61,7% |
| Bangkalan | 13,1% |
| Pamekasan | 9,8% |
| Sumenep | 8,1% |
| Sampang | 7,3% |

Surabaya menjadi wilayah dengan konsentrasi Digital Seller terbesar dibandingkan kota lainnya.

### 2. Plan Event vs Actual Event

Perbandingan antara Plan Event dan Actual Event menunjukkan adanya perbedaan tingkat realisasi aktivitas di setiap kota.

- Surabaya memiliki gap terbesar antara jumlah event yang direncanakan dan yang terealisasi.
- Bangkalan, Sumenep, Sampang, dan Pamekasan menunjukkan realisasi yang relatif mendekati rencana.
- Perbedaan antara rencana dan realisasi dapat menjadi bahan evaluasi efektivitas pelaksanaan aktivitas lapangan.

### 3. Business Opportunity

Surabaya memiliki potensi pengembangan aktivitas bisnis yang besar karena kontribusinya terhadap persebaran Digital Seller cukup dominan.

Namun, adanya gap antara Plan Event dan Actual Event menunjukkan perlunya evaluasi lebih lanjut terhadap pelaksanaan kegiatan di wilayah tersebut.

### 4. Business Recommendations

Berdasarkan insight tersebut, beberapa rekomendasi yang dapat dipertimbangkan adalah:

1. **Regular Monitoring:** Melakukan pemantauan rutin terhadap pencapaian Plan Event dan Actual Event.
2. **Resource Optimization:** Mengevaluasi alokasi sumber daya dan agen penjualan berdasarkan kebutuhan masing-masing wilayah.
3. **Performance Evaluation:** Mengidentifikasi faktor yang menyebabkan kesenjangan antara rencana dan realisasi event, khususnya di Surabaya.
4. **Data-Driven Decision Making:** Memanfaatkan dashboard sebagai salah satu dasar evaluasi dan perencanaan aktivitas operasional berikutnya.

---

## 🛠️ Tools & Technologies

Berikut teknologi dan tools yang digunakan dalam pengembangan proyek:

| Kategori | Tools / Technologies | Penggunaan |
|---|---|---|
| Programming Language | Python | Pengolahan dan integrasi data |
| Data Manipulation | Pandas | Data cleaning, merging, dan preprocessing |
| Numerical Computing | NumPy | Mendukung operasi numerik |
| File Handling | os | Pengelolaan direktori dan file |
| Development Environment | Jupyter Notebook | Menjalankan kode ETL dan eksplorasi data |
| Spreadsheet | Microsoft Excel | Pemeriksaan dan validasi data |
| Business Intelligence | Looker Studio | Pembuatan dashboard dan visualisasi |
| Data Source | MyNami Telkomsel | Sumber data events internal |

---

## 🔄 Project Workflow

Proyek ini dilaksanakan melalui beberapa tahapan untuk memastikan proses pengolahan data hingga visualisasi berjalan secara sistematis.

```text
Problem Identification
        ↓
Literature Study
        ↓
Data Collection
        ↓
Data Understanding
        ↓
Data Cleaning & Preprocessing
        ↓
Data Integration (ETL)
        ↓
Dashboard Design
        ↓
Dashboard Development
        ↓
Dashboard Validation
        ↓
Data Analysis & Business Insights
```

### Workflow Description

| No. | Tahapan | Deskripsi |
|---|---|---|
| 1 | Problem Identification | Mengidentifikasi kebutuhan monitoring data events melalui diskusi dengan mentor. |
| 2 | Literature Study | Mempelajari penggunaan Looker Studio dan konsep visualisasi data melalui dokumentasi serta tutorial. |
| 3 | Data Collection | Mengumpulkan data events bulanan dari platform internal MyNami melalui menu Manage Resource. |
| 4 | Data Understanding | Memahami struktur dataset, nama kolom, tipe data, serta informasi yang tersedia. |
| 5 | Data Cleaning & Preprocessing | Membersihkan data, menangani missing values, menghapus kolom yang tidak diperlukan, dan menyesuaikan tipe data. |
| 6 | Data Integration | Menggabungkan sembilan dataset bulanan menggunakan Python. |
| 7 | Dashboard Design | Menentukan informasi utama, struktur dashboard, dan jenis visualisasi yang sesuai dengan kebutuhan monitoring. |
| 8 | Dashboard Development | Menghubungkan dataset hasil ETL ke Looker Studio dan membangun visualisasi interaktif. |
| 9 | Dashboard Validation | Melakukan evaluasi dashboard bersama mentor, termasuk penambahan visualisasi geografis. |
| 10 | Data Analysis | Menganalisis hasil visualisasi, mengidentifikasi kesenjangan performa, serta menyusun rekomendasi bisnis. |

---

## ⚙️ ETL Process

Proses ETL dilakukan menggunakan Python dengan bantuan library Pandas dan NumPy.

### 1. Extract

Tahap Extract dilakukan dengan membaca sembilan file Excel bulanan yang berasal dari platform internal MyNami Telkomsel.

**Periode data:** Januari–September 2024.

Contoh nama file:

```text
Reporting_Events_202401.xlsx
Reporting_Events_202402.xlsx
Reporting_Events_202403.xlsx
...
Reporting_Events_202409.xlsx
```

Setiap file memiliki lebih dari 1.000 baris dan 26 kolom yang mencakup data operasional seluruh cabang.

### 2. Transform

Tahap Transform bertujuan untuk membersihkan dan menyatukan data agar memiliki struktur yang konsisten.

Proses yang dilakukan meliputi:

- **Data Filtering:** Memfilter data berdasarkan `BRANCH == 'SURABAYA'`.
- **Data Integration:** Menggabungkan sembilan dataset bulanan menggunakan `pd.concat()`.
- **Column Removal:** Menghapus kolom yang tidak diperlukan atau duplikat, seperti `OMSET TOTAL.1`.
- **Missing Value Handling:** Menangani nilai kosong menggunakan `fillna(0)`.
- **Data Type Conversion:** Mengonversi kolom bertipe float menjadi integer sesuai kebutuhan analisis, termasuk kolom persentase `DS RATIO` dan `ACTUAL CALL (%)`.
- **Data Validation:** Memeriksa struktur dan konsistensi dataset menggunakan `.info()` dan `.head()`.

Contoh implementasi:

```python
import pandas as pd
import numpy as np
import os

# Menggabungkan data bulanan
all_data = []

for file in os.listdir(folder_path):
    if file.endswith('.xlsx'):
        file_path = os.path.join(folder_path, file)

        df = pd.read_excel(file_path)

        # Filter data Branch Surabaya
        df = df[df['BRANCH'] == 'SURABAYA']

        all_data.append(df)

# Integrasi seluruh dataset
merged_data = pd.concat(all_data, ignore_index=True)

# Menghapus kolom yang tidak diperlukan
merged_data = merged_data.drop(
    columns=['OMSET TOTAL.1'],
    errors='ignore'
)

# Menangani missing values
merged_data = merged_data.fillna(0)

# Memeriksa struktur dataset
merged_data.info()
merged_data.head()
```

*Catatan: Potongan kode di atas merupakan ilustrasi tahapan ETL. Sesuaikan dengan implementasi aktual pada notebook proyek.*

### 3. Load

Tahap Load dilakukan dengan menyimpan dataset hasil transformasi ke dalam format Excel atau CSV.

File hasil pengolahan:

```text
merged_Events_data.xlsx
merged_Events_data.csv
```

Dataset kemudian digunakan sebagai sumber data untuk membangun dashboard di Looker Studio.

### ETL Result

| Keterangan | Hasil |
|---|---:|
| Periode Data | Januari–September 2024 |
| Jumlah File Sumber | 9 file Excel |
| Data per File | Lebih dari 1.000 baris |
| Kolom Awal | 26 kolom |
| Branch yang Dianalisis | SURABAYA |
| Jumlah Baris Akhir | 45 baris |
| Jumlah Kolom Akhir | 24 kolom |

**Final Dataset:** 45 baris dan 24 kolom yang telah melalui proses integrasi dan preprocessing sehingga siap digunakan untuk visualisasi dashboard.

---

## 📁 Repository Structure

Berikut struktur direktori repositori proyek:

```text
Dashboard-Events-Telkomsel-Branch-Surabaya/
│
├── README.md
│
├── notebooks/
│   └── code.ipynb
│
├── docs/
│   └── Laporan_Kecerdasan_Bisnis.pdf
│
├── data/
│   └── output EVENTS alls.xlsx

```

### Directory Description

| Folder / File | Deskripsi |
|---|---|
| `notebooks/` | Berisi Jupyter Notebook untuk proses ETL dan pengolahan data. |
| `docs/` | Berisi laporan proyek sebagai bagian dari rekognisi Mata Kuliah Kecerdasan Bisnis. |
| `data/` | Berisi  sumber dan struktur data dalam format excel.|
| `README.md` | Dokumentasi utama proyek. |

---

## 📖 Data Dictionary

Berikut merupakan beberapa variabel utama yang digunakan dalam proyek.

| Nama Kolom | Deskripsi |
|---|---|
| `AREA` | Informasi wilayah operasional berdasarkan area. |
| `REGIONAL` | Informasi regional operasional. |
| `BRANCH` | Identifikasi cabang operasional. |
| `CLUSTER` | Pengelompokan wilayah operasional. |
| `CITY` | Nama kota berdasarkan lokasi aktivitas. |
| `DS TOTAL` | Jumlah keseluruhan Digital Seller. |
| `DS ACTIVE` | Jumlah Digital Seller yang aktif. |
| `DS RATIO (%)` | Rasio Digital Seller aktif terhadap total Digital Seller. |
| `OMSET TOTAL` | Informasi total omzet. |
| `OMSET DIGITAL` | Informasi omzet dari aktivitas digital. |
| `PLAN POI` | Jumlah rencana aktivitas kunjungan Point of Interest. |
| `ACTUAL POI` | Jumlah realisasi aktivitas kunjungan Point of Interest. |
| `PLAN EVENT` | Jumlah event yang direncanakan. |
| `ACTUAL EVENT` | Jumlah event yang berhasil direalisasikan. |
| `ACTUAL CALL (%)` | Persentase realisasi aktivitas call. |
| `SALES` | Informasi terkait aktivitas penjualan. |
| `TRX DIGITAL` | Informasi transaksi digital. |
| `VF` | Metrik operasional sesuai definisi pada dataset sumber. |

*Catatan: Penjelasan variabel di atas merupakan deskripsi umum berdasarkan nama kolom. Untuk penggunaan operasional, definisi dan perhitungan setiap variabel perlu mengacu pada dokumentasi resmi perusahaan.*

---

## 🔒 Data Privacy & Disclaimer

Dataset dalam proyek ini berasal dari platform internal **MyNami Telkomsel**, sehingga terdapat batasan dalam publikasi data.

Untuk menjaga kerahasiaan informasi perusahaan:

- Dataset mentah tidak disertakan dalam repositori GitHub.
- Data internal perusahaan tidak dibagikan secara publik.
- Screenshot dashboard yang dipublikasikan perlu dipastikan tidak menampilkan informasi sensitif.
- Replikasi proyek dapat dilakukan menggunakan dataset dummy dengan struktur kolom yang serupa.
- Publikasi dashboard dilakukan dengan memperhatikan izin dan kebijakan perusahaan.

Proyek ini ditampilkan sebagai dokumentasi pengalaman pembelajaran dan pengembangan keterampilan Business Intelligence selama kegiatan magang.

---

## 🎓 Business Intelligence Implementation

Proyek ini menerapkan beberapa konsep utama dalam Mata Kuliah Kecerdasan Bisnis.

| Konsep Business Intelligence | Implementasi |
|---|---|
| Data Collection | Mengumpulkan data events bulanan dari platform internal MyNami. |
| Data Integration | Menggabungkan sembilan file Excel menjadi satu dataset menggunakan Pandas. |
| Data Cleaning | Menangani missing values, menghapus kolom yang tidak diperlukan, dan menyesuaikan tipe data. |
| ETL Process | Menerapkan Extract, Transform, dan Load menggunakan Python. |
| Business Reporting | Menyajikan informasi operasional melalui dashboard interaktif. |
| Data Visualization | Menggunakan Geo Map, Pie Chart, dan Bar Chart. |
| Business Analysis | Menganalisis distribusi Digital Seller dan perbandingan Plan Event dengan Actual Event. |
| Decision Support | Menyusun insight dan rekomendasi untuk mendukung evaluasi aktivitas bisnis. |

Melalui implementasi tersebut, proyek ini menunjukkan bagaimana data operasional dapat diolah menjadi informasi yang lebih terstruktur dan mudah dipahami untuk mendukung proses pengambilan keputusan.

---

## 🔮 Future Improvements

Beberapa pengembangan yang dapat dilakukan untuk meningkatkan fungsionalitas dashboard antara lain:

1. **Automated ETL Pipeline:** Mengotomatisasi proses pengambilan dan pengolahan data bulanan agar pembaruan dataset lebih efisien.
2. **Additional KPI Monitoring:** Menambahkan indikator performa lain sesuai kebutuhan monitoring operasional.
3. **Interactive Filtering:** Mengembangkan filter berdasarkan periode, wilayah, dan kategori aktivitas.
4. **Historical Performance Analysis:** Melakukan analisis tren performa events berdasarkan periode waktu.
5. **Advanced Business Analysis:** Mengembangkan analisis lebih lanjut untuk mengidentifikasi faktor yang memengaruhi kesenjangan antara rencana dan realisasi event.

---

<p align="center">
  <b>Turning Data into Insights for Better Business Decisions.</b>
  <br>
  Thank you for visiting this repository! 
</p>
