<div align="center">

# 🏡 California Housing Regression Engine
### *Advanced Machine Learning Pipeline & Predictive API*

[![Python](https://img.shields.io/badge/Python-3.11%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Model-orange?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Flask](https://img.shields.io/badge/Flask-API-black?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
🏡 California Housing Regression Project
Proyek Machine Learning ini dikembangkan untuk memprediksi nilai median perumahan berdasarkan dataset California Housing yang mencakup 20.640 baris data statistik riil.

📊 Alur Kerja Proyek (Pipeline)
Data Preprocessing: Memuat dataset, menangani nilai kosong, serta memastikan kualitas data.
Data Splitting: Membagi dataset menjadi data latih (train) dan data uji (test) secara proporsional.
Model Training: Melatih beberapa algoritma regresi untuk perbandingan performa:
Least Angle Regression (LARS)
Linear Regression
Gradient Boosting Regressor (GBR)
Model Evaluation: Menguji akurasi model menggunakan metrik regresi standar:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared Score (
R
2
)
Model Saving: Menyimpan model terbaik yang telah dilatih ke dalam format .joblib dan .pkl agar dapat digunakan kembali.
💻 Cara Menjalankan Proyek
Pastikan pustaka Python berikut sudah terinstal di lingkungan kamu:
pip install pandas scikit-learn seaborn matplotlib joblib
About

Proyek Machine Learning regresi menggunakan dataset California Housing (20.640 baris). Mencakup data splitting (train/test), pelatihan model (Lars, Linear Regression, Gradient Boosting), evaluasi performa (MAE, MSE, $R^2$), hingga penyimpanan model akhir dengan joblib.

Resources
Readme
Activity
Stars
0 stars
Watchers
0 watching
Forks
0 forks
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Contributors
1
 (1)
@ariyandririsky
ariyandririsky
Languages
Jupyter Notebook
100%
---

## 📊 Alur Kerja Sistem (*Pipeline*)

Proyek ini dibangun melalui tahapan sistematis untuk memastikan kualitas performa model yang optimal:

1. **Data Preprocessing & Cleaning**: Memuat dataset mentah, menangani nilai kosong atau anomali, serta memastikan kualitas data siap diolah.
2. **Data Splitting**: Membagi dataset secara proporsional ke dalam porsi data latih (*train*) dan data uji (*test*).
3. **Model Training & Comparison**: Melatih dan membandingkan performa dari beberapa algoritma regresi unggulan:
   - *Least Angle Regression* (**LARS**)
   - *Linear Regression*
   - *Gradient Boosting Regressor* (**GBR**)
4. **Model Evaluation**: Menguji akurasi model menggunakan metrik evaluasi regresi standar:
   - *Mean Absolute Error* (**MAE**)
   - *Mean Squared Error* (**MSE**)
   - *R-squared Score* (**$R^2$**)
5. **Model Persistence**: Menyimpan model terbaik yang telah dilatih ke dalam format berkas `.joblib` dan `.pkl` agar dapat digunakan kembali secara fleksibel.

---

<div align="center">
  <i>Dokumentasi Proyek Eksplorasi Machine Learning & Deployment. 🚀</i>
</div>
