# Submission-Fundamental-Analisis-Data
# 🛒 Dashboard Analisis E-Commerce

Dashboard interaktif untuk menganalisis data transaksi e-commerce periode 2016–2018 menggunakan Streamlit.

---

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk:
- Menganalisis tren penjualan dari waktu ke waktu
- Mengidentifikasi kategori produk paling banyak terjual dan menghasilkan revenue terbesar
- Mengetahui distribusi pelanggan berdasarkan wilayah
- Melakukan segmentasi pelanggan menggunakan metode RFM (Recency, Frequency, Monetary)

---

## ⚙️ Setup Environment - Anaconda

```bash
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt

## ⚙️ Setup Environment - Shell/Terminal
'''bash
mkdir proyek_analisis_data
cd proyek_analisis_data
pip install -r requirements.txt

## ▶️ Menjalankan Dashboard
'''bash
streamlit run dashboard/dashboard_fundamental_analisis_data.py
