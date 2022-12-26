# **YOLOv4 Untuk Klasifikasi Citra**
Kegiatan ini dilakukan untuk mencoba melakukan klasifikasi citra menggunakan model YOLOv4.

## Sumber Rujukan
Kodingan notebook yang dipakai merujuk pada [file colab ini](https://github.com/techzizou/yolov4-custom_Training) dan untuk [site github ini](https://github.com/techzizou/yolov4-custom_Training).

## Dataset
Dataset yang dipakai merujuk ke [site kaggle ini](https://www.kaggle.com/datasets/sdevkota007/vehicles-nepal).  Dataset lalu dikelompokkan menjadi 3 kelas utama; mobil, truk, dan bus. Citra lalu dianotasi secara manual menggunakan [tools ini](https://github.com/techzizou/OpenLabeling). Dataset akhir sebelum masuk ke model dapat diakses [di sini](https://drive.google.com/drive/folders/19rPellKfH1cEiQYhg3sWIh0rOwYYzCjU?usp=share_link).

## Environment
Kodingan secara keseluruhan dilakukan pada google colab, menggunakan [library darknet](https://github.com/AlexeyAB/darknet) dan drive pribadi.

## Training
Training dilakukan menggunakan dataset sekitar 405 citra yang sudah dianotasi. Proses ini dilakukan selama sekitar 2 jam dan dengan nilai avg loss terakhir sebesar 0.4737.

![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/training.png)

## Testing
Weight yang sudah didapat tadi dipakai detector untuk test ke data baru untuk melakukan klasifikasi. Berikut adalah hasil deteksi pada citra dari dataset awal.

![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/testin1.png)
![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/testin2.png)
![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/testin3.png)

Namun karena keterbatasan varian dataset, model yang dipakai masih kurang bahkan belum bisa melakukan klasifikasi pada citra lain.

![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/testin4.png)
![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/testin5.png)
![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/testin6.png)
