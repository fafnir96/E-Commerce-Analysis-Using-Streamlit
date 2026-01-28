# Proyek Analisis Data: E-Commerce Public Dataset

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Proyek ini adalah tugas akhir dari program "Belajar Analisis Data dengan Python". Tujuan dari proyek ini adalah untuk menganalisis dataset _E-Commerce Public Dataset_, menemukan wawasan bisnis (_insight_), dan membuat dashboard interaktif menggunakan Streamlit.

## Pertanyaan Bisnis

Proyek ini bertujuan untuk menjawab pertanyaan bisnis berikut:

1. **Produk Terlaris & Kurang Diminati:** Kategori produk apa yang memiliki penjualan tertinggi dan terendah?
2. **Demografi Pelanggan:** Bagaimana persebaran pelanggan berdasarkan lokasi negara bagian (state)?
3. **Analisis Pelanggan (RFM):** Siapa pelanggan terbaik berdasarkan _Recency_, _Frequency_, dan _Monetary_?

## Struktur Folder

Pastikan direktori proyek Anda memiliki struktur berikut agar dapat berjalan dengan lancar:

```text
submission/
├── dashboard/
│   ├── main_data.csv       # Data bersih hasil cleaning
│   └── dashboard.py        # Kode utama dashboard Streamlit
├── data/                   # Folder berisi data mentah (raw data)
├── notebook.ipynb          # Notebook analisis data (Jupyter/Colab)
├── README.md               # Dokumentasi proyek
├── requirements.txt        # Daftar library yang dibutuhkan
└── url.txt                 # Tautan dashboard Streamlit Cloud
```

## Memakai Anaconda

```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Memakai Shell/Terminal

```
mkdir submission_proyek
cd submission_proyek
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app

```
streamlit run dashboard.py
```
