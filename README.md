# perbandingan-algoritma-ann-dan-svm-untuk-pengelompokan-kinerja-siswa
Pada project ini, dilakukan klasifikasi untuk mengelompokan kinerja siswa. Akan dibandingkan hasil klasifikasi algoritma ANN dan SVM.

<br>
Klasifikasi data menggunakan MLPClassifier dengan parameter :<br>
o activation = relu (menggunakan fungsi aktivasi relu)<br>
o solver = lbfgs<br>
o max_iter = 500 (jumlah maksimal iterasi atau epoch)<br>
o alpha = 1e-5<br>
o hidden_layer_size = 5,3 (terdapat 2 hidden layer dimana hidden layer pertama mempunyai 5 neuron dan hidden kedua mempunyai 3 neuron)<br>
o random_state = 0 (generator nilai random agar setiap si run tidak berubah) <br>
Menghasilkan akurasi validasi sebesar 0,94444 dimana nilai tersebut hamper mendekati 1 sehingga dikatakan akurasi tinggi. Kemudian dilakukan prediksi x_test dengan model yang sudah dibentuk tersebut yang menghasilkan y_prediksi sebagai berikut ['group A' 'group B' 'group A' 'group C' 'group C' 'group B' 'group B' 'group A' 'group C' 'group C'] yang sama percis dengan y_test. Kemudian dilakukan evaluasi klasifikasi dan didapatkan hasil sebagai berikut <br>
o Accuracy Score = 1.0<br>
o Precision Score = 1.0<br>
o Recall Score = 1.0<br>

<br><br>
Dengan model.n_support dapat diketahui bahwa jumlah masing-masing support vector untuk setiap kelas adalah 20, 28 dan 22. Kemudian dilakukan evaluasi klasifikasi dan didapatkan hasil sebagai berikut<br>
o Accuracy Score = 1.0<br>
o Precision Score = 1.0<br>
o Recall Score = 1.0<br>
