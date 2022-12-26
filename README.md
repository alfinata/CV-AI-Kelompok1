# **YOLOv4 Untuk Klasifikasi Citra**
Kegiatan ini dilakukan untuk mencoba melakukan klasifikasi citra menggunakan model YOLOv4.

## Sumber Rujukan
Kodingan notebook yang dipakai merujuk pada [file colab ini](https://github.com/techzizou/yolov4-custom_Training) dan untuk [site github ini](https://github.com/techzizou/yolov4-custom_Training).

## Dataset
Dataset yang dipakai merujuk ke [site kaggle ini](https://www.kaggle.com/datasets/sdevkota007/vehicles-nepal).  Dataset lalu dikelompokkan menjadi 3 kelas utama; mobil, truk, dan bus. Citra lalu dianotasi secara manual menggunakan [tools ini](https://github.com/techzizou/OpenLabeling).

## Environment
Kodingan secara keseluruhan dilakukan pada google colab, menggunakan [library darknet](https://github.com/AlexeyAB/darknet) dan drive pribadi.

## Training
Training dilakukan menggunakan dataset sekitar 405 citra yang sudah dianotasi. Proses ini dilakukan selama sekitar 2 jam dan dengan nilai avg loss terakhir sebesar 0.4737.


![](https://github.com/alfinata/CV-AI-Kelompok1/blob/main/images/training.png)
