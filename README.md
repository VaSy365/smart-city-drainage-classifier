# Sistem Cerdas Tata Kota: Klasifikasi Citra Drainase dan Kondisi Jalan untuk Mitigasi Banjir

## 🌟 Deskripsi Proyek
Proyek ini dikembangkan oleh **Diva Syabina Putri** sebagai solusi berbasis *Artificial Intelligence* (AI) untuk memantau infrastruktur tata kota secara cerdas. Fokus utama model ini adalah melakukan klasifikasi otomatis terhadap kondisi saluran air dan jalan raya guna mendukung sistem peringatan dini banjir (*Early Warning System*) berbasis IoT.

Eksplorasi teknologi ini dilakukan secara elegan menggunakan arsitektur **Convolutional Neural Network (CNN)** untuk mengenali potensi penyumbatan saluran akibat sampah serta deteksi genangan air secara real-time.

## 📊 Analisis Performa Model
Model dilatih menggunakan dataset gambar infrastruktur perkotaan (Banjir, Normal, dan Tersumbat) dengan hasil evaluasi sebagai berikut:
- **Akurasi Pelatihan (Training Accuracy)**: 95.38%
- **Akurasi Validasi (Validation Accuracy)**: 98.12%
- **Loss**: 0.08

Model berhasil mencapai target akurasi di atas 85% dan menunjukkan kurva pembelajaran yang stabil tanpa indikasi overfitting yang signifikan.

## 🛠️ Teknologi & Library
Proyek ini dibangun menggunakan ekosistem Python dan TensorFlow:
- **Bahasa**: Python 3
- **Framework**: TensorFlow & Keras
- **Optimization**: Adam Optimizer
- **Deployment Formats**: SavedModel, TF-Lite, & TFJS

## 📂 Struktur Berkas Submission
Berikut adalah susunan berkas yang disertakan dalam proyek ini:
- `saved_model/`: Model dalam format standar TensorFlow.
- `tflite/`: Model yang dioptimalkan untuk perangkat mobile dan embedded.
- `tfjs_model/`: Model untuk deployment pada aplikasi berbasis web.
- `notebook.ipynb`: Berkas Jupyter Notebook yang berisi alur lengkap dari Data Loading hingga Inference.
- `requirements.txt`: Daftar dependensi library yang digunakan.

## 🚀 Cara Penggunaan
1. Pastikan library yang dibutuhkan telah terpasang:
   `pip install -r requirements.txt`
2. Jalankan berkas `notebook.ipynb` di Google Colab menggunakan runtime **T4 GPU** untuk performa optimal.
3. Gunakan bagian **Inference** di akhir notebook untuk menguji model dengan gambar baru secara interaktif.

---
*Dibuat untuk memenuhi kriteria submission kelas Machine Learning - Dicoding Indonesia.*
