# Analisis Retensi Pengguna G-Tech Academy

## 📌 Deskripsi Proyek
Proyek ini merupakan simulasi analisis data dunia nyata untuk **G-Tech Academy**, sebuah platform edukasi teknologi. Fokus utama analisis ini adalah memahami perilaku pengguna, mengidentifikasi fitur yang paling diminati, dan memberikan rekomendasi strategis untuk meningkatkan retensi (keaktifan) pengguna.

Analisis ini menggunakan pendekatan **Data-Driven Decision Making** dengan memproses data aktivitas pengguna yang mencakup durasi belajar, preferensi fitur, dan skor kepuasan.

## 🛠️ Alur Kerja (Workflow)
1.  **Data Preparation**: Pembuatan dataset yang merepresentasikan aktivitas nyata (User ID, Durasi, Fitur, dan Skor Kepuasan).
2.  **Data Cleaning**: 
    - Penanganan *Missing Values* (NaN) pada skor kepuasan secara transparan.
    - Pemilihan metrik **Median** untuk menangani pencilan (*outliers*) pada durasi belajar.
3.  **Exploratory Data Analysis (EDA)**: 
    - Analisis distribusi penggunaan fitur.
    - Perbandingan efektivitas fitur Video vs Forum vs Kuis.
4.  **Visualisasi Data**: Menggunakan Bar Chart dan Pie Chart untuk memperkuat argumen analisis.
5.  **Insight & Rekomendasi**: Menyusun solusi bisnis konkret berbasis temuan data.

## 📊 Temuan Utama
- **Standar Keaktifan**: Rata-rata durasi belajar (Mean) sebesar 55 menit dianggap bias. **Median (37.5 menit)** dipilih sebagai representasi yang lebih jujur.
- **Dominasi Fitur**: Fitur **Video** adalah "magnet" utama bagi pengguna (50% penggunaan) dengan durasi terlama.
- **Analisis Fitur Pendek**: Fitur **Forum** memiliki durasi singkat namun esensial bagi pengguna yang menyukai metode belajar tekstual/cepat.
- **Isu Feedback**: Ditemukan 3 user yang tidak mengisi rating, mengindikasikan perlunya perbaikan sistem pengumpulan feedback.

## 💡 Rekomendasi Bisnis
1.  **Strategi Integrasi (Cross-Feature)**: Menambahkan sesi otomatis Forum atau Kuis singkat setelah video berakhir untuk meningkatkan eksplorasi fitur.
2.  **Pengembangan Fitur**: Meningkatkan interaktivitas pada fitur Forum dan Kuis tanpa menghilangkan kemudahannya.
3.  **Monitoring Prospektif**: Memantau tren penggunaan fitur pasca-pengembangan sebelum memutuskan keberlangsungan fitur tertentu.

## 🚀 Teknologi yang Digunakan
- **Bahasa**: Python
- **Library**: Pandas, NumPy, Matplotlib
- **Tool**: Jupyter Notebook / VS Code
