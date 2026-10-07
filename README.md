# Prediksi Diabetes Belum Terdiagnosis Berbasis Fitur Non-Laboratorium: Validasi Temporal Lintas Siklus NHANES 2013–2023

Repositori ini berisi kode, data, dan hasil analisis untuk artikel:

> Rumintarsih, A. (2026). *Prediksi Diabetes Belum Terdiagnosis Berbasis Fitur Non-Laboratorium: Validasi Temporal Lintas Siklus NHANES 2013–2023*. Universitas Nusa Mandiri.

## Ringkasan

Model regresi logistik (LR), random forest (RF), gradient boosting (GB), dan multilayer perceptron (MLP) dilatih menggunakan 14 fitur non-laboratorium dari NHANES 2013–2016. Model kemudian divalidasi secara temporal pada siklus 2017–2018 dan siklus pascapandemi 2021–2023. Luaran penelitian adalah diabetes belum terdiagnosis, yakni HbA1c ≥6,5% atau glukosa plasma puasa ≥126 mg/dL pada responden yang belum pernah didiagnosis diabetes.

## Struktur folder

```
.
├── prediksi_diabetes_nhanes.ipynb   # seluruh analisis, dari data sampai gambar
├── data/
│   ├── nhanes_HIJL_adults.csv.gz    # data gabungan NHANES dewasa ≥20 tahun (4 siklus)
│   ├── raw/                         # berkas XPT asli CDC (terisi bila DOWNLOAD = True)
│   └── README.md                    # kamus variabel dan sumber data
├── outputs/                         # tabel hasil (.csv) dan Gambar 1–4 (.png)
├── requirements.txt
├── CITATION.cff
└── LICENSE
```

## Cara menjalankan

```bash
pip install -r requirements.txt
jupyter notebook prediksi_diabetes_nhanes.ipynb
```

Jalankan seluruh sel secara berurutan (Run All). Waktu eksekusi sekitar 5–10 menit pada laptop biasa. Secara bawaan notebook memakai `data/nhanes_HIJL_adults.csv.gz`. Untuk mengunduh ulang data mentah dari CDC, ubah `DOWNLOAD = True` pada sel pertama.

## Sumber data

National Center for Health Statistics (NCHS), Centers for Disease Control and Prevention. National Health and Nutrition Examination Survey (NHANES), siklus 2013–2014 (H), 2015–2016 (I), 2017–2018 (J), dan August 2021–August 2023 (L). https://wwwn.cdc.gov/nchs/nhanes/

Data NHANES merupakan data publik dan anonim. Pengumpulan data NHANES telah memperoleh persetujuan dari NCHS Research Ethics Review Board.

## Sitasi

Apabila menggunakan kode atau data ini, mohon sitasi artikel di atas dan arsip Zenodo repositori ini (lihat `CITATION.cff`).

## Lisensi

Kode dirilis dengan lisensi MIT. Data NHANES berada dalam domain publik.
