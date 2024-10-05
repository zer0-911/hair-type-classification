### Proyek Klasifikasi Gambar: Hair Type

Proyek ini bertujuan untuk mengembangkan model klasifikasi gambar yang mampu mengidentifikasi jenis rambut berdasarkan gambar. Dalam proyek ini, beberapa jenis rambut yang diklasifikasikan termasuk **Straight (lurus)**, **Wavy (bergelombang)**, **Curly (keriting)**, **Kinky (sangat keriting)**, dan **Dreadlocks**. 

### Tahapan Proyek:
1. **Pengumpulan Data**: Gambar berbagai tipe rambut dikumpulkan dan dipersiapkan sebagai dataset untuk melatih model.
   
2. **Preprocessing**: Setiap gambar diproses sebelum digunakan untuk melatih model. Preprocessing ini termasuk resizing gambar menjadi ukuran yang seragam, normalisasi nilai piksel, dan konversi gambar ke tensor.

3. **Model Machine Learning**: Model klasifikasi gambar menggunakan **TensorFlow Lite** untuk mendeteksi tipe rambut dari gambar. Model ini dilatih untuk mengenali pola visual dari setiap jenis rambut.

4. **Inference (Prediksi)**: Setelah model dilatih, gambar baru bisa diinput ke model, yang akan memberikan prediksi jenis rambut. Model ini dioptimalkan untuk berjalan secara lokal menggunakan TensorFlow Lite, sehingga dapat digunakan pada perangkat edge seperti smartphone.

### Manfaat:
- Model ini bisa digunakan dalam berbagai aplikasi seperti sistem rekomendasi produk perawatan rambut, diagnosis virtual untuk tipe rambut, atau bahkan dalam aplikasi kecantikan berbasis AI.

Proyek ini memanfaatkan teknik machine learning yang populer dalam visi komputer untuk menyelesaikan masalah klasifikasi visual secara efisien.