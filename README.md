# MLOps - Twitter Sentiment Analysis Amanda Brownies

## Deskripsi Proyek

Proyek ini bertujuan untuk membangun sistem **analisis sentimen pada percakapan pengguna di platform X (Twitter)** yang berkaitan dengan brand **Amanda Brownies**. Sistem ini menggunakan pendekatan **Machine Learning** untuk mengklasifikasikan tweet ke dalam tiga kategori sentimen yaitu **positif, netral, dan negatif**.

Proyek ini juga menerapkan konsep **MLOps (Machine Learning Operations)** agar proses pengembangan model dapat berjalan secara terstruktur, reproducible, dan mudah dikembangkan di lingkungan kolaboratif.

Lingkungan pengembangan proyek ini menggunakan **GitHub Codespaces** sehingga seluruh dependensi dan konfigurasi dapat dijalankan secara konsisten oleh siapa pun yang mengakses repository ini.

---

## Tujuan Proyek

Tujuan dari proyek ini adalah:

* Membangun sistem klasifikasi sentimen terhadap tweet yang membahas Amanda Brownies
* Menerapkan praktik **MLOps** dalam pengembangan proyek Machine Learning
* Menyediakan lingkungan pengembangan yang **reproducible** menggunakan GitHub Codespaces
* Mengelola eksperimen model menggunakan **GitHub Flow**

---

## Struktur Direktori Proyek

Repository ini menggunakan struktur proyek yang terinspirasi dari **Cookiecutter Data Science**.

```
MLOps-TwitterSentimentAmandaBrownies
│
├── data
│   ├── raw            # Data mentah dari Twitter
│   └── processed      # Data yang sudah dibersihkan / diproses
│
├── models             # Penyimpanan model machine learning
│
├── notebooks          # Notebook untuk eksplorasi data dan eksperimen
│
├── src
│   ├── data           # Script pengambilan dan pemrosesan data
│   ├── features       # Feature engineering
│   ├── models         # Training dan evaluasi model
│   └── visualization  # Visualisasi data
│
├── config             # File konfigurasi proyek
│
├── README.md          # Dokumentasi proyek
├── requirements.txt   # Daftar library Python
└── .gitignore
```

---

## Teknologi yang Digunakan

Beberapa teknologi yang digunakan dalam proyek ini:

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook
* GitHub Codespaces
* GitHub Flow

---

## Cara Menjalankan Proyek Menggunakan GitHub Codespaces

Proyek ini dirancang agar dapat dijalankan langsung melalui **GitHub Codespaces**.

Langkah-langkah:

1. Buka repository ini di GitHub
2. Klik tombol **Code**
3. Pilih tab **Codespaces**
4. Klik **Create Codespace on main**
5. Tunggu hingga environment selesai dibuat

Setelah environment aktif, kamu dapat langsung menjalankan kode Python dan melakukan eksperimen machine learning.

---

## Branching Strategy (GitHub Flow)

Proyek ini menggunakan strategi **GitHub Flow** untuk pengelolaan kode.

Alur pengembangan:

1. Branch utama: `main`
2. Branch fitur/eksperimen dibuat dari `main`

Contoh:

```
feat/initial-eda
```

3. Pengembangan dilakukan pada branch tersebut
4. Setelah selesai dan divalidasi, perubahan akan digabungkan ke `main` melalui **Pull Request**

---

## Eksperimen Awal

Eksperimen awal dilakukan pada branch:

```
feat/initial-eda
```

Eksperimen ini berfokus pada:

* eksplorasi dataset
* analisis distribusi sentimen
* persiapan pipeline data untuk model machine learning

---

## Pengembangan Selanjutnya

Tahapan pengembangan proyek selanjutnya meliputi:

* Data collection dari Twitter
* Text preprocessing
* Feature extraction
* Model training
* Evaluasi model
* Deployment pipeline MLOps

---

## Lisensi

Proyek ini menggunakan lisensi **MIT License**.
