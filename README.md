# Studi-Kasus-Ketiga-Computer-Vision

## Dataset German Traffic Sign
[German Traffic](https://www.kaggle.com/datasets/saadhaxxan/germantrafficsigns) Sign Dataset merupakan benchmark dataset untuk klasifikasi gambar multi kelas. Terdapat satu rambu lalu lintas pada masing-masing gambar, sehingga dataset ini disebut juga sebagai single-image atau gambar tunggal. Dataset ini pertama kali diluncurkan dalam perlombaan (challenge) yang diselenggarakan oleh the International Joint Conference on Neural Networks (IJCNN) pada tahun 2011. 

Dataset ini memiliki komponen sebagai berikut:

- Data untuk permasalahan klasifikasi gambar tunggal dengan banyak kelas.
- Terdiri dari 43 kelas, artinya ada 43 jenis rambu lalu lintas.
- Memiliki total lebih dari 50.000 gambar .
- Data diambil dari foto rambu yang sebenarnya (bukan sintetis).

Data yang akan kita gunakan dalam bentuk file pickle yang dibuat dengan modul Python bernama [pickle](https://docs.python.org/3/library/pickle.html). Ia digunakan untuk mengubah objek Python menjadi representasi byte untuk disimpan pada storage atau dipindahkan melalui jaringan. Hal ini memungkinkan objek untuk disimpan atau ditransmisikan dengan mudah tanpa mengubah data ke format lain terlebih dahulu.

## Loading Data
Pada proyek ini melakukan mount drive dan me-_load_ data untuk _training_ dan _test_
training_file = "/content/drive/MyDrive/Dataset/German Traffic Sign/train.p"
testing_file = "/content/drive/MyDrive/Dataset/German Traffic Sign/test.p"  
