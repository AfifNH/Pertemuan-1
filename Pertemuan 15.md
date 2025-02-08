# Tugas Machine Learning 15

Nama		: Afif Naufal Hafidz

NPM		: 41155050210067

Kelas		: TIF A2

---
Aplikasi Deteksi Diabetes berbasis Web
Aplikasi ini dikembangkan untuk mendeteksi kemungkinan diabetes berdasarkan data yang diberikan oleh pengguna. Aplikasi ini dibangun menggunakan Python dengan framework Flask dan dideploy menggunakan Railway.
1.	Setting file app.py
File app.py merupakan inti dari aplikasi ini yang menangani logika backend. Beberapa hal yang dikonfigurasi dalam file ini antara lain:
•	Mengimpor library yang diperlukan seperti Flask, Pandas, dan Scikit-learn.
•	Memuat model Machine Learning yang telah dilatih sebelumnya untuk mendeteksi diabetes.
•	Mengatur routing pada aplikasi seperti halaman utama (/), halaman hasil (/hasil), dan API prediksi.
•	Mengolah input pengguna dan memberikan output berupa prediksi berdasarkan model yang telah dilatih.

![Image](https://github.com/user-attachments/assets/138188c9-f71e-46f7-b9ba-59d1827f004f)

2.	Setting file base.html
File base.html merupakan template utama untuk tampilan aplikasi. File ini menggunakan template inheritance agar halaman lain seperti index.html dan hasil.html dapat menggunakan struktur yang sama. Isi utama dari file ini meliputi:
•	Struktur dasar HTML termasuk header dan footer.
•	Link ke CSS dan JavaScript untuk tampilan yang lebih menarik.
•	Template block yang akan diisi oleh halaman lain.

![Image](https://github.com/user-attachments/assets/3d0fb081-2a14-41b4-93e5-d473b48119c3)

3.	Setting file hasil.html
File hasil.html digunakan untuk menampilkan hasil prediksi dari model Machine Learning. Halaman ini berisi:
•	Pesan yang menunjukkan apakah pengguna berisiko diabetes atau tidak.
•	Tampilan lebih lanjut seperti grafik atau probabilitas jika diperlukan.
•	Tombol kembali ke halaman utama untuk memasukkan data baru.

![Image](https://github.com/user-attachments/assets/009ba38d-eb55-4789-868a-7edad9cde159)

4.	Setting file index.html
File index.html merupakan halaman utama aplikasi yang berisi:
•	Form untuk memasukkan data pengguna, seperti usia, tekanan darah, kadar glukosa, dll.
•	Tombol untuk mengirimkan data ke backend agar diproses oleh model Machine Learning.
•	Deskripsi singkat mengenai tujuan aplikasi.

![Image](https://github.com/user-attachments/assets/f74323ed-ecf6-4281-a684-e77920d80be0) 

![Image](https://github.com/user-attachments/assets/e80201e8-580a-430c-94d3-3d64199ea2dc)

5.	Mengupload file konfigurasi ke Github

![Image](https://github.com/user-attachments/assets/597baade-f83b-4e52-b85f-ef82d51b8065) 

6.	Mendeploy di web railway
Railway digunakan untuk melakukan deployment aplikasi secara online. Langkah-langkah yang dilakukan:
•	Menghubungkan repository GitHub ke Railway.
•	Menyesuaikan variabel lingkungan (environment variables) yang diperlukan oleh aplikasi.
•	Menjalankan build dan deploy aplikasi sehingga dapat diakses oleh pengguna melalui URL yang disediakan oleh Railway.

![Image](https://github.com/user-attachments/assets/383b1a03-71b1-48a7-9735-41f295077f10)

7.	Tampilan aplikasi hasil deploy

![Image](https://github.com/user-attachments/assets/efa82e09-4a50-4b01-8abf-4734f7cccc1f)

8.	Hasil Testing Aplikasi

![Image](https://github.com/user-attachments/assets/4bc803f6-5c13-4e12-a34a-961bf42d075a)
