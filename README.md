# Analyzing Wikipedia Pages

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis halaman-halaman Wikipedia dengan berbagai cara, termasuk mengunduh artikel acak, mencari kata kunci, menghitung frekuensi kata, mengidentifikasi kategori artikel, hingga membuat visualisasi seperti Word Cloud dan grafik distribusi topik.

## Fitur Utama
1. **Mengunduh Artikel Acak Wikipedia**
   - Mengunduh 1000 artikel Wikipedia secara acak.
   - Memastikan bahwa halaman yang diunduh adalah artikel utama (bukan halaman khusus).
   - Menyimpan artikel dalam format `.html` dengan nama file yang dibersihkan dari karakter ilegal.

2. **Menghitung Jumlah File dalam Folder Dataset**
   - Menampilkan jumlah total file yang tersimpan di folder `wiki`.

3. **Membaca dan Menampilkan Konten File Pertama**
   - Menampilkan seluruh konten dari file pertama dalam folder `wiki`.

4. **Pencarian Paralel Kata Kunci (`data`)**
   - Mencari kemunculan kata kunci `"data"` di semua file menggunakan pendekatan **MapReduce** dan **pemrosesan paralel**.
   - Menunjukkan lokasi spesifik (file dan baris) di mana kata tersebut muncul.

5. **Pencarian Case-Insensitive**
   - Mirip dengan pencarian sebelumnya, tetapi tidak membedakan huruf besar/kecil (case-insensitive).

6. **Membandingkan Hasil Pencarian Baru dan Lama**
   - Menunjukkan file baru atau tambahan kemunculan kata `"data"` yang tidak ada di hasil pencarian sebelumnya.

7. **Mencari Indeks Kemunculan Substring**
   - Menampilkan indeks awal setiap kemunculan substring `"data"` dalam sebuah string.

8. **Ekstraksi Kemunculan Kata dengan Konteks**
   - Menyimpan hasil pencarian ke dalam file CSV, mencakup nama file, nomor baris, indeks karakter, dan konteks sekitar kata.

9. **Menghitung Frekuensi Kata Kunci**
   - Menampilkan frekuensi kemunculan kata kunci seperti `"science"` dan `"history"` di semua file.

10. **Mengidentifikasi Kategori Artikel**
    - Menampilkan daftar kategori artikel dari file pertama.

11. **Membuat Word Cloud**
    - Menampilkan Word Cloud yang menunjukkan kata-kata paling sering muncul dalam dataset.

12. **Klasifikasi dan Visualisasi Kategori Artikel**
    - Menampilkan grafik batang yang menunjukkan distribusi artikel berdasarkan kategori seperti Science, History, dan Technology.
