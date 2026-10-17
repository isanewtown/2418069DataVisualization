# 2418069DataVisualization
IMDB Dataset Data Visualization

Deskripsi Proyek

Proyek ini berfokus pada pengolahan dan visualisasi data menggunakan dataset film IMDB. Tujuan utama dari tugas ini adalah menerapkan teknik visualisasi data langkah demi langkah menggunakan library Matplotlib di Python, guna menemukan insight menarik terkait tren film dari tahun ke tahun.

Fitur Visualisasi

Dalam proyek ini, data mentah yang telah melalui proses cleansing diolah lebih lanjut untuk menghasilkan dua visualisasi utama:

Tren Rata-Rata Skor IMDB per Tahun: Sebuah Line Chart yang melacak pergerakan rata-rata rating/skor film dari rilis terlama hingga terbaru.

Tren Total Pendapatan Film per Tahun: Sebuah Line Chart yang menampilkan akumulasi pendapatan film (Income) di setiap tahunnya (disajikan dalam satuan Juta Dolar agar representasi visual lebih rapi).

Teknik Matplotlib yang Diterapkan

Sesuai dengan tahapan pembelajaran visualisasi data, pembuatan grafik ini mencakup implementasi berikut:

Line Chart Trend: Membuat plot garis dasar dari data hasil agregasi (Groupby Pandas).

Figure Size: Mengatur dimensi kanvas grafik agar proporsional.

Title & Axis Labels: Memberikan judul grafik yang jelas beserta keterangan sumbu X (Tahun Rilis) dan sumbu Y (Skor/Pendapatan).

Line & Point Customization: Mengubah estetika visual seperti warna (color), ketebalan garis (linewidth), gaya garis (linestyle), serta bentuk penanda titik (marker).

Grid Customization: Menambahkan garis bantu latar belakang agar titik koordinat lebih mudah dibaca.

Text Annotation: Menyematkan teks informasi dinamis langsung di dalam grafik, seperti penanda otomatis untuk titik nilai tertinggi (skor maksimal atau rekor pendapatan).

Tech Stack

Bahasa Pemrograman: Python

Library Utama: Pandas, Matplotlib

Environment: Google Colaboratory (Colab)

Cara Menjalankan

Clone repositori ini atau unduh file Jupyter Notebook (.ipynb).

Pastikan file data bersih IMDB_dataset_clean.xlsx berada di direktori yang sama, atau unggah ke dalam session storage Google Colab.

Jalankan cell secara berurutan untuk melihat hasil transformasi data dan proses pembentukan visualisasi selangkah demi selangkah.
