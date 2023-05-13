# Rain in Australia - Next-Day Prediction Model
## Project Overview
## Data Source

* Dataset yang digunakan adalah data rain in Australia yang tersedia di platform Kaggle. Dataset ini berisi histori cuaca harian selama 10 tahun dari berbagai lokasi di Australia yang terdiri dari 145460 baris dan 23 atribut.
* Data ini terdiri dari informasi cuaca di Melbourne, Australia dari tahun 2009 hingga 2017. Setiap baris dalam dataset mencakup informasi seperti suhu, kelembaban, tekanan, arah angin, kecepatan angin, dan banyak lagi. Data ini bersumber dari Australian Bureau of Meteorology.
* Kolom RainTomorrow adalah target variable yang mau kita prediksi. Jika “Yes” maka besok harinya disana hujan 1mm atau lebih. https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

## Latar belakang
Latar belakang masalah yang mungkin muncul dari dataset ini adalah untuk memahami pola cuaca di Melbourne selama delapan tahun terakhir. Data ini dapat membantu dalam memprediksi kondisi cuaca di masa depan dan membantu dalam pengambilan keputusan yang lebih baik, seperti pengaturan jadwal aktivitas luar ruangan, perencanaan transportasi, peramalan bencana alam, dan lain sebagainya.

Selain itu, data ini juga dapat digunakan untuk analisis iklim di Melbourne dan daerah sekitarnya. Hal ini dapat membantu ilmuwan untuk memahami perubahan iklim yang terjadi dan dampaknya terhadap lingkungan dan masyarakat setempat. Dengan demikian, data ini dapat berguna bagi berbagai pihak seperti pemerintah, peneliti, dan masyarakat umum.

## Tujuan

Latar belakang masalah yang mungkin muncul dari dataset ini adalah untuk memahami pola cuaca di Melbourne selama delapan tahun terakhir. Data ini dapat membantu dalam memprediksi kondisi cuaca di masa depan dan membantu dalam pengambilan keputusan yang lebih baik, seperti pengaturan jadwal aktivitas luar ruangan, perencanaan transportasi, peramalan bencana alam, dan lain sebagainya.

Selain itu, data ini juga dapat digunakan untuk analisis iklim di Melbourne dan daerah sekitarnya. Hal ini dapat membantu ilmuwan untuk memahami perubahan iklim yang terjadi dan dampaknya terhadap lingkungan dan masyarakat setempat. Dengan demikian, data ini dapat berguna bagi berbagai pihak seperti pemerintah, peneliti, dan masyarakat umum.


## Kesimpulan terhadap model
* Berdasarkan Metrics Performence untuk Logistic Regression dan Support Vector Machine model, keduanya memberikan nilai yang sangat bagus serta kedua model tersebut memiliki akurasi yang tidak jauh berbeda.
* Akurasi LR : 0.7083 lebih besar dibandingkan Akurasi SVM : 0.7091
* Akurasi kedua model tersebut berada pada nilai 70%, sehingga untuk memprediksi kejadian hujan untuk selanjutnya bisa menggunakan SVM atau Logistic Regression tergantung kebutuhan, karena keduanya menghasilkan tingkat akurasi model yang nilainya hampir sama
* Pada kasus ini, performa model LR dan SVM cukup seimbang antara data train dan test dengan perbedaan skor yang tidak terlalu jauh. Oleh karena itu, dapat dikatakan bahwa model ini tidak mengalami overfitting atau underfitting.
* Skor akurasi, presisi, recall dan f1 score pada kedua model sudah cukup baik (> 0.7).
