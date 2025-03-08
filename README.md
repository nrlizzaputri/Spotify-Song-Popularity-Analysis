# Spotify-Song-Popularity-Analysis

**Tentang Kumpulan Data ini:** 
Netflix adalah salah satu platform
media dan streaming video terpopuler. Mereka memiliki lebih
dari 8 ribu film atau acara TV yang tersedia di platform mereka,
hingga pertengahan tahun 2024, mereka memiliki lebih dari 282
juta Pelanggan di seluruh dunia. Kumpulan data tabular ini terdiri
dari daftar semua film dan acara TV yang tersedia di Netflix,
beserta detail seperti - pemeran, sutradara, rating, tahun rilis,
durasi, dan lain-lain.

**Kolom dan Deskripsi :**
show_id: Unique identifier for each show (s1, s2).
type: Specifies whether the title is a "Movie" or "TV Show".
title: The name of the Netflix title.
director: The director of the title
cast: The main actors involved in the title.
country: The country where the title was produced.
date_added: The date when the title was added to Netflix.
release_year: The year the title was originally released.
rating: The content rating ("PG-13", "TV-МА").
duration: Duration of the movie (in minutes) or the number of seasons for TV shows.
listed_in: Categories or genres the title falls under ("Documentaries", "TV Dramas").
description: The summary description

**Conclusion**

Model Machine Learning:
• Logistic Regression, Support Vector Machine (SVM), dan Random Forest digunakan untuk
membangun model klasifikasi.
• Logistic Regression: Model dasar yang cocok untuk masalah klasifikasi biner seperti
• SVM: Model yang efektif dalam menangani data dengan margin pemisahan yang jelas, cocok
untuk masalah klasifikasi dengan data yang lebih kompleks.
• Random Forest: Model ensemble yang menggabungkan banyak decision trees untuk
meningkatkan akurasi dan mengurangi overfitting.

Hasil Visualisasi:
• Visualisasi memberikan gambaran yang jelas mengenai distribusi data, seperti jumlah Movie dan
TV Show, serta negara dengan jumlah konten terbanyak di Netflix.
Hasil visualisasi akurasi dari berbagai model memberikan wawasan yang jelas tentang keunggulan
dan kelemahan masing-masing model dalam memprediksi tipe konten.

Evaluasi Model:
• Setelah pelatihan, model dievaluasi menggunakan metrik akurasi, precision, recall, dan F1-score,
serta confusion matrix untuk melihat distribusi prediksi.
• Visualisasi akurasi digunakan untuk membandingkan kinerja antara ketiga model.
Berdasarkan hasil, Random Forest menunjukkan performa yang lebih baik dalam menangani data
ketidakseimbangan dan menghasilkan akurasi yang lebih tinggi dibandingkan Logistic Regression
dan SVM.
