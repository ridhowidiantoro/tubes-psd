
# 🔍 TUBES PSD  Scraping & Analisis Topik + Sentimen Energi Baru dan Terbarukan (EBT) di Media Sosial X (Twitter)

## 📘 Deskripsi Singkat

Repositori ini merupakan proyek tugas besar mata kuliah *Pengantar Sains Data* (PSD) oleh **Kelompok 12** yang berfokus pada scraping data dan analisis topik serta sentimen publik terhadap isu **Energi Baru dan Terbarukan (EBT)** di media sosial **X (Twitter)**.

---

## 📁 Struktur Repositori

```
tubes-psd/
├── hasil-scraping-NRE-X.csv         # Dataset hasil scraping Twitter
├── nre-analysis.ipynb               # Notebook analisis topik & sentimen
├── FINALPROJECT_TUBES_KELOMPOK12.pdf # Laporan akhir proyek
```

---

## 🎯 Tujuan Proyek

1. Mengambil data Twitter terkait isu EBT.
2. Membersihkan data dan menyiapkan untuk analisis.
3. Melakukan analisis **topik** menggunakan model LDA.
4. Melakukan analisis **sentimen** untuk mengklasifikasikan opini publik.
5. Menyajikan hasil dalam bentuk visualisasi.

---

## ⚙️ Tools & Library

- Python (Jupyter Notebook)
- `snscrape` untuk scraping data Twitter
- `pandas`, `numpy` untuk analisis data
- `nltk`, `gensim`, `sklearn` untuk NLP dan model LDA
- `TextBlob` untuk analisis sentimen
- `matplotlib`, `seaborn`, `wordcloud` untuk visualisasi

---

## 🧪 Alur Analisis

### 1. Scraping Data
- Menggunakan `snscrape`
- Keyword: `"energi terbarukan" OR "new renewable energy" OR "EBT"`
- Output CSV berisi: tanggal, username, isi tweet

### 2. Pembersihan Teks
- Menghapus URL, mention, hashtag, emoji, dan tanda baca
- Tokenisasi dan stopword removal

### 3. Analisis Topik
- Menggunakan LDA (Latent Dirichlet Allocation)
- Visualisasi dengan `pyLDAvis`
- Menampilkan topik utama percakapan publik

### 4. Analisis Sentimen
- Menggunakan `TextBlob` untuk klasifikasi sentimen (positif, negatif, netral)
- Visualisasi distribusi sentimen

---

## 📊 Hasil Utama

- **Topik Dominan**: transisi energi, kebijakan pemerintah, PLTS, kendaraan listrik
- **Sentimen**: Mayoritas positif terutama pada isu energi surya & kendaraan listrik

---

## 🧑‍💻 Tim Pengembang

**Kelompok 12 - Tugas Besar PSD**

---

## 📄 Lisensi

Proyek ini dibuat untuk tujuan akademik dan pembelajaran.

