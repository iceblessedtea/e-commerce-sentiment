# e-commerce-sentiment

NAMA    : KALINGGA SAKTI SATRIANTARA
NIM     : F1G122020

# 🛒 E-Commerce Sentiment Analysis (Shopee)

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap ulasan pelanggan pada platform **Shopee** menggunakan pendekatan pemrosesan bahasa alami (NLP) dan deep learning (LSTM). Sistem ini mampu mengklasifikasikan ulasan menjadi tiga kategori: **positif**, **netral**, dan **negatif**.

---

## 📂 Dataset

- Dataset diambil dari ulasan produk Shopee dan telah melalui tahap preprocessing:
  - Penghapusan URL, HTML, emoticon
  - Normalisasi kata tidak baku
  - Stopword removal
  - Tokenisasi
  - Stemming Bahasa Indonesia (Sastrawi)

---

## 🔧 Teknologi & Tools

- Python
- Pandas, NumPy
- TensorFlow + Keras
- Scikit-learn
- NLTK
- Matplotlib, WordCloud
- LSTM Neural Network

---

## 🚀 Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/iceblessedtea/e-commerce-sentiment.git
   cd e-commerce-sentiment
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Jalankan training model:
   ```bash
   python train_lstm.py
   ```

> Catatan: Pastikan kamu sudah menambahkan file `dataset-shopee-final.csv` di direktori proyek.

---

## 📈 Hasil Model

- Model menggunakan arsitektur LSTM dengan akurasi awal:
  - Accuracy: ± 83%
  - Evaluasi menggunakan `classification_report` dan confusion matrix

---

## 📁 Struktur Folder (opsional)

```
e-commerce-sentiment/
├── dataset-shopee-final.csv
├── train_lstm.py
├── model/
├── utils/
├── README.md
└── ...
```

---

## 🧑‍💻 Author

- **[@iceblessedtea](https://github.com/iceblessedtea)**  
Final project for *Natural Language Processing - Semester 6*

---
