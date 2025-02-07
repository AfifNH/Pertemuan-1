# Tugas Machine Learning 9

Nama		: Afif Naufal Hafidz

NPM		: 41155050210067

Kelas		: TIF A2

---
Studi Kasus :
Sebuah perusahaan melakukan penelitian terhadap data-data konsumen yang dimilikinya. Perusahaan tersebut akan melakukan pengelompokkan data ke dalam beberapa cluster berdasarkan kriteria besaran gaji yang diterima dan pengeluaran per bulannya. Berikut adalah data-data 20 konsumen dari perusahaan tersebut

Studi kasus kali ini akan melakukan clustering terhadap data-data konsumen di atas ke dalam beberapa kelompok, dimana masing-masing kelompok memiliki tingkat kemiripan maksimum. Tujuan penelitian ini adalah agar perusahaan dapat memetakan jenis produk yang sesuai dengan karakteristik konsumen.

Dataset :

![Image](https://github.com/user-attachments/assets/3d4a5ebf-57a1-4802-aac9-7b7a85a21605)

Jawaban:
## Metode Clustering

Metode yang digunakan dalam analisis ini adalah K-Means Clustering, sebuah teknik unsupervised learning yang mengelompokkan data ke dalam K kelompok berdasarkan kemiripan pola.

**Langkah-langkah Clustering:**
1. Menentukan jumlah cluster (K) - Dengan metode Elbow atau Silhouette Score.

2. Inisialisasi centroid awal - Memilih titik awal untuk pusat cluster.

3. Menghitung jarak Euclidean antara setiap titik data dan centroid.

4. Mengelompokkan data ke centroid terdekat.

5. Memperbarui centroid berdasarkan rata-rata data dalam cluster.

6. Mengulang proses hingga tidak ada perubahan signifikan dalam pembagian cluster.

![Image](https://github.com/user-attachments/assets/36b67b08-6715-4319-87ab-bce79f4257ae)

![Image](https://github.com/user-attachments/assets/23b7982e-84a3-4be7-98e9-7c021eb8f5c4)

![Image](https://github.com/user-attachments/assets/4185d8e1-71d8-4f43-832b-b5da6015b9f0)

![Image](https://github.com/user-attachments/assets/70ba1325-036a-4c95-9512-273cef586059)

![Image](https://github.com/user-attachments/assets/d6b5eaa3-bc8a-426a-826b-9b9de5b4c68e)

![Image](https://github.com/user-attachments/assets/391fa34f-fc6e-439c-8049-1ecd1fc7c885)

![Image](https://github.com/user-attachments/assets/58aac569-883f-40ce-996b-b5569c08e719)
