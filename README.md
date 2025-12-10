# Sentiment Analysis Google Review

Analisis keluhan konsumen pada Google Maps untuk dealer dan bengkel motor menggunakan Python dan teknik Natural Language Processing (NLP).

## Deskripsi
Repositori ini berisi notebook analisa data ulasan Google Maps, fokus pada review negatif untuk mengidentifikasi penyebab utama keluhan pelanggan. Analisis dilakukan menggunakan bigram & trigram, serta visualisasi data.

## Fitur Utama
- Membersihkan data ulasan dan menghapus stopwords Bahasa Indonesia
- Mengelompokkan review negatif (rating ≤ 3)
- Analisis bigram & trigram untuk mendeteksi frasa keluhan utama
- Visualisasi: grafik 10 besar keluhan dan tempat dengan review negatif terbanyak
- Rekap temuan dan saran perbaikan

## Struktur Proyek
```
.
├── Sentiment_Analysis_Review_Google_Maps.ipynb     # Notebook utama analisis
├── google_maps_reviews.csv                         # Data ulasan mentah
├── README.md
```

## Cara Menjalankan
1. **Clone repo**
    ```bash
    git clone https://github.com/ariefbsusilo/Sentiment-Analysis-Google-Review.git
    cd Sentiment-Analysis-Google-Review
    ```
2. **Persiapkan data**
    - Pastikan file google_maps_reviews.csv sudah ada dan sesuai format.
    - Kolom yang dibutuhkan: `Nama Tempat`, `rating`, `teks_ulasan`
3. **Buka notebook**
    - Dapat dibuka di Jupyter Notebook lokal, VSCode, atau [Google Colab](https://colab.research.google.com/github/ariefbsusilo/Sentiment-Analysis-Google-Review/blob/main/Sentiment_Analysis_Review_Google_Maps.ipynb)
4. **Jalankan kode**
    - Ikuti instruksi pada tiap cell untuk mendapatkan hasil analisa dan visualisasi.

## Hasil Temuan
- Dealer dengan review negatif tertinggi:  
  - Yamaha Harpindo Jaya
  - Yamaha Donny’s Motor Tingkir
  - Yamaha Sumber Baru Motor Ambarukmo
  - (lihat detail di notebook)
- Contoh keluhan utama:  
  - Proses beli motor
  - Pengurusan dokumen (STNK, BPKB)
  - Kualitas dan kecepatan layanan servis

## Dependensi
- python >= 3.6
- pandas
- matplotlib
- seaborn
- scikit-learn

Instalasi:
```python
!pip install pandas matplotlib seaborn scikit-learn
```

## Insight & Saran
- Rekomendasi perbaikan layanan untuk dealer dengan tingkat keluhan tertinggi
- Peninjauan proses dokumen dan pembelian motor di tempat terkait

## Referensi
- [Notebook Google Colab](https://colab.research.google.com/github/ariefbsusilo/Sentiment-Analysis-Google-Review/blob/main/Sentiment_Analysis_Review_Google_Maps.ipynb)
- Data review: hasil ekstraksi Google Maps

---

Silakan edit sesuai kebutuhan!