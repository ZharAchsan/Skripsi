# Optimasi Support Vector Machine Menggunakan SMOTE Untuk Mengatasi Ketidakseimbangan Data Pada Analisis Sentimen Aplikasi Cloudmoon 
Repository ini berisi proyek skripsi yang mengembangkan sistem analisis sentimen untuk mengklasifikasikan ulasan pengguna pada Aplikasi Cloudmoon di Google Play Store ke dalam tiga kategori: Positif, Negatif, dan Netral. Proyek ini memanfaatkan metode Machine Learning untuk menghasilkan analisis yang akurat dan objektif.

---

# Tentang Pembuat
- Nama : Moch. Achsanul Azhar
- Program Studi : Teknik Informatika
- Perguruan Tinggi : Universitas Nahdlatul Ulama Sunan Giri
Proyek ini diselesaikan sebagai salah satu syarat untuk memperoleh gelar Sarjana Komputer (S.Kom).

---

# Tentang Proyek
Sistem analisis sentimen ini dibangun melalui tahapan:

- Pengumpulan data ulasan Google Play Store
Preprocessing teks (data cleaning, case folding, normalisasi kata, tokenizing, stopword removal, stemming)
- Balancing dataset dengan SMOTE
- Pembobotan kata menggunakan TF-IDF dengan Kombinasi N-Gram
- Pelatihan algoritma Machine Learning:
Support Vector Machine (SVM)
- Evaluasi model untuk mendapatkan performa terbaik
- Implementasi ke sistem berbasis web untuk input review & tampilan hasil

---

# Fitur Utama Sistem Web

- Analisis sentimen otomatis berdasarkan input  
- Visualisasi hasil analisis  
- Riwayat analisis 
- Penyimpanan hasil sentimen  
- Tampilan UI responsif dan user-friendly  

---

# Teknologi yang Digunakan

| Komponen                  | Teknologi                                      |
|--------------------------|-----------------------------------------------|
| Machine Learning         | Python, Scikit-Learn, TF-IDF                  |
| Preprocessing & Balancing| Python                           |
| Web Backend              | Flask      |
| Frontend                 | HTML, CSS, Bootstrap                          |
| Tools Tambahan           | Google Play Scraper                           |
