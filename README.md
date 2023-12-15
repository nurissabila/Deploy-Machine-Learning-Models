## DEPLOY MACHINE LEARNING MODELS
Project ini digunakan untuk mendeteksi RPS (Rock, Paper, Scissors) untuk mengklasifikasi citra gestur tangan individu pada permaian batu, kertas, gunting.

Link Dataset yang digunakan : 

Menggunakan Tranfer Learning pada klasifikasi citra gstur tangan dengan model VGG19

# Overview Dataset
Link dataset yang digunakan : 
Gambar yang digunakan dalah citra gestur tangan pada permaian batu, kertas, gunting dengan total gambar 2520 Terdiri dari 840 gambar gestur tangan batu, 840 gambar gestur tangan kertas, dan 840 gambar gestur tangan gunting

Splitting Dataset : Training : 70% , Validation = 25% , Testing = 5%

# Preprocessing dan Modelling
Preprocessing Model :  rescale=1./255, rotation_range=30, zoom_range=0.2, Horizontal_flip=True, fill_mode='nearest')

Modelling model VGG19
summary model VGG19

<img width="200" alt="Screenshot 2023-12-15 111848" src="https://github.com/nurissabila/Deploy-Machine-Learning-Models/assets/71714312/28e2e04e-413d-480a-837f-cc75d7538ca3">

Graph Loss dan Accuracy
![download (1)](https://github.com/nurissabila/Deploy-Machine-Learning-Models/assets/71714312/734c3497-dee7-44c0-ae16-9e5d3b655ee5)

Evaluation Matrix
<img width="270" alt="Screenshot 2023-12-15 112656" src="https://github.com/nurissabila/Deploy-Machine-Learning-Models/assets/71714312/25f5b39c-0725-4818-b21c-6af9ed769b39">

# Predict Data
Predict Data dengan Model VGG19
![download](https://github.com/nurissabila/Deploy-Machine-Learning-Models/assets/71714312/598f9a69-37e5-4a92-8b16-21b72629351d)


# Local Development



