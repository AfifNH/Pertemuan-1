# Tugas Machine Learning 13

Nama		: Afif Naufal Hafidz

NPM		: 41155050210067

Kelas		: TIF A2

---
Self Organizing Maps (SOM) 
Self Organizing Maps (SOM) adalah jenis jaringan saraf tiruan yang digunakan untuk mengelompokkan atau memetakan data dalam bentuk dua dimensi berdasarkan kesamaan fitur. SOM bekerja dengan cara unsupervised learning, di mana algoritma ini tidak memerlukan label dalam proses pelatihannya. Algoritma ini sering digunakan dalam analisis data eksploratif dan visualisasi data.
1.	Import Package
 ![Image](https://github.com/user-attachments/assets/58170767-2390-4c68-904f-1035d4aa0883)
2.	Import File CSV & Liat Data CSV
Dataset yang digunakan dalam implementasi ini disimpan dalam file CSV. Pada tahap ini, file CSV dibaca menggunakan pustaka pandas, kemudian data ditampilkan untuk memastikan bahwa data telah berhasil dimuat dengan benar. Beberapa fungsi yang sering digunakan adalah pd.read_csv() untuk membaca file dan df.head() untuk melihat beberapa baris pertama dari dataset.
![Image](https://github.com/user-attachments/assets/62e39a28-c5e9-41a8-bf92-20c0bd8dccb9) 
3.	Training  Dataset
Pada tahap ini, dataset yang telah diimpor digunakan untuk melatih model SOM. Proses ini melibatkan beberapa langkah:
•	Normalisasi dataset agar semua fitur memiliki rentang nilai yang sama.
•	Inisialisasi peta SOM dengan ukuran tertentu.
•	Pelatihan model menggunakan metode pembaruan bobot berdasarkan kesamaan data dengan neuron dalam peta.
 ![Image](https://github.com/user-attachments/assets/674bc7e4-132b-4f07-b7ab-645d44520b29)
4.	Output Training
Setelah proses pelatihan selesai, model akan menghasilkan output berupa:
•	Visualisasi peta SOM, yang menunjukkan klaster atau pola dalam data.
•	Label hasil klasterisasi, jika dataset memiliki label yang bisa dibandingkan.
•	Bobot neuron, yang menggambarkan bagaimana data dipetakan ke dalam jaringan SOM.
 ![Image](https://github.com/user-attachments/assets/37980b27-1b28-457d-9166-8ab8d3769e9f)

