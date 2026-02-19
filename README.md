# ml-foundations-series

**Machine Learning Foundations: From Linear Models to Ensembles**
📌 **Overview**

Repositori ini adalah jurnal teknis perjalanan belajar saya dalam menguasai Machine Learning menggunakan ekosistem Python. Di sini, saya mengimplementasikan berbagai algoritma untuk menyelesaikan tantangan prediksi yang berbeda, mulai dari estimasi nilai numerik hingga klasifikasi cuaca.

📁 **Struktur Pembelajaran**

1. Estimating Medical Charges (Linear Regression)
    - File: Lesson1.ipynb
    - Topik: Regresi Linear & Gradient Descent.
    - Analisis: Memprediksi biaya premi asuransi berdasarkan variabel demografi. Menunjukkan pemahaman dasar tentang loss function (RMSE).

2. Australian Rain Prediction (Logistic Regression)
    - File: Lesson2.ipynb
    - Topik: Klasifikasi Biner & Data Preprocessing.
    - Analisis: Membangun baseline model untuk prediksi cuaca dengan fokus pada penanganan data hilang dan normalisasi fitur.

3. Advanced Weather Classification (Decision Trees & Random Forests)
    - File: Lesson3.ipynb
    - Topik: Ensemble Learning & Overfitting.
    - Analisis: Meningkatkan performa prediksi hujan di Australia menggunakan model berbasis pohon. Proyek ini mendemonstrasikan kemampuan dalam:
        - Visualisasi struktur pohon keputusan.
        - Hyperparameter tuning (max depth, leaf nodes) untuk mengatasi overfitting.
        - Implementasi Random Forest untuk meningkatkan akurasi dan stabilitas model.

🛠️ **Tech Stack & Data**

- Core: Scikit-Learn, Pandas, NumPy.
- Viz: Seaborn, Matplotlib, Graphviz (untuk visualisasi pohon).
- Data Management: Menggunakan format Parquet untuk efisiensi transfer data antar modul.
