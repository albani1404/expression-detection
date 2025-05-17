
# 🧠 Deteksi Emosi dari Gambar

Proyek ini merupakan implementasi model deep learning untuk mendeteksi ekspresi atau emosi manusia dari gambar wajah menggunakan Convolutional Neural Networks (CNN) dengan TensorFlow dan Keras.

## 📁 Struktur Proyek

- `deteksi.ipynb` — Notebook utama yang berisi keseluruhan pipeline deteksi emosi.
- Dataset terdiri dari gambar wajah yang dikategorikan berdasarkan label emosi.

## 🔧 Teknologi yang Digunakan

- Python 3.x
- TensorFlow & Keras
- OpenCV
- Scikit-learn
- Matplotlib & Seaborn (visualisasi)
- tqdm (progress bar)

## ⚙️ Alur Pemrosesan

1. **Import Library**  
   Mengimpor semua pustaka yang diperlukan untuk pemrosesan gambar, pemodelan, dan evaluasi.

2. **Preprocessing Data**  
   - Membaca dataset gambar
   - Resize dan normalisasi gambar
   - Split data menjadi training dan validation set

3. **Augmentasi Gambar**  
   Menggunakan `ImageDataGenerator` untuk meningkatkan performa model melalui augmentasi data.

4. **Arsitektur Model CNN**  
   Menggunakan beberapa lapisan `Conv2D`, `MaxPooling2D`, `Flatten`, dan `Dense` untuk klasifikasi gambar.

5. **Pelatihan Model**  
   Model dilatih menggunakan `fit()` dan disimpan ke file jika diperlukan.

6. **Evaluasi Model**  
   - Menampilkan grafik akurasi dan loss
   - Menampilkan confusion matrix dan classification report

## 🚀 Cara Menjalankan

1. Clone repositori ini (jika ada):
   ```bash
   git clone https://github.com/username/deteksi-emosi.git
   cd deteksi-emosi
   ```

2. Instal dependensi:
   ```bash
   pip install -r requirements.txt
   ```

3. Jalankan notebook:
   ```bash
   jupyter notebook deteksi.ipynb
   ```

## 📝 Catatan

- Dataset gambar tidak disediakan dalam repositori ini. Pastikan Anda menyiapkan dataset dengan struktur direktori yang sesuai.
- Model dapat dikustomisasi untuk menyesuaikan jumlah kelas emosi atau arsitektur CNN yang lebih kompleks.

