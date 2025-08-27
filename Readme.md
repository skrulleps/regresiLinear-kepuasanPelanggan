# Analisis Regresi Linier - Tingkat Kepuasan Pelanggan

Proyek ini melakukan analisis regresi linier sederhana untuk memprediksi total pembelian berdasarkan pendapatan pelanggan dan menganalisis hubungannya dengan tingkat kepuasan.

## 📊 Dataset

Dataset yang digunakan berisi informasi 20 pelanggan dengan variabel:
- **ID Pelanggan**: Identifikasi unik pelanggan
- **Nama**: Nama pelanggan
- **Jenis Kelamin**: 1 = Laki-laki, 2 = Perempuan
- **Pendapatan**: Pendapatan bulanan pelanggan (dalam Rupiah)
- **Produk**: Jenis produk yang dibeli (A, B, C, D, E)
- **Harga**: Harga per unit produk (dalam Rupiah)
- **Jumlah**: Jumlah produk yang dibeli
- **Total**: Total pembelian (Harga × Jumlah)
- **Tingkat Kepuasan**: Skala 1-3 (1 = Puas, 2 = Cukup Puas, 3 = Tidak Puas)

## 🎯 Tujuan Analisis

Membangun model regresi linier untuk:
1. Memprediksi total pembelian (`Total`) berdasarkan pendapatan pelanggan (`Pendapatan`)
2. Menganalisis hubungan antara pendapatan dengan total pembelian
3. Memahami pengaruh pendapatan terhadap keputusan pembelian

## 🛠️ Teknologi yang Digunakan

- **Python 3.x**
- **Pandas** - Manipulasi dan analisis data
- **Statsmodels** - Analisis statistik dan regresi
- **NumPy** - Komputasi numerik
- **Matplotlib/Seaborn** - Visualisasi data
- **Jupyter Notebook** - Environment pengembangan
- **Great Expectations** - Validasi kualitas data
- **ipywidgets** - Widget interaktif untuk Jupyter
- **missingno** - Visualisasi data yang hilang

## 📦 Instalasi Dependencies

```bash
pip install -r requirements.txt
```

## 🚀 Cara Menjalankan

1. Clone atau download proyek ini
2. Install dependencies dengan perintah di atas
3. Buka file `regresi.ipynb` di Jupyter Notebook
4. Jalankan semua sel kode secara berurutan

## 📈 Model Regresi

Model regresi linier sederhana yang dibangun:
- **Variabel Tak Bebas (Dependent)**: `Total` (Total pembelian)
- **Variabel Bebas (Independent)**: `Pendapatan` (Pendapatan pelanggan)

### Persamaan Regresi
```
Total = β₀ + β₁ × Pendapatan + ε
```

## 📊 Hasil Analisis

Output dari model regresi akan menampilkan:
- Koefisien regresi (β₀ dan β₁)
- R-squared dan adjusted R-squared
- P-values untuk signifikansi statistik
- Confidence intervals
- Diagnostic tests

## 🔍 Insight Bisnis

Analisis ini dapat membantu dalam:
- Memahami pola pembelian berdasarkan tingkat pendapatan
- Mengembangkan strategi pricing yang sesuai dengan segmentasi pendapatan
- Memprediksi potensi penjualan berdasarkan data demografi pendapatan
- Mengoptimalkan penawaran produk untuk berbagai segmen pelanggan

## 📁 Struktur Proyek

```
.
├── regresi.ipynb          # Notebook utama dengan analisis
├── requirements.txt       # Dependencies Python
├── README.md              # Dokumentasi proyek
└── data/
    └── dataset_statistic.csv  # Dataset pelanggan
```

## 👨‍💻 Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan:
1. Analisis multivariat dengan variabel tambahan
2. Analisis korelasi dengan tingkat kepuasan
3. Segmentasi pelanggan berdasarkan pola pembelian
4. Predictive modeling untuk forecasting penjualan
5. Visualisasi interaktif dengan Plotly

## 📝 Catatan

- Dataset menggunakan separator `;` (semicolon)
- Encoding data menggunakan format standar
- Model menggunakan OLS (Ordinary Least Squares) dari statsmodels

## 🤝 Kontribusi

Silakan fork proyek ini dan submit pull request untuk perbaikan atau penambahan fitur.

## 📄 Lisensi

Proyek ini terbuka untuk penggunaan edukasi dan penelitian.
