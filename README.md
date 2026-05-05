Sistem Cerdas Tata Kota: Klasifikasi Citra Drainase dan Kondisi Jalan untuk Mitigasi Banjir

🌟 Deskripsi Proyek
Proyek ini dikembangkan oleh Diva Syabina Putri sebagai solusi berbasis Artificial Intelligence (AI) untuk pemantauan infrastruktur tata kota. Model ini dirancang untuk mendeteksi potensi penyumbatan saluran air dan genangan secara otomatis guna mendukung sistem mitigasi banjir yang cerdas.

Eksplorasi ini menggunakan arsitektur Convolutional Neural Network (CNN) yang telah dioptimalkan dengan Batch Normalization untuk mengenali pola kompleks pada citra drainase.

📊 Analisis Performa Model (Revisi Terbaru)
Berdasarkan revisi kriteria terbaru, model telah melalui pengujian ketat pada data yang belum pernah dilihat sebelumnya (unseen data):

Total Dataset: 3475 citra.

Pembagian Data (Physical Split): Data dibagi secara fisik menjadi folder Train (80%), Validation (10%), dan Test (10%) untuk menjamin objektivitas evaluasi.

Akurasi Testing Akhir: 86.78%.

Karakteristik Model: Menunjukkan kurva pembelajaran yang sehat (nanjak) dengan stabilitas tinggi pada klasifikasi objek sulit seperti sampah/sumbatan.

🛠️ Teknologi & Library
Proyek ini dibangun menggunakan ekosistem Python dan TensorFlow terbaru:

Bahasa: Python 3.12+

Library Utama: TensorFlow, Keras, Split-Folders, Matplotlib

Optimization: Adam Optimizer dengan Learning Rate Scheduling

Deployment Formats: SavedModel (Keras v3 Export), TF-Lite, & TFJS

📂 Struktur Berkas Submission
Berkas ini telah disusun ulang agar sesuai dengan standar revisi:

saved_model/: Model dalam format SavedModel terbaru (hasil model.export).

tfjs_model/: Model untuk deployment pada aplikasi berbasis web.

model.tflite: Model yang dioptimalkan untuk perangkat mobile dan embedded.

Submission_Akhir_Diva.ipynb: Notebook lengkap dengan grafik performa dan evaluasi testing murni.

requirements.txt: Daftar dependensi library terbaru.

🚀 Cara Penggunaan
Pasang library: pip install -r requirements.txt.

Buka Notebook di Google Colab dan pastikan dataset ZIP sudah terhubung dari Drive.
Jalankan cell Inference untuk menguji deteksi kondisi infrastruktur secara real-time.

Dibuat oleh Diva Syabina Putri - Mahasiswi Sistem Informasi Universitas Raharja (Class of 2023).
