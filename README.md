# 📘 UTS Sistem Berbasis Pengetahuan  
**Semester Genap 2025/2026**

## 📌 Deskripsi Proyek  
Proyek ini merupakan tugas Ujian Tengah Semester (UTS) pada mata kuliah **Sistem Berbasis Pengetahuan**.  

Pada proyek ini, kami membangun sistem berbasis pengetahuan untuk **rekomendasi tempat wisata di Bali** menggunakan metode inferensi dan probabilistik.

Pendekatan yang digunakan adalah **Project-Based Learning (PBL)**.

---

## 👥 Anggota Kelompok  
- DANICA NASYWA PUTRINIAR – 2341760122 
- DINI ELMININGTYAS RAHAYU WILUJENG – 2341760180 
- IMEL THERESIA BR SEMBIRING – 2341760046
- MOHAMMAD SYIFA'UL FAJ ISMUNIR - 2341760054
- MUHAMMAD ULIL FAHMI MA'RIFATULLOH - 2341760194

---

## 🎯 Tujuan  
- Mengolah dataset menjadi data siap pakai  
- Membangun sistem rekomendasi wisata  
- Mengimplementasikan metode berbasis pengetahuan  
- Membandingkan performa metode  
- Menentukan metode terbaik secara akademis  

---

## 📂 Dataset  

- **Nama File**: `dataset_tempat_wisata_bali.xlsx`  
- **Jumlah Data**: 761  
- **Jumlah Fitur**: 8  

### Deskripsi Atribut:
- `nama` → Nama tempat wisata  
- `kategori` → Jenis wisata  
- `kabupaten_kota` → Lokasi wilayah  
- `rating` → Nilai rating  
- `preferensi` → Karakteristik wisata  
- `link` → Referensi  
- `latitude` → Koordinat lintang  
- `longitude` → Koordinat bujur  

---

## ⚙️ Tahapan Pengerjaan  

### Data Preprocessing  
- Menghapus data kosong / tidak valid  
- Transformasi dan normalisasi data  
- Encoding kategori dan preferensi  
- Seleksi fitur  

---

## 🧠 Metode yang Digunakan  

### Forward Chaining  
Penalaran dimulai dari fakta untuk menghasilkan kesimpulan berdasarkan aturan.

### Backward Chaining  
Penalaran dimulai dari tujuan (goal) dan ditelusuri ke fakta pendukung.

### Teorema Bayes  
Menghitung probabilitas suatu hipotesis berdasarkan evidence.

Rumus:  
P(H|E) = (P(E|H) × P(H)) / P(E)

### Certainty Factor  
Mengukur tingkat keyakinan terhadap suatu hasil berdasarkan evidence.

---

## 📊 Analisis Hasil  

- **Forward Chaining** → Cocok untuk rule sederhana  
- **Backward Chaining** → Fleksibel untuk kebutuhan spesifik  
- **Bayes** → Adaptif dan berbasis probabilitas  
- **Certainty Factor** → Memberikan tingkat kepercayaan hasil  

### Kesimpulan  
Metode terbaik: **FC/BC (Full)**  

Alasan:  
- Mampu menangani ketidakpastian  
- Lebih fleksibel terhadap input  
- Hasil lebih akurat  

---

## ▶️ Catatan  
Implementasi sistem tersedia dalam file Jupyter Notebook/Colab (.ipynb) pada repository ini.
