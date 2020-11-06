# Pembelajaran-Mesin-Metode-Regresi
Merupakan Program Sederhana Untuk Melakukan Prediksi Berdasarkan Dataset Training dengan Metode Regresi Linier

Untuk penjelasan yang lebih lengkap silahkan membuka video berikut : ().

Penjelasan singkat bisa dilihat di bagian komentar program: tubes_regresi_kelompok_9.py.
Penjelasan umum dapat dibaca di file readme ini.

Kami melakukan prediksi terhadap data daya tenaga mesin mobil (hoursepower) terhadap perkiraan durasi akselerasi. 
Kami menggunakan dataset yang diimport dari vega (https://github.com/altair-viz/vega_datasets)

Overview Regresi Linier 

Regresi Linier merupakan suatu model statistik yang umum dan paling sederhana dalam Machine Learning. Digunakan untuk melakukan prediksi dengan cara supervised learning. Regresi Linier hanya bisa digunakan untuk data yang bersifat interval dan ratio yang biasanya bersifat diskrit dan kontinu, dan merupakan analisis bivariate dan multivariate.

Pada kelompok kami menggunakan analisis bivariate atau korelasi antara 2 variabel.
Dimana salah satunya adalah variabel independen (x) variabel utama yang mungkin akan mempengaruhi nilai variabel y dan satu lagi adalah variabel dependen (y) nilai variabel ini akan tergantung dari nilai variabel independennya.

x:= Horsepower (HP) y:= Waktu Akselerasi (s)

Overview Colab 

Colab merupakan IDE bebrbasis cloud dari google. Google colab cocok digunakan untuk pemrograman python dan dimana kita tidak menjalankan  komputasi yang berat di device kita, tapi semuanya dilakukan di cloud, kita hanya membutuhkan koneksi internet saja.

Overview Scikit 

Scikit-learn merupakan open source machine learning library menyediakan berbagai macam machine learning dengan bahasa python yang mendukung supervised and unsupervised learning.


Kesimpulan hasil running program :

Jika nilai daya/tenaga mesin mobil (Horsepower) tinggi, maka waktu akselerasi semakin cepat.
Akurasi program mencapai 57,03%

Regresi Linier dapat digunakan untuk melakukan prediksi nilai dengan pola garis terbaik antara variable independent dan dependen.

Kelebihan:
- Mudah diimplementasikan
- Digunakan untuk memprediksi nilai numerik/ continous /data jenis interval dan ratio
Kekurangan:
- Tidak dapat digunakan bila relasi antara variabel independen dan dependen tidak linier atau korelasinya rendah
- Variabel yang digunakan terbatas


Laily Ade Oktaviana         - 2101201026
Naufal Hanan Lutfianto      - 2101201030
Gregorius Pradana Satriawan - 2101201041
