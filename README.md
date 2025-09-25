**Satria Data 2024 - Klasifikasi Teks Multi Kelas dalam Tweet untuk Pemilihan Presiden Indonesia 2024**

---

<!-- <img src="https://satriadata.kemdikbud.go.id/wp-content/uploads/2024/05/logo-24.png" alt="SATRIA DATA 2024" width="300"/> -->

---

Selamat datang di repositori Personal Satria Data 2024! Proyek ini bertujuan untuk melakukan klasifikasi teks multi kelas pada tweet yang berkaitan dengan Pemilihan Presiden Indonesia 2024. Dengan menggunakan teknik Pemrosesan Bahasa Alami (NLP), BERT, dan atau pembelajaran mesin, kita akan mengkategorikan tweet berdasarkan sentimen, kandidat, dan topik yang relevan, menggunakan label Astagatra.

---

### Tentang Proyek

Proyek ini fokus pada pengumpulan dan analisis tweet yang berkaitan dengan Pemilihan Presiden Indonesia 2024. Kami akan menggunakan berbagai teknik NLP untuk mengklasifikasikan tweet ke dalam beberapa kategori Astagatra, seperti:

- Demografi
- Ekonomi
- Geografi
- Ideologi
- Pertahanan dan Keamanan
- Politik
- Sosial Budaya
- Sumber Daya Alam

---

### Tujuan

- **Klasifikasi Multi Kelas**: Mengembangkan model untuk mengklasifikasikan tweet ke dalam beberapa kategori berdasarkan sentimen, kandidat, dan topik.
- **Analisis Wacana Publik**: Memahami bagaimana publik berbicara tentang para kandidat dan isu-isu yang relevan dalam pemilihan presiden.
- **Visualisasi Data**: Menyajikan hasil analisis dalam bentuk visualisasi yang mudah dipahami.

---

### Struktur Repositori

```
├── data/
│   └── tweets.csv
├── notebooks/
│   ├── 0. Augmentasi Data Text.ipynb
│   ├── 0. Latest - Augmentasi Data Text.ipynb
│   ├── 0. Model Inference to Testing Dataset.ipynb
│   ├── 1. Processing of Tweets related to the 2024 Presidential Election.ipynb
│   ├── 2. CatBoost Model For Multi Classification Tweets 2024 Presidential Election.ipynb
│   ├── 3. IndoBERTweet Fine Tune Setelah Mentoring kak Bryan.ipynb
│   ├── 4. LSTM For Multi Classification Tweets 2024 Presidential Election.ipynb
│   ├── 5. Distilbert_base_indonesian_For_Multi_Classification_Tweets_2024_Presidential_Election.ipynb
│   ├── 6. [Salah] Latest Training IndoBERTweet (Data augmentasi masuk ke data validasi).ipynb
│   ├── 7. [Salah] Latest Training Distilbert_base_indonesian (Data augmentasi masuk ke data validasi).ipynb
│   ├── 8. Distilbert-base-indonesian [Augmented Data] K-fold Method.ipynb
│   ├── 9. IndoBERTweet [Augmented Data] K-fold Method.ipynb
│   ├── 10. IndoBERTweet [Unbalanced][Latest Processing Data] K-fold Method.ipynb
│   ├── Baru - 1.ipynb
│   ├── Baru - 2.ipynb
│   ├── Baru - 3.ipynb
│   ├── Combine Submissions.ipynb
├── README.md
├── requirements.txt
├── Augmented Data/
├── Corpus by TimTam/
```

---

### Memulai

1. **Klon Repositori**:
   ```
   git clone https://github.com/your_username/Satria-Data-2024.git
   ```

2. **Pasang Dependensi**:
   ```
   pip install -r requirements.txt
   ```

3. **Jelajahi Notebook**:
   - `0. Augmentasi Data Text.ipynb`: Melakukan augmentasi data untuk memperbesar dataset.
   - `0. Latest - Augmentasi Data Text.ipynb`: Augmentasi data terbaru.
   - `0. Model Inference to Testing Dataset.ipynb`: Menerapkan model ke dataset pengujian.
   - `1. Processing of Tweets related to the 2024 Presidential Election.ipynb`: Memproses data tweet yang berkaitan dengan Pemilihan Presiden Indonesia 2024.
   - `2. CatBoost Model For Multi Classification Tweets 2024 Presidential Election.ipynb`: Membangun model CatBoost untuk klasifikasi multi kelas pada tweet.
   - `3. IndoBERTweet Fine Tune Setelah Mentoring kak Bryan.ipynb`: Fine-tuning model IndoBERTweet.
   - `4. LSTM For Multi Classification Tweets 2024 Presidential Election.ipynb`: Membangun model LSTM untuk klasifikasi multi kelas pada tweet.
   - `5. Distilbert_base_indonesian_For_Multi_Classification_Tweets_2024_Presidential_Election.ipynb`: Membangun model DistilBERT base Indonesian untuk klasifikasi multi kelas pada tweet.
   - `8. Distilbert-base-indonesian [Augmented Data] K-fold Method.ipynb`: Menerapkan metode K-fold pada data yang di-augmentasi menggunakan DistilBERT base Indonesian.
   - `9. IndoBERTweet [Augmented Data] K-fold Method.ipynb`: Menerapkan metode K-fold pada data yang di-augmentasi menggunakan IndoBERTweet.
   - `10. IndoBERTweet [Unbalanced][Latest Processing Data] K-fold Method.ipynb`: Menerapkan metode K-fold pada data yang tidak seimbang menggunakan IndoBERTweet.

4. **Jalankan Kode**:
   - Mulai dengan notebook di direktori `notebooks/` untuk memahami alur analisis dan membangun model klasifikasi.

---

### Kategori dan Jumlah Data

nb: Data tidak disertakan, karena bersifat pribadi milik pihak penyelenggara acara Satria Data 2024
Berikut adalah kategori label Astagatra dan jumlah data yang tersedia dalam setiap kategori:

| Encoded | Label                     | Count |
|---------|---------------------------|-------|
| 0       | Demografi                 | 62    |
| 1       | Ekonomi                   | 367   |
| 2       | Geografi                  | 20    |
| 3       | Ideologi                  | 400   |
| 4       | Pertahanan dan Keamanan   | 400   |
| 5       | Politik                   | 2972  |
| 6       | Sosial Budaya             | 587   |
| 7       | Sumber Daya Alam          | 192   |

---

### Pedoman Kontribusi

Kontribusi untuk meningkatkan analisis, mengembangkan model yang lebih baik, atau memperbaiki dokumentasi sangat disambut! Jika Anda menemukan masalah atau memiliki saran, silakan buka isu atau kirimkan pull request.

---

### Pengakuan

Terima kasih kepada semua kontributor dan komunitas yang mendukung proyek ini.

---

### Informasi Kontak

Untuk pertanyaan atau kolaborasi, silakan hubungi [rendikarendi96@gmail.com](mailto:rendikarendi96@gmail.com).

---

Mari kita analisis percakapan publik tentang Pemilihan Presiden Indonesia 2024 bersama-sama! 🗳️🇮🇩
