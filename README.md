# Ujian Tengah Semester (UTS) - Graf Sains Data

**Identitas Mahasiswa:**
- **Nama:** Mohammad Tyas Subianto
- **NIM:** 24031554077
- **Mata Kuliah:** Graf Sains Data

---

## Pembagian Rentang Waktu (Dataset RetailRocket)

Sesuai dengan ketentuan perhitungan berdasarkan 3 digit terakhir NIM:
- **P1 (Training Period):** 13 Mei 2015 – 5 Juli 2015
- **P2 (Testing Period):** 6 Juli 2015 – 10 September 2015

---

## Struktur File Proyek

```text
UTS-GSD/
├── data/
│   └── events_P1_train.csv  # Dataset hasil filter periode P1 (Training)
├── screenshots/             # Bukti tangkapan layar eksekusi kueri di Neo4j Browser
├── uts-gsd.ipynb            # Jupyter Notebook utama berisi pipeline analisis lengkap & visualisasi
├── requirements.txt         # Dependensi library Python yang dibutuhkan
├── .gitignore               # Konfigurasi pengecualian file
└── README.md                # Dokumentasi proyek
```

---

## Langkah Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/Underag3/UTS-GSD.git
   cd UTS-GSD
   ```

2. Buat dan aktifkan virtual environment (opsional tapi disarankan):
   ```bash
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # Linux/macOS:
   source venv/bin/activate
   ```

3. Pasang dependensi:
   ```bash
   pip install -r requirements.txt
   ```

4. Unduh dataset RetailRocket (`events.csv`) dan letakkan di folder `data/events.csv`.
5. Buka dan jalankan seluruh cell pada notebook `uts-gsd.ipynb`.
