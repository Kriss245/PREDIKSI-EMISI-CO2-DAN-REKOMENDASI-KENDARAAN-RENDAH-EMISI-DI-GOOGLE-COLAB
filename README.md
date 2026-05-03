# 📖 DESKRIPSI PROYEK
> Proyek ini merupakan sistem pemodelan berbasis _Machine Learning_ yang dikembangkan menggunakan Google Colab untuk memprediksi tingkat emisi karbon dioksida (CO₂) pada kendaraan. Selain prediksi, sistem ini juga mengintegrasikan fitur rekomendasi kendaraan rendah emisi untuk mendukung keberlanjutan lingkungan.

---

# ✨ FITUR UTAMA
- **Prediksi Emisi CO₂:** Menggunakan algoritma _Random Forest Regression_ untuk akurasi prediksi yang tinggi.
- **Sistem Rekomendasi:** Implementasi _Content-Based Filtering_ untuk merekomendasikan kendaraan alternatif yang relevan.

---

# 🛠️ TEKNOLOGI YANG DIGUNAKAN
- **Bahasa Pemrograman:** Python.
- **Library:** Pandas, NumPy, Scikit-Learn, Matplotlib, dan IPyWidgets.
- **Platform:** Google Colab.
- **Dataset:** _Dataset_ ini bersifat publik terkait Emisi CO₂ kendaraan yang berasal dari platform Kaggle.

---

# 🚀 PANDUAN PENGGUNAAN SISTEM
Untuk menjalankan sistem pemodelan ini secara optimal, silakan ikuti langkah-langkah berikut:
1. **Akses Notebook:** Klik badge Open In Colab berikut: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NyI9-Qzkm8AuGzblO0VMZOpis4S_xg1K?usp=sharing).
2. **Simpan Salinan:** Pilih menu File > _Save a copy in Drive_ agar Anda dapat mengedit dan menyimpan perubahan pada akun Google Anda sendiri.
3. **Unggah Dataset:**
   - Klik ikon Files (gambar folder) pada sidebar sebelah kiri.
   - Klik ikon Upload atau seret file dataset Anda ke dalam direktori `..` tersebut.
4. **Eksekusi Program:** Jalankan seluruh sel kode dengan memilih menu `Runtime` > `Run All` atau gunakan pintasan keyboard `Ctrl + F9`.
5. **Uji Coba Implementasi:** Setelah semua sel selesai dijalankan, Anda dapat langsung mencoba implementasi sistem dengan memasukkan spesifikasi kendaraan pada panel interaktif sesuai dengan preferensi Anda untuk melihat hasil prediksi dan rekomendasi secara real-time.

**Catatan Teknis:** Pastikan koneksi internet stabil saat proses instalasi library dan pemuatan data di Google Colab. Dataset harus diunggah setiap kali sesi runtime baru dimulai (kecuali jika dikoneksikan via Google Drive).

---

# 🖼️ TAMPILAN IMPLEMENTASI SISTEM
### 1. HASIL PREDIKSI EMISI
<p align="center"><img src="https://imgur.com/RCMuLRq.png" width="500"></p>
<p align="center" style="font-size:10px; color:gray;">
<em> Gambar 1. Hasil Prediksi Emisi </em>
</p>

### 2. VISUALISASI EVALUASI MODEL
<p align="center"><img src="https://imgur.com/X3V8N7t.png" width="500"></p>
<p align="center" style="font-size:10px; color:gray;">
<em> Gambar 2. Perbandingan Data Aktual dan Hasil Prediksi </em>
</p>

<p align="center"><img src="https://imgur.com/nkpYxOX.png" width="500"></p>
<p align="center" style="font-size:10px; color:gray;">
<em> Gambar 3. Fitur Paling Berpengaruh (Feature Importance) </em>
</p>

<p align="center"><img src="https://imgur.com/Z0Fgri2.png" width="500"></p>
<p align="center" style="font-size:10px; color:gray;">
<em> Gambar 4. Analisis Error (Residual Plot) </em>
</p>

### 3. IMPLEMENTASI SISTEM
<p align="center"><img src="https://imgur.com/zmY6u0v.png" width="500"></p>
<p align="center" style="font-size:10px; color:gray;">
<em> Gambar 5. Implementasi Sistem </em>
</p>

## 📃 Lisensi

Proyek ini dirilis di bawah [MIT License](https://opensource.org/licenses/MIT).  
Bebas digunakan untuk keperluan pribadi maupun komersial dengan atribusi yang sesuai.
