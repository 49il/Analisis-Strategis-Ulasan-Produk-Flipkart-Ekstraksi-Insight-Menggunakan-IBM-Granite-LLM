Analisis Strategis Ulasan Produk Flipkart
Ekstraksi Insight Menggunakan IBM Granite LLM

Deskripsi:
Analisis ulasan produk Flipkart menggunakan IBM Granite LLM untuk mengekstraksi insight bisnis yang actionable dan memperbaiki inkonsistensi sentimen. Proyek ini bertujuan mengubah ribuan ulasan tidak terstruktur menjadi informasi strategis yang mendukung keputusan bisnis.

🔹 Project Overview

Ulasan pelanggan kini menjadi aset data strategis di era e-commerce yang kompetitif. Analisis awal pada dataset Flipkart menunjukkan adanya inkonsistensi signifikan antara rating dan sentimen, yang dapat mengaburkan pemahaman tentang kepuasan pelanggan.

Tujuan proyek:

Mengidentifikasi pola tersembunyi dalam ulasan.

Mengoreksi label sentimen yang salah menggunakan AI.

Memberikan rekomendasi strategis untuk tim produk, pemasaran, dan layanan pelanggan.

🔹 Rumusan Masalah

Apa pendorong utama kepuasan dan kekecewaan pelanggan secara spesifik?

Pola tersembunyi apa yang ada dalam keluhan terkait produk tertentu?

Bagaimana memprioritaskan perbaikan produk atau layanan untuk meningkatkan loyalitas pelanggan?

🔹 Tujuan Proyek

Klasifikasi Sentimen Akurat: Mengklasifikasikan ulasan menjadi positif, negatif, dan netral menggunakan IBM Granite LLM.

Ekstraksi Tema Utama: Meringkas ribuan ulasan untuk menemukan tema utama keluhan dan pujian (misal: "kualitas pengiriman", "daya tahan baterai").

Identifikasi Faktor Kunci: Menemukan faktor yang paling mempengaruhi rating dan sentimen pelanggan.

Rekomendasi Strategis: Menyusun rekomendasi actionable untuk meningkatkan pengalaman pelanggan dan performa produk.

🔹 Metodologi

Alur kerja proyek:

Pemahaman Bisnis: Menentukan tujuan dan metrik keberhasilan.

Akuisisi & Preprocessing Data:

Load dataset dari Kaggle.

Cek missing values dan duplikat.

Normalisasi teks review.

Exploratory Data Analysis (EDA):

Distribusi sentimen dan rating.

Panjang teks review.

Analisis kata umum, bigram, trigram, dan WordCloud.

Hubungan harga dengan rating.

Analisis outlier review tidak konsisten.

Pemodelan dengan IBM Granite LLM:

Klasifikasi sentimen.

Ekstraksi tema utama.

Insight & Findings:

Tema dan masalah tersembunyi.

Faktor penentu rating.

Pola outlier dan inkonsistensi.

Benchmarking produk.

Rekomendasi strategis untuk perbaikan produk dan pengalaman pelanggan.

Deployment: Hasil analisis siap digunakan untuk mendukung keputusan bisnis.

🔹 Dataset

Sumber: Kaggle

Flipkart Product Reviews Dataset

🔹 Insight & Findings

Inkonsistensi Data: Banyak ulasan rating tinggi diberi label negative dan sebaliknya.

Produk Bermasalah Kronis: Contoh: MAHARAJA WHITELINE Air Cooler, keluhan utama: "kualitas buruk" dan "tidak berguna."

Tema Keluhan Kategori Fashion: "Ukuran tidak sesuai" lebih sering muncul daripada kualitas kain.

Kualitas Produk Lebih Penting daripada Harga: Rating positif lebih dipengaruhi kualitas dan fungsionalitas daripada harga.

🔹 AI Support

IBM Granite LLM digunakan untuk:

Klasifikasi & Analisis Sentimen: Mengoreksi label yang salah dan memahami konteks ulasan.

Summarization: Mengekstraksi tema utama dari ribuan ulasan untuk mendukung analisis produk dan kategori.

Tujuan utama: mengubah dataset tidak konsisten menjadi aset data akurat untuk keputusan bisnis yang strategis.
