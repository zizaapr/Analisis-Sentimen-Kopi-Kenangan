# ☕ Analisis Sentimen Kopi Kenangan

Proyek ini bertujuan untuk melakukan **Analisis Sentimen** terhadap ulasan pelanggan Kopi Kenangan menggunakan teknik **Machine Learning** dengan algoritma **Support Vector Machine (SVM)**.

Analisis sentimen dilakukan untuk mengetahui apakah ulasan pelanggan termasuk ke dalam kategori:
- Positif 😊
- Negatif 😞
- Netral 😐

---

## 📌 Tujuan Project

- Mengumpulkan data ulasan Kopi Kenangan
- Melakukan preprocessing teks
- Melatih model Machine Learning
- Mengklasifikasikan sentimen pelanggan
- Mengevaluasi performa model

---

## 📂 Struktur Repository
Analisis-Sentimen-Kopi-Kenangan/
│
├── kopken_reviews.csv
├── scrapping_kopken.ipynb
├── SVMPelatihan_Model.ipynb
└── requirements.txt

---

### Penjelasan File:

- `scrapping_kopken.ipynb` → Digunakan untuk melakukan scraping dan pengumpulan data ulasan.
- `kopken_reviews.csv` → Dataset hasil scraping.
- `SVMPelatihan_Model.ipynb` → Notebook untuk preprocessing, training, dan evaluasi model SVM.
- `requirements.txt` → Daftar library yang dibutuhkan.

---

## 🧠 Algoritma yang Digunakan

- Support Vector Machine (SVM)
- TF-IDF Vectorizer
- Text Preprocessing (case folding, tokenizing, stopword removal, dll.)

---

## ⚙️ Cara Menjalankan Project

### 1️⃣ Clone Repository
```bash
git clone https://github.com/zizaapr/Analisis-Sentimen-Kopi-Kenangan.git
cd Analisis-Sentimen-Kopi-Kenangan
```

2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

3️⃣ Jalankan Jupyter Notebook
```bash
jupyter notebook
```

Buka dan jalankan:
1. scrapping_kopken.ipynb
2. SVMPelatihan_Model.ipynb

📊 Tahapan Analisis
1. Data Collection (Scraping)
2. Data Cleaning & Preprocessing
3. Feature Extraction (TF-IDF)
4. Split Data (Train & Test)
5. Training Model (SVM)
6. Evaluasi Model (Accuracy, Confusion Matrix)

📈 Evaluasi Model
Model dievaluasi menggunakan:
1. Accuracy
2. Classification Report
3. Confusion Matrix

🛠️ Tools & Library
1. Python
2. Pandas
3. Scikit-learn
4. NLTK
5. BeautifulSoup / Scraping tools
6. Matplotlib / Seaborn (untuk visualisasi)



