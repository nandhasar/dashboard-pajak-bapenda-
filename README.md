# Dashboard PAD BAPENDA Lombok Tengah

![Dashboard Screenshot](screenshot.png)

Sistem Dashboard Realisasi Pendapatan Asli Daerah (PAD) Kabupaten Lombok Tengah Tahun 2026.

## 🎯 Fitur

- 📊 **Dashboard Interaktif** - Visualisasi data PAD dengan chart dan grafik
- 📈 **Perbandingan Tahun** - Bandingkan realizasi 2026 dengan 2025
- ✏️ **Edit Data** - Form untuk update data realization per bulan
- 🔄 **Auto Refresh** - Data otomatis diperbarui setiap 5 menit

## 📁 Struktur File
dashboard-pajak-bapenda-/
├── index.html # Landing page
├── dashboard.html # Halaman dashboard utama
├── admin.html # Halaman edit data
├── README.md # Dokumentasi
└── screenshot.png # Preview dashboard

## 🔗 Link Akses

| Halaman | Deskripsi |
|---------|-----------|
| [Dashboard](dashboard.html) | Lihat visualisasi & statistik PAD |
| [Edit Data](admin.html) | Edit data realization per bulan |

## 📊 Sumber Data

Data diambil dari **Google Sheets** yang sudah dipublish:

| Sheet | Sheet ID | GID |
|-------|----------|-----|
| Data 2026 | `1BE7gPYSSlCnaIZ4Q7RvGx_L_2v46fQjkEnK3EC3VQz4` | `0` |
| Data 2025 | `1BE7gPYSSlCnaIZ4Q7RvGx_L_2v46fQjkEnK3EC3VQz4` | `757965445` |

### Format Data Google Sheets

| Kolom | Isi |
|-------|-----|
| A | Jenis Pajak |
| B | Target Tahunan |
| C-N | Realisasi per bulan (Jan-Des) |
| O | Total (auto-calculate) |
| P | % Capaian (auto-calculate) |

## ⚙️ Cara Update Data

### 📝 Opsi 1: Edit Langsung di Google Sheets
1. Buka [Google Sheets](https://docs.google.com/spreadsheets/d/1BE7gPYSSlCnaIZ4Q7RvGx_L_2v46fQjkEnK3EC3VQz4)
2. Pilih tab **Data_2026** atau **Data_2025**
3. Edit nilai realization per bulan
4. Data akan otomatis terupdate di dashboard

### 📥 Opsi 2: Export CSV dari Admin Page
1. Buka [Admin Page](admin.html)
2. Pilih jenis pajak yang ingin diedit
3. Masukkan nilai baru per bulan
4. Klik **Simpan**
5. File CSV akan ter-download
6. Import ke Google Sheets

## 📋 Jenis Pajak yang Dimonitor

1. Pajak Reklame
2. Pajak Air Tanah
3. Pajak Sarang Burung Walet
4. Pajak Mineral Bukan Logam
5. PBBP2
6. BPHTB
7. PBJT Makanan & Minuman
8. PBJT Tenaga Listrik
9. PBJT Jasa Perhotelan
10. PBJT Jasa Parkir
11. PBJT Jasa Kesenian & Hiburan
12. Opsen PKB
13. Opsen BBNKB
14. Lain-lain PAD yang Sah

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|-----------|----------|
| HTML5/CSS3 | Struktur & tampilan |
| JavaScript | Logika & interaksi |
| [Chart.js](https://www.chartjs.org/) | Visualisasi grafik |
| Google Sheets API | Sumber data |
| GitHub Pages | Hosting |

## 👥 Kontak

**BAPENDA Lombok Tengah**
- Kabupaten Lombok Tengah, NTB, Indonesia

## 📄 Lisensi

© 2026 BAPENDA Lombok Tengah - Hak Cipta Dilindungi
