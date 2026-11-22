# Project Data Science
## Anggota dan Kontribusi
| Nama | NIM | Kontribusi |
|---|---|---|
| Nayla Cahaya Zahira | 123240024 | Business Understanding dan Data Understanding |
| Dzahabbia S. Anjani | 123240037 | EDA, pemeriksaan kualitas data, dan clustering |
| Alya Choirunnisa | 123240213 | Preprocessing, pemodelan regresi, tuning Ridge dan Lasso, dan pengelolaan repository |
| Nahdia Izzadina | 123240251 | Evaluasi, analisis kesalahan, kesimpulan, dan README |


## Ringkasan Proyek
Proyek akhir Praktikum Data Science 2026/2027, Informatika UPN "Veteran" Yogyakarta. Proyek ini memprediksi harga kamera digital (USD) dari spesifikasinya dengan regresi (Linear Regression, Ridge, dan Lasso). Sebagai tambahan, kamera dikelompokkan dengan clustering (K-Means dan Hierarchical). Model terbaik adalah Linear Regression dengan RMSE 640,42 USD dan R² 0,369 pada data test, sedangkan baseline memiliki RMSE 806,38 USD.

## Sumber Data
1000 Cameras Dataset (Kaggle, pengguna crawford): https://www.kaggle.com/datasets/crawford/1000-cameras-dataset. Lisensi CC BY-SA 3.0. Diakses pada 22 November 2026. File yang dipakai adalah `camera_dataset.csv` (1.038 baris, 13 kolom).

## Cara Menjalankan
1. Pasang Python 3.10 atau lebih baru.
2. Pasang pustaka dengan perintah `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`.
3. Letakkan `camera_dataset.csv` dan notebook dalam satu folder.
4. Jalankan `jupyter notebook`, buka notebook `project_ds.ipynb`, lalu pilih Kernel, Restart & Run All.

## Referensi
1. Huguet, C. (2018). 1000 Cameras Dataset [Data set]. Kaggle. https://www.kaggle.com/datasets/crawford/1000-cameras-dataset
2. Chapman, P., Clinton, J., Kerber, R., Khabaza, T., Reinartz, T., Shearer, C., & Wirth, R. (2000). CRISP-DM 1.0: Step-by-step data mining guide. SPSS Inc.
3. Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., et al. (2011). Scikit-learn: Machine learning in Python. Journal of Machine Learning Research, 12, 2825-2830.
