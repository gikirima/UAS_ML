# 📊 Berita Clustering dengan IndoBERT + KMeans

Proyek ini melakukan ekstraksi fitur dari berita berbahasa Indonesia menggunakan model `indobenchmark/indobert-base-p1`, lalu mengelompokkan artikel berita berdasarkan kemiripan semantik menggunakan algoritma KMeans. Setelah clustering, dilakukan analisis frekuensi kata dari setiap kluster untuk memahami topik dominan.

---

## 🧩 Fitur Utama

- 🧼 **Pembersihan Teks** dari sumber berita seperti Liputan6, TurnBackHoax, Kompas, Fimela, dll.
- 🔍 **Ekstraksi Embeddings** dari judul dan isi berita menggunakan IndoBERT
- 🧠 **KMeans Clustering** berdasarkan gabungan embedding judul dan isi
- 📉 **Penentuan Jumlah Kluster Optimal** dengan metode Elbow
- 📚 **Analisis Frekuensi Kata Terbanyak** per kluster


---

## 🛠️ Instalasi

Pastikan Python 3.8+ telah terinstal. Kemudian jalankan:

```bash
pip install transformers torch scikit-learn pandas tqdm matplotlib nltk kneed
