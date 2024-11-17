# Tugas Machine Learning 5

Nama		: Afif Naufal Hafidz

NPM		: 41155050210067

Kelas		: TIF A2

---

1.	K-Nearest Neighbours (KNN)

1.1.	Persiapan sample dataset
![1](https://github.com/user-attachments/assets/b46d4ff9-9539-4a1e-be4b-558e989353b0)

1.2.	 Visualisasi dataset
![2](https://github.com/user-attachments/assets/553a9112-5b9e-4d81-a436-446b57fb5094) 
![2 1](https://github.com/user-attachments/assets/c5fd37bd-2295-4ded-9a9e-df13e0ed11cb)
 
1.3.	 Pengantar classification dengan K-Nearest Neighbours | KNN

KNN adalah model machine learning yang dapat digunakan untuk melakukan prediksi berdasarkan kedekatan karakteristik dengan sejumlah tetangga terdekat. Prediksi yang dilakukan dapat diterapkan baik pada classification maupun regression tasks.
Algoritma K-Nearest Neighbor menggunakan 'kemiripan fitur' untuk memprediksi nilai dari setiap titik data baru. Ini berarti bahwa titik baru diberi nilai berdasarkan seberapa dekat kemiripannya dengan titik-titik dalam set pelatihan. Selama implementasi regresi, rata-rata nilai diambil sebagai prediksi akhir, sedangkan selama implementasi klasifikasi, mode nilai diambil sebagai prediksi akhir.	

1.4.	 Preprocessing dataset dengan Label Binarizer
![3](https://github.com/user-attachments/assets/de3048c1-79bb-4e4d-8709-69edf94127a8) 
![3 1](https://github.com/user-attachments/assets/05aed880-d92e-4f8b-8967-0fa559cdc26d)
 
1.5.	 Training KNN Classification Model
![4](https://github.com/user-attachments/assets/5bbfbf98-1c4d-42f5-ae3f-b04da49e3432)
 
1.6.	 Prediksi dengan KNN Classification Model
![5](https://github.com/user-attachments/assets/61b24a22-6e53-4112-bbb3-d17cd14bb0c1)
 
1.7.	 Visualisasi Nearest Neighbours
![6](https://github.com/user-attachments/assets/4862d18a-5035-4554-b112-7ac0d8725f2b)
![6 1](https://github.com/user-attachments/assets/46205b25-5c61-4deb-94fc-84e9ece1645b)
  
1.8.	 Kalkulasi jarak dengan Euclidean Distance

Dalam matematika, Euclidean Distance antara dua titik dalam ruang Euclidean adalah panjang segmen garis di antara keduanya. Jarak ini dapat dihitung dari koordinat Cartesius titik-titik tersebut menggunakan teorema Pythagoras, dan oleh karena itu kadang-kadang disebut

![7 3](https://github.com/user-attachments/assets/c59b42eb-9c12-4bcf-a2ed-0d92e3b3a351) 
![7](https://github.com/user-attachments/assets/f4a2addc-a5ac-4061-88e9-cbcbe9521f6c) 
![7 1](https://github.com/user-attachments/assets/69f0139d-5bb8-4241-9231-edf71fff380c)
![7 2](https://github.com/user-attachments/assets/2babc078-8402-4cd7-a552-787679ba4563)
 
1.9.	 Evaluasi KNN Classification Model | Persiapan testing set
![8](https://github.com/user-attachments/assets/b166af91-34a4-4369-a097-4b29b9ed6e58) 

1.10.	 Evaluasi model dengan accuracy score

Akurasi adalah proporsi contoh pengujian yang diklasifikasikan dengan benar.

![9](https://github.com/user-attachments/assets/efd7f375-46c9-4d56-8051-d5683253be6a)
![9 1](https://github.com/user-attachments/assets/d5cddd0d-74fe-454f-9d9d-5c0696a2d056)

1.11.	Evaluasi model dengan precision score

Presisi adalah proporsi contoh tes yang diprediksi positif yang benar-benar positif.

![10](https://github.com/user-attachments/assets/2b17d225-48ac-459e-862a-163d4462838d) 
![10 1](https://github.com/user-attachments/assets/85ffdc47-b94c-40c5-8cd8-be8e26e21732)
   
1.12.	Evaluasi model dengan recall score

Recall adalah proporsi contoh tes yang benar-benar positif yang diprediksi positif.

![11](https://github.com/user-attachments/assets/a820cb19-ff81-4722-b30d-de634e88c0d4)
![11 1](https://github.com/user-attachments/assets/197e9ada-f65b-4c46-99e6-e2ceddab87bc)
 
1.13.	Evaluasi model dengan F1 score

Skor F1 adalah rata-rata harmonis dari presisi dan recall.

![12](https://github.com/user-attachments/assets/79b15c78-d12b-4660-a864-8bc918312258)
![12 1](https://github.com/user-attachments/assets/158ac5c1-bd9e-4e46-ab90-0e95f83557a9)
 
 
1.14.	Evaluasi model dengan classification report
![13](https://github.com/user-attachments/assets/e965ec8b-7317-4cb9-b83f-3db7ae42b1fe)
 
1.15.	Evaluasi model dengan Mathews Correlation Coefficient

•	MCC adalah alternatif dari skor F1 untuk mengukur kinerja pengklasifikasi biner.

•	MCC pengklasifikasi yang sempurna adalah 1.

•	Pengklasifikasi trivial yang memprediksi secara acak akan mendapat skor 0, dan pengklasifikasi yang salah sempurna akan mendapat skor -1.

![14](https://github.com/user-attachments/assets/674b7fa5-54ea-4ce6-a108-7dd9cb8cf2d5)
![14 1](https://github.com/user-attachments/assets/5b79f020-a30b-44d0-81c0-8027e7abc7e0)
 
 
2.	Support Vector Machine (SVM)

2.1.	 Pengenalan Decision Boundary & Hyperplane

Konsep Dasar

Decision Boundary (Hyperplane)
![1](https://github.com/user-attachments/assets/5cd8135d-8268-4cb4-869f-d3eb62d1c030)
 
2.2.	 Pengenalan Support Vector & Maximum Margin
![2](https://github.com/user-attachments/assets/693712a6-b9be-4392-a101-5fa45bd241cc)
 
2.3.	 Pengenalan kondisi Linearly Inseparable dan Kernel Tricks
![3](https://github.com/user-attachments/assets/d76b0996-56ab-4bb3-b80e-f7131d078fb8)
 
2.4.	 Pengenalan MNIST Handwritten Digits Dataset
![ver collab 1](https://github.com/user-attachments/assets/6bc59c48-d191-45c6-a7a1-02ae66beb81e)
![ver collab 1 1](https://github.com/user-attachments/assets/ddef87dc-d594-4036-a5c5-38d375ffd946)
  
2.5.	  Klasifikasi dengan Support Vector Classifier | SVC
![ver collab 2](https://github.com/user-attachments/assets/4a166dad-39e9-440d-876f-140ae45af719)
 
2.6.	 Hyperparameter Tuning dengan Grid Search
![ver collab 3](https://github.com/user-attachments/assets/36d94bbe-9cff-47c5-814c-e8220790e44f)
![ver collab 3 1](https://github.com/user-attachments/assets/4f93da74-8684-4eb3-8ca6-c70855cb90fd)
 
2.7.	  Evaluasi model 
![ver collab 4](https://github.com/user-attachments/assets/6e4dd325-e770-4a63-ac1c-4ed741917369)
 

