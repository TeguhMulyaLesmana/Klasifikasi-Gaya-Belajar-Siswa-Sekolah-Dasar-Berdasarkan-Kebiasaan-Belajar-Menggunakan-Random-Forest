# Klasifikasi Gaya Belajar Siswa Sekolah Dasar Berdasarkan Kebiasaan Belajar Menggunakan Random Forest

## Deskripsi
Project ini merupakan implementasi metode **Random Forest** untuk melakukan klasifikasi gaya belajar siswa sekolah dasar berdasarkan pola kebiasaan belajar siswa. Sistem ini mengklasifikasikan siswa ke dalam tiga kategori gaya belajar, yaitu:

- Visual
- Auditori
- Kinestetik

Penelitian ini bertujuan untuk membantu guru dan peneliti dalam memahami karakteristik belajar siswa sehingga proses pembelajaran dapat disesuaikan dengan gaya belajar masing-masing siswa.

---

## Latar Belakang
Setiap siswa memiliki gaya belajar yang berbeda-beda. Identifikasi gaya belajar secara manual membutuhkan waktu dan observasi yang cukup panjang. Oleh karena itu, pada penelitian ini digunakan algoritma machine learning **Random Forest** untuk membantu proses klasifikasi gaya belajar berdasarkan data kebiasaan belajar siswa.

---

## Metode yang Digunakan
Algoritma yang digunakan pada project ini adalah:

- Random Forest Classifier
- Data Preprocessing
- Label Encoding
- Train Test Split
- Evaluasi menggunakan Accuracy Score dan Confusion Matrix

---

## Dataset
Dataset diperoleh dari hasil pengumpulan data menggunakan Google Form yang berisi kebiasaan belajar siswa sekolah dasar.

### Contoh atribut:
- Cara memahami pelajaran
- Kebiasaan saat belajar
- Preferensi media belajar
- Aktivitas saat menghafal
- Respon terhadap instruksi guru

### Target klasifikasi:
- Visual
- Auditori
- Kinestetik

---

## Tools dan Teknologi
Project ini menggunakan:

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Struktur Project

```bash
Klasifikasi-Gaya-Belajar/
│
├── dataset/
│   └── dataset.csv
│
├── model/
│   └── random_forest_model.pkl
│
├── notebook/
│   └── klasifikasi_gaya_belajar.ipynb
│
├── output/
│   ├── confusion_matrix.png
│   └── hasil_prediksi.csv
│
├── README.md
└── requirements.txt
