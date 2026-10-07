# Data

`nhanes_HIJL_adults.csv.gz` berisi 24.866 responden NHANES berusia ≥20 tahun dari empat siklus. Setiap baris adalah satu responden.

| Kolom | Berkas NHANES | Keterangan |
| --- | --- | --- |
| cycle | – | H = 2013–2014, I = 2015–2016, J = 2017–2018, L = 2021–2023 |
| SEQN | DEMO | Nomor responden |
| RIDAGEYR, RIAGENDR, RIDRETH3, DMDEDUC2, INDFMPIR, RIDEXPRG | DEMO | Usia, jenis kelamin, ras/etnis, pendidikan, rasio pendapatan–kemiskinan, status hamil |
| WTMEC2YR, SDMVPSU, SDMVSTRA | DEMO | Bobot pemeriksaan, PSU, strata |
| DIQ010, DIQ050, DIQ070, DIQ160 | DIQ | Diagnosis diabetes, insulin, obat penurun glukosa, prediabetes |
| LBXGH | GHB | HbA1c (%) |
| LBXGLU, WTSAF2YR | GLU | Glukosa plasma puasa (mg/dL), bobot subsampel puasa |
| BMXBMI, BMXWAIST, BMXHT, BMXWT | BMX | IMT, lingkar pinggang, tinggi, berat |
| BPXSY1–3, BPXDI1–3 | BPX | Tekanan darah auskultasi (H, I, J) |
| BPXOSY1–3, BPXODI1–3 | BPXO | Tekanan darah osilometrik (L) |
| MCQ300C | MCQ | Riwayat keluarga diabetes (tidak tersedia pada L) |
| BPQ020, BPQ080 | BPQ | Riwayat hipertensi, riwayat kolesterol tinggi |
| SMQ020 | SMQ | Pernah merokok ≥100 batang |
| PAQ605, PAQ620, PAQ650, PAQ665, PAD680 | PAQ | Aktivitas fisik dan waktu duduk (menit/hari) |

Sel kosong berarti data tidak tersedia atau tidak ditanyakan. Kode jawaban mengikuti dokumentasi resmi NHANES.
