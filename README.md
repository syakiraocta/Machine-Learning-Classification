Klasifikasi Machine Learning: Social Network Ads
Repositori ini memuat implementasi algoritma klasifikasi guna memprediksi potensi pembelian produk berdasarkan profil pengguna. Analisis dilakukan terhadap variabel umur dan estimasi gaji dengan memanfaatkan dataset Social Network Ads sebagai bagian dari tugas mata kuliah Machine Learning.

📂 Struktur Repositori
Source_Code/: Menyimpan file notebook asli dari materi perkuliahan (K-Nearest Neighbors, Naive Bayes, dan Decision Tree).

KNN.ipynb: Menampilkan implementasi algoritma K-NN yang telah melalui proses modifikasi mandiri untuk optimasi hasil prediksi.

Social_Network_Ads.csv: Menyediakan dataset referensi yang digunakan dalam seluruh proses pemodelan.

🛠️ Pengembangan & Modifikasi K-NN
Proses pengembangan pada file KNN.ipynb melibatkan beberapa langkah optimasi dan penguatan dokumentasi:

Melakukan Hyperparameter Tuning: Mengubah nilai n_neighbors menjadi 7 guna menghasilkan decision boundary yang lebih stabil serta meminimalisir risiko overfitting.

Menyusun Dokumentasi Logika: Melengkapi setiap tahapan (Step 1 hingga Step 8) dengan penjelasan menggunakan kata kerja aktif guna memperjelas alur kerja dari preprocessing hingga tahap evaluasi.

Melaksanakan Evaluasi Model: Menyajikan Confusion Matrix serta perhitungan skor akurasi secara eksplisit untuk memberikan gambaran performa model yang transparan.

📊 Visualisasi Keputusan
Hasil pemodelan menghasilkan visualisasi Decision Boundary yang memetakan klasifikasi secara spasial:

Area Merah: Menunjukkan kelompok pengguna yang diprediksi tidak melakukan pembelian.

Area Hijau: Menunjukkan kelompok pengguna yang diprediksi akan melakukan pembelian.
