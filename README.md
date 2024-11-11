# **Assignment-3**
Nomor 1<br>
Melakukan konversi warna seperti:<br>
a. BGR ke RGB untuk tampilan yang benar<br>
b. BGR ke Grayscale untuk pemrosesan lebih lanjut<br>
c. Grayscale ke Binary untuk segmentasi gambar<br>
Menganalisis Histogram:<br>
a. Plot histogram gambar asli untuk melihat distribusi intensitas warna<br>
b. Plot histogram grayscale untuk analisis kecerahan<br>
Melakukan pooling Min, Max, Avg. Lalu melakukan Image Enhancement dengan CLAHE<br>

Nomor 2<br>
Menggunakan dataset MNIST Handwritten Digits (10 kelas), lalu mengimplementasi Transfer Learning dengan CNN-based Pre-trained Models.<br>
a. Dengan jumlah epoch yang sama Transfer Learning dengan freezing layer menghasilkan akurasi akhir yang lebih buruk, Semakin banyak layer yang di-freeze maka Akurasi awal (epoch) semakin rendah Waktu training dan validasi semakin cepat.<br>
b. Freezing layer mengurangi kemampuan model untuk beradaptasi pada dataset baru: Model tidak dapat belajar mengupdateParameters lapisan yang di-freeze. Namun, freezing juga mempercepat waktu komputasi. Semakin banyak layer yang di-freeze, semakin sedikit parameter yang dapat ditraining. Menghasilkan akurasi awal yang lebih rendah. Tetapi proses training dan validasi menjadi lebih cepat.<br>

Nomor 3 <br>
Melakukan perbedaan image Classification dan Object Detection dengan Menggunakan dataset video YouTube dan Real-time Object Detection menggunakan CNN-based Pre-trained Models.<br>
Mengklasifikasikan satu gambar ke dalam satu kategori dengan Fokus pada identifikasi keseluruhan gambar. Mendeteksi dan mengklasifikasi satu atau lebih objek dalam gambar, Fokus pada identifikasi dan lokalisasi objek-objek lalu menganalisis akurasi deteksi video:<br>
Lalu Implementasi real-time object detection dengan model pre-trained, Pemahaman perbedaan image classification dan object detection, Kemampuan menganalisis faktor-faktor yang mempengaruhi akurasi deteksi.<br>

Nomor 4 <br>
Melakukan komputasi menggunakan GPU dengan domain Natural Language Understanding (NLU) dengan dataset: Disaster Tweets untuk Text Classification menggunakan model pre-trained BERT<br>
Dengan menggunakan BERT:<br>
a. BERT adalah model pre-trained yang powerful untuk pemrosesan bahasa alami<br>
b. Arsitektur Transformer encoder-decoder memungkinkan pemodelan konteks dua arah<br>
c. Dapat diterapkan secara efektif untuk berbagai tugas NLP, termasuk klasifikasi teks<br>
Dengan teknis: Aktivasi GPU (CUDA) untuk mempercepat komputasi, Pembagian dataset menjadi (training, validation, dan test),Pengaturan hyperparameter: batch size, epoch, learning rate, Melakukan fine-tuning model BERT dengan dataset yang ada, Penyesuaian hyperparameter jika akurasi awal belum memuaskan.
