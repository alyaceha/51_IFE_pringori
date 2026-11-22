# Project Data Science

## Ringkasan Proyek
Proyek ini dibuat untuk memenuhi mata kuliah Praktikum Data Science yang bertujuan memprediksi harga kamera digital (USD) berdasarkan spesifikasinya menggunakan Linear Regression, Ridge, dan Lasso. Selain pemodelan regresi, proyek ini juga menggunakan K-Means dan Hierarchical Clustering untuk mengelompokkan kamera berdasarkan karakteristiknya. Linear Regression menghasilkan performa terbaik pada data test dengan RMSE 640,42 USD dan R² 0,369, dibandingkan baseline dengan RMSE 806,38 USD.

## Anggota dan Kontribusi
| Nama | NIM | Kontribusi |
|---|---|---|
| Nayla Cahaya Zahira | 123240024 | Business Understanding dan Data Understanding |
| Dzahabbia S. Anjani | 123240037 | EDA, pemeriksaan kualitas data, dan clustering |
| Alya Choirunnisa | 123240213 | Preprocessing, pemodelan regresi, tuning Ridge dan Lasso, dan pengelolaan repository |
| Nahdia Izzadina | 123240251 | Evaluasi, analisis kesalahan, kesimpulan, dan README |

## Sumber Data
1000 Cameras Dataset (Kaggle, pengguna crawford): https://www.kaggle.com/datasets/crawford/1000-cameras-dataset. Lisensi CC BY-SA 3.0. Diakses pada 22 November 2026. File yang dipakai adalah `camera_dataset.csv` (1.038 baris, 13 kolom).

## Cara Menjalankan
1. Pasang Python 3.10 atau lebih baru.
2. Pasang pustaka dengan perintah `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`.
3. Letakkan `camera_dataset.csv` dan notebook dalam satu folder.
4. Jalankan `jupyter notebook`, buka notebook `project_ds.ipynb`, lalu pilih Kernel, Restart & Run All.
