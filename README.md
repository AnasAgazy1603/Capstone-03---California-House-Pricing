🏡 California House Price Prediction with Random Forest & LightGBM
Proyek ini merupakan bagian dari tugas akhir Capstone Project yang bertujuan untuk memprediksi harga rumah di California berdasarkan berbagai fitur seperti jumlah kamar, luas bangunan, lokasi, dan lain sebagainya. Proyek ini mengimplementasikan dua algoritma machine learning utama, yaitu Random Forest dan LightGBM, untuk membandingkan performa prediksi serta kemampuan generalisasi masing-masing model.

🔄 Alur Proyek
1. Data Collection
Dataset yang digunakan adalah data_california_house.csv, berisi data harga rumah dan atribut-atribut terkait properti di California.

2. Data Preprocessing
  - Pembersihan data dari missing values dan outlier
  - Encoding fitur kategorikal (jika ada)
  - Normalisasi/skaling data numerik
  - Feature engineering untuk meningkatkan kualitas input model

3. Eksperimen Model
  - Menggunakan teknik Gradient-based One-Side Sampling (GOSS) dan Exclusive Feature Bundling (EFB)
  - Mencapai MAE ≈ $32,514 dan R² ≈ 82% pada data test
  - Menunjukkan performa stabil dan kemampuan generalisasi yang baik

4. Evaluasi
  - Metrik yang digunakan: MAE, RMSE, dan R²
  - Dilakukan evaluasi pada data train dan test untuk memastikan tidak terjadi overfitting
  - Visualisasi residual, distribusi error, dan korelasi fitur dilakukan untuk interpretabilitas

5. Kesimpulan
  - Random Forest menunjukkan performa prediksi terbaik pada data ini, terutama dalam hal akurasi dan generalisasi.
  - LightGBM tetap menjadi pilihan solid untuk efisiensi dan stabilitas model, terutama dalam skenario data besar dan kompleks.

📁 Struktur File
  - JCDS_0610_Capstone_3_Anas_Putra_Agazy.ipynb - Notebook utama berisi seluruh proses analisis, modeling, dan evaluasi.
  - data_california_house.csv - Dataset properti California.

⚙️ Tools & Libraries
  - Python
  - Pandas, Numpy
  - Scikit-Learn
  - LightGBM
  - Matplotlib, Seaborn

📌 Catatan
Proyek ini berfokus pada pendekatan supervised learning untuk regresi. Ke depannya, model dapat dioptimalkan lebih lanjut dengan:
  - Hyperparameter tuning yang lebih dalam
  - Feature selection menggunakan teknik lain (misal: Recursive Feature Elimination)
  - Menguji model pada data dari negara bagian lain
