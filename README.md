# Student Performance Factors - Data Cleansing

## Deskripsi
Repository ini berisi Dataset asli berisi sekitar 6.000 baris, tetapi untuk latihan, saya mengambil 300 baris pertama dan menerjemahkan seluruh isi dataset dari bahasa Inggris ke bahasa Indonesia agar lebih mudah dipahami.

## Langkah-langkah Data Cleansing
1. **Standarisasi Nama Kolom**  
   - Mengubah nama kolom dari bahasa Inggris ke bahasa Indonesia.  
   - Menyederhanakan format penamaan agar konsisten.

2. **Mengisi Data Kosong (Missing Values)**  
   - Mengisi nilai yang hilang dengan nilai default atau kategori yang relevan.  
   - Memastikan semua kolom memiliki data yang valid.

3. **Memperbaiki Format Data**  
   - Menyesuaikan format jam belajar, nilai, dan kategori agar konsisten.  
   - Menghapus data yang duplikat atau tidak relevan.

4. **Validasi Data**  
   - Memastikan tidak ada nilai yang salah atau inkonsisten setelah proses cleansing.

## Dataset
- Dataset Awal : `StudentPerformanceFactors`
- Nama File: `StudentPerformanceFactors300_Kotor.csv` → setelah cleansing bisa disimpan sebagai `StudentPerformanceFactors_Cleansed.csv`  
- Jumlah Kolom: X (isi sesuai jumlah kolom final)  
- Jumlah Baris: 300 (atau sesuai dataset)  

## Tools yang Digunakan
- **Python** (Google Colab)  
- **Pandas** untuk manipulasi dan cleansing data  

## Cara Menggunakan
1. Clone repository ini:  
   ```bash
   git clone https://github.com/JasaSK/DataCleansingStudentPerformanceFactors.git
