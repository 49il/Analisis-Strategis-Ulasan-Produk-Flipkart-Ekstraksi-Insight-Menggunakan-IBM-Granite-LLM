Analisis Strategis Ulasan Produk Flipkart: Ekstraksi Insight Menggunakan IBM Granite LLM
Deskripsi
Proyek ini melakukan analisis mendalam terhadap ulasan produk Flipkart menggunakan IBM Granite LLM untuk mengekstraksi insight bisnis yang actionable. Tujuan utamanya adalah mengubah ribuan ulasan tidak terstruktur—terutama yang memiliki inkonsistensi antara rating dan sentimen—menjadi informasi strategis yang akurat untuk mendukung pengambilan keputusan bisnis.

🔹 Project Overview
Di tengah persaingan e-commerce yang ketat, ulasan pelanggan telah menjadi aset data strategis. Analisis awal pada dataset ulasan produk Flipkart menunjukkan adanya inkonsistensi signifikan antara rating bintang yang diberikan pelanggan dan sentimen teks ulasan. Masalah ini dapat mengaburkan pemahaman nyata tentang kepuasan pelanggan dan menghambat perumusan strategi yang efektif.

Tujuan proyek ini adalah:

Mengidentifikasi pola tersembunyi di balik kepuasan dan keluhan pelanggan.

Mengoreksi label sentimen yang tidak konsisten menggunakan kemampuan kontekstual AI.

Memberikan rekomendasi strategis yang tajam untuk tim produk, pemasaran, dan layanan pelanggan.

🔹 Rumusan Masalah
Apa pendorong utama di balik kepuasan dan kekecewaan pelanggan secara spesifik?

Pola tersembunyi apa yang ada dalam keluhan yang terkait dengan produk atau kategori tertentu?

Bagaimana cara memprioritaskan perbaikan produk atau layanan untuk memberikan dampak terbesar pada loyalitas pelanggan?

🔹 Tujuan Proyek
Klasifikasi Sentimen Akurat: Mengklasifikasikan ulasan menjadi positif, negatif, dan netral menggunakan IBM Granite LLM untuk mengatasi inkonsistensi data.

Ekstraksi Tema Utama: Meringkas ribuan ulasan untuk menemukan tema utama dari keluhan (misal: "kualitas pengiriman", "ukuran tidak sesuai") dan pujian (misal: "daya tahan baterai", "desain elegan").

Identifikasi Faktor Kunci: Menemukan faktor-faktor yang paling krusial dalam memengaruhi rating dan sentimen pelanggan.

Rekomendasi Strategis: Menyusun rekomendasi yang actionable untuk meningkatkan pengalaman pelanggan dan performa produk.

🔹 Metodologi
Proyek ini dijalankan dengan alur kerja yang sistematis:

Pemahaman Bisnis: Menentukan tujuan dan metrik keberhasilan proyek.

Akuisisi & Preprocessing Data: Memuat dataset dari Kaggle, membersihkan data (menangani missing values & duplikat), dan normalisasi teks.

Exploratory Data Analysis (EDA): Melakukan analisis mendalam terhadap distribusi sentimen dan rating, panjang teks ulasan, analisis kata umum (termasuk WordCloud), serta menganalisis hubungan antara harga dan rating untuk menemukan outlier dan inkonsistensi.

Pemodelan dengan IBM Granite LLM: Menerapkan model untuk klasifikasi sentimen dan ekstraksi tema utama dari ulasan.

Analisis Hasil & Rekomendasi: Menganalisis insight yang dihasilkan dan merumuskan rekomendasi bisnis yang strategis.

🔹 Dataset
Sumber: Flipkart Product Reviews Dataset di Kaggle

🔹 Insight & Findings
Inkonsistensi Data Terungkap: Analisis membuktikan adanya banyak ulasan dengan rating tinggi namun sentimen teksnya negatif, dan sebaliknya. AI berhasil mengoreksi ini.

Identifikasi Produk Bermasalah: Ditemukan produk dengan keluhan kronis, contohnya MAHARAJA WHITELINE Air Cooler dengan keluhan utama pada "kualitas buruk" dan "tidak berguna."

Pola Keluhan per Kategori: Untuk kategori Fashion, keluhan "ukuran tidak sesuai" ternyata lebih dominan dibandingkan keluhan tentang kualitas kain.

Kualitas Mengalahkan Harga: Ditemukan bahwa rating positif lebih kuat dipengaruhi oleh kualitas dan fungsionalitas produk daripada sekadar harga yang murah.

🔹 Rekomendasi & Aplikasi Bisnis
Hasil analisis ini siap digunakan untuk mendukung keputusan bisnis yang berdampak:

Untuk Tim Pemasaran: Menggunakan tema pujian utama (misal: "Kualitas Pendingin Terbaik") sebagai bahan utama untuk slogan dan kampanye promosi.

Untuk Tim Produk: Memprioritaskan perbaikan pada produk-produk yang teridentifikasi memiliki keluhan kronis dan spesifik.

Untuk Tim Layanan Pelanggan: Melatih tim untuk lebih memahami akar masalah keluhan pelanggan berdasarkan tema yang paling sering muncul.

🔹 Cara Menjalankan Proyek
Clone repositori ini: git clone https://github.com/49il/Analisis-Strategis-Ulasan-Produk-Flipkart-Ekstraksi-Insight-Menggunakan-IBM-Granite-LLM

Buka file Analisis Strategis Ulasan Produk Flipkart_ Ekstraksi Insight Menggunakan IBM Granite LLM.ipynb di Google Colab.

Pastikan dataset dari Kaggle telah diunggah atau tersedia di lingkungan Colab Anda.

Jalankan semua sel secara berurutan untuk mereproduksi analisis dari awal hingga akhir.

🔹 AI Support
IBM Granite LLM memainkan peran sentral dalam proyek ini untuk:

Klasifikasi & Analisis Sentimen: Memahami konteks ulasan secara mendalam untuk mengoreksi label sentimen yang salah.

Summarization: Mengekstraksi dan meringkas tema-tema kunci dari ribuan ulasan, yang memungkinkan analisis produk dan kategori secara efisien.

Tujuan utama penggunaan AI adalah untuk mengubah dataset yang tidak konsisten menjadi aset data yang akurat dan bernilai tinggi untuk pengambilan keputusan bisnis yang strategis
