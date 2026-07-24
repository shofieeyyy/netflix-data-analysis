# 🎬 Analisis Data Netflix

Analisis eksploratif (Exploratory Data Analysis) terhadap dataset Netflix Movies and TV Shows untuk menemukan tren konten, distribusi genre, negara produksi, rating, dan durasi film dari waktu ke waktu.

## 📌 Tentang Proyek

Proyek ini bertujuan untuk menggali insight dari katalog Netflix menggunakan Python, mulai dari data cleaning hingga visualisasi data. Analisis ini menjawab beberapa pertanyaan kunci:

- Bagaimana perbandingan jumlah Movie vs TV Show di Netflix?
- Bagaimana tren jumlah konten yang ditambahkan ke platform dari tahun ke tahun?
- Negara mana yang paling banyak memproduksi konten?
- Rating konten apa yang paling dominan?
- Genre apa yang paling populer?
- Bagaimana tren durasi film dari tahun ke tahun?

## 🗂️ Dataset

Dataset yang digunakan adalah **Netflix Movies and TV Shows** yang tersedia secara publik di [Kaggle]([[https://www.kaggle.com/code/ronikdedhia/netflix-titles/input]), berisi 8.807 judul dengan 12 kolom informasi seperti judul, sutradara, pemeran, negara, tanggal ditambahkan, rating, durasi, dan genre.

## 🛠️ Tools & Library

- **Python 3**
- **Google Colab** (environment analisis)
- **Pandas** — manipulasi & pembersihan data
- **Matplotlib** & **Seaborn** — visualisasi data

## 🔍 Alur Analisis

1. **Data Loading** — memuat dataset ke dalam DataFrame
2. **Data Cleaning**
   - Menangani missing values pada kolom `director`, `cast`, `country`
   - Mengonversi `date_added` menjadi tipe datetime
   - Memisahkan kolom `duration` menjadi `duration_minutes` (untuk Movie) dan `duration_seasons` (untuk TV Show)
3. **Exploratory Data Analysis (EDA)** — analisis komposisi konten, tren tahunan, negara produksi, rating, genre, dan durasi
4. **Visualisasi** — representasi visual dari setiap insight menggunakan pie chart, line chart, dan bar chart
5. **Kesimpulan & Rekomendasi**

## 📊 Key Findings

- Movie mendominasi katalog Netflix dibandingkan TV Show.
- Jumlah konten yang ditambahkan meningkat pesat menjelang 2019–2020.
- Amerika Serikat merupakan kontributor konten terbesar, diikuti oleh India dan Inggris.
- **TV-MA** adalah rating paling umum, menunjukkan Netflix banyak menyasar audiens dewasa.
- Drama Internasional dan Komedi menjadi genre yang paling sering muncul.
- Rata-rata durasi film menunjukkan tren **menurun** sejak tahun 2000-an, dari sekitar 120 menit menjadi sekitar 95 menit pada 2021, mengindikasikan pergeseran preferensi ke format film yang lebih ringkas.

## 📁 Struktur Repository

```
netflix-data-analysis/
├── netflix_data_analysis.ipynb   # Notebook analisis lengkap
├── netflix_titles.csv            # Dataset
├── README.md                     # Dokumentasi proyek
```

## 🚀 Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/shofieeyyy/netflix-data-analysis.git
   ```
2. Buka file `netflix_data_analysis.ipynb` menggunakan Jupyter Notebook atau Google Colab
3. Jalankan seluruh cell secara berurutan (Runtime > Run all)

## 👤 Kontak

Dibuat oleh **[Shofiyatul Fajriyah]**
- LinkedIn: [https://www.linkedin.com/in/shofiyatulfajriyah/]
- Email: [fajriyah144@gmail.com]

---
⭐ Jika proyek ini membantu atau menginspirasi, jangan ragu untuk memberi star pada repository ini!
