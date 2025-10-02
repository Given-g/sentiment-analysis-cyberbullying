# Sentiment Analysis Cyberbullying (Instagram Comments)

Proyek ini bertujuan untuk **mendeteksi sentimen dan potensi cyberbullying** pada komentar Instagram menggunakan pendekatan **Natural Language Processing (NLP)** dan **Machine Learning**.

---

## 📂 Struktur Project
```
Sentiment-Cyberbullying/
│── data/
│   ├── dataset_komentar_instagram_cyberbullying.csv   # Dataset asli
│   └── cleaned_cyberbullying_dataset.csv              # Dataset setelah preprocessing
│
│── notebooks/
│   └── Sentiment CyberBullying.ipynb                  # Notebook utama analisis
│
│── requirements.txt                                   # Library yang dibutuhkan
│── README.md                                          # Dokumentasi project
│── .gitignore                                         # File yang diabaikan Git
```

---

## 📊 Dataset
- **Sumber**: Komentar Instagram (labelled cyberbullying / non-cyberbullying).
- **Ukuran**: ± [isi sesuai jumlah baris dataset kamu].
- **Atribut utama**:
  - `text` → komentar Instagram
  - `label` → kategori (cyberbullying / non-cyberbullying)

---

## 🔎 Langkah Analisis
1. **Preprocessing Data**
   - Case folding
   - Tokenisasi
   - Stopwords removal
   - Stemming

2. **Feature Extraction**
   - TF-IDF Vectorizer

3. **Modeling**
   - Algoritma Machine Learning (contoh: Logistic Regression, SVM, Naive Bayes).
   - Evaluasi menggunakan akurasi, precision, recall, f1-score.

4. **Hasil**
   - LogisticRegression mencapai akurasi 95% pada dataset uji.*

---

## 🚀 Cara Menjalankan
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/Sentiment-Cyberbullying.git
   cd Sentiment-Cyberbullying
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Buka notebook:
   ```bash
   jupyter notebook notebooks/Sentiment\ CyberBullying.ipynb
   ```

---

## 📌 Requirements
Library utama:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- nltk
- sastrawi
- maleo


Semua library sudah dicantumkan di `requirements.txt`.

---

## ✨ Author
- Given Glorious
- 
