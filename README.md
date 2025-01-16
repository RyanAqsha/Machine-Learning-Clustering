# Machine-Learning-Clustering & Klasifikasi

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis dataset menggunakan teknik **clustering** dan **classification**. Dengan algoritma **K-Means**, data dikelompokkan menjadi beberapa cluster, sedangkan model **Random Forest** digunakan untuk memprediksi label cluster dengan akurasi tinggi.

## Fitur Utama
- Menggunakan **K-Means** untuk clustering data.
- Mengevaluasi kualitas clustering menggunakan **Silhouette Score**.
- Membangun model klasifikasi menggunakan **Random Forest** untuk memprediksi label cluster.
- Menyediakan laporan evaluasi berupa akurasi, precision, recall, dan F1-score.

## Langkah-langkah
1. **Persiapan Data**:
   - Memuat dataset.
   - Menangani nilai kosong menggunakan metode `ffill`.
   - Memilih fitur relevan untuk analisis.

2. **Clustering dengan K-Means**:
   - Menerapkan algoritma **K-Means** dengan jumlah cluster tertentu.
   - Mengevaluasi clustering menggunakan **Silhouette Score**.

3. **Klasifikasi dengan Random Forest**:
   - Membagi dataset menjadi data pelatihan dan pengujian.
   - Melatih model **Random Forest** pada data pelatihan.
   - Memprediksi label cluster untuk data pengujian.

4. **Evaluasi Model**:
   - Mengukur akurasi model klasifikasi.
   - Menyediakan laporan klasifikasi yang mencakup metrik utama.

## Cara Menjalankan
1. Instal pustaka yang dibutuhkan:
   ```bash
   pip install pandas numpy scikit-learn
