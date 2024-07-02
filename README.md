# YOLOv5 Train Tutorial
### Tutorial Melatih Model YOLOv5

Anotasi dataset pada situs [Roboflow](https://roboflow.com/).

![image](https://github.com/lordwildbeast/yolov5-train-tutorial/assets/116777219/2f611f03-621b-4361-a36e-ccd599351279)

Kemudian eksport dataset ke format YOLO dalam bentuk baris kode yang sudah disediakan.

![image](https://github.com/lordwildbeast/yolov5-train-tutorial/assets/116777219/bcddc6bf-1f0e-4956-99fb-c4cacd750e8f)

Selanjutnya masuk ke dalam [Google Colab](https://colab.research.google.com/), platform ini tempat untuk model YOLO dilatih. Tahapan awal adalah buka [file notebook](https://github.com/lordwildbeast/yolov5-train-tutorial/blob/main/YOLOv5_Training_GDrive.ipynb) menggunakan Colab. 

![image](https://github.com/lordwildbeast/yolov5-train-tutorial/assets/116777219/b1031e2e-5c1d-4566-9738-328a6d39f7dc)

Selanjutnya jalankan tiap sel dimulai dari menghubungkan ke Google Drive dan clone repositori YOLO dari Github serta menginstal library yang dibutuhkan untuk training model YOLO.

![image](https://github.com/lordwildbeast/yolov5-train-tutorial/assets/116777219/8b71b65b-d5cd-4930-aa80-a2a67679f106)

Tempel baris kode yang sebelumnya didapatkan dari Roboflow pada Colab.

![image](https://github.com/lordwildbeast/yolov5-train-tutorial/assets/116777219/30792ba5-60c1-4863-a999-cdc2aa15dac9)

Tahap berikutnya memulai training model dengan epoch sebanyak 500.

![image](https://github.com/lordwildbeast/yolov5-train-tutorial/assets/116777219/e1879762-a03d-47a0-9d53-147c33758945)

Setelah tahap training selesai, unduh file model YOLO dalam format onnx untuk dimasukkan ke dalam program.

![image](https://github.com/lordwildbeast/yolov5-train-tutorial/assets/116777219/f32baab5-bc12-4bbd-a0c0-756ea020883e)







