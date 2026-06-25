# UAS-Data-Mining-Forecasting
Prediksi Sales E-Commerce Harian Menggunakan Teknik Machine Learning
# Prediksi Sales E-Commerce Harian
## Menggunakan Teknik Machine Learning

### Identitas Mahasiswa
- **Nama**        : Mixo Vidianto
- **NIM**         : 1224160001
- **Kelas**       : SI 24 SIM SHIFT
- **Mata Kuliah** : Konsep Data Warehouse & Mining
- **Dosen**       : Agus Rifaldi, S.Kom

---

### Deskripsi Project
Project ini membangun model forecasting untuk 
memprediksi total penjualan harian (sales_amount_gbp) 
menggunakan dataset Global E-Commerce Forecasting 
(±100.000 baris transaksi, 34 negara, Des 2009–Des 2010).

---

### Studi Kasus
Forecasting (Peramalan)

### Dataset
- **Nama**   : Global E-Commerce Forecasting Dataset
- **Jumlah** : ±100.000 baris transaksi
- **Periode**: Desember 2009 – Desember 2010
- **Negara** : 34 negara
- **Sumber** : [Link Dataset]

---

### Algoritma yang Digunakan
| No | Model | R² Score | Status |
|---|---|---|---|
| 1 | Linear Regression | 0.4001 | ❌ |
| 2 | Random Forest | 0.8193 | ✅ |
| 3 | Gradient Boosting | 0.8218 | ✅ |
| 4 | KNN Regressor | 0.4225 | ❌ |
| 5 | SVR | 0.0419 | ❌ |

**Model Terbaik: Gradient Boosting (R² = 0.8218)**

---

### Links
- 🌐 **Website Portofolio** : https://sites.google.com/view/datascienceportofolio/uas-mixo-vidianto
- 🎥 **Video Presentasi**   : https://youtu.be/f2jSFNEYc4Q

---

### File dalam Repository
- `UAS_KDMW_FORECASTING_5models.ipynb` - Source code
- `global_ecommerce_forecasting.csv` - Dataset
- `README.md` - Dokumentasi project
