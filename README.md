# sentiment-analysis-LSTM

## Hasil Confusion Matrix
<img src="https://github.com/taufiq26127/sentiment-analysis-LSTM/blob/main/images/hasil1.jpg?raw=true" alt="Deskripsi Gambar" width="300"/>

## Kesimpulan
Model masih memiliki kekuranga dalam mengklasifikasikan sentiment, dimana model harus ditingkatkan atau mencoba menggunakan algoritma yang lain
 - 197 (True Positives, TP): Jumlah contoh dari kelas positif yang diprediksi dengan benar sebagai positif.
 - 12 (False Positives, FP): Jumlah contoh dari kelas negatif yang diprediksi salah sebagai positif.
 - 32 (False Negatives, FN): Jumlah contoh dari kelas positif yang diprediksi salah sebagai negatif.
 - 116 (True Negatives, TN): Jumlah contoh dari kelas negatif yang diprediksi dengan benar sebagai negatif.
Kesimpulan dari confusion matrix ini adalah bahwa model memiliki akurasi sekitar 87.7%, dengan presisi tinggi pada prediksi positif (94.3%) dan recall yang cukup baik (86.0%). Meskipun begitu, masih terdapat 32 instance yang seharusnya positif namun diprediksi negatif, dan 12 instance yang seharusnya negatif namun diprediksi positif.
