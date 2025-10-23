# 💾 Implementasi Pembacaan dan Penampilan Data CSV Menggunakan Java Swing

## 🧩 Deskripsi Proyek

Proyek ini merupakan implementasi sederhana dari proses **upload dan pembacaan file CSV** menggunakan **bahasa pemrograman Java** dengan antarmuka **Java Swing**.
Tujuan utama proyek ini adalah memahami bagaimana data eksternal berformat CSV dapat dibaca, diproses, dan ditampilkan secara dinamis ke dalam komponen **JTable**.
Aplikasi ini tidak menggunakan proses CRUD dengan database, melainkan hanya menampilkan data langsung dari file CSV yang diunggah oleh pengguna.

---

## 🚀 Fitur Utama

* 📂 Upload file CSV melalui tombol **“Upload”** pada GUI.
* 🧠 Membaca data CSV menggunakan kelas Java bawaan (`BufferedReader`, `FileReader`).
* 🪄 Menampilkan isi file CSV ke dalam **JTable** secara dinamis.
* 🌐 Mendukung file berformat **CSV UTF-8 (Comma delimited)** agar karakter terbaca dengan benar.

---

## 🎯 Tujuan Praktikum

1. Memahami konsep dasar format **Comma Separated Values (CSV)**.
2. Mempelajari cara **membaca dan memproses file CSV menggunakan Java**.
3. Mengimplementasikan **antarmuka grafis (GUI)** dengan **Java Swing**.
4. Menampilkan data eksternal secara dinamis ke dalam **JTable**.
5. Melatih kemampuan dalam **pengolahan file input/output (I/O)** di Java.

---

## 📋 Langkah Penggunaan

1. 🧾 **Buat file data di Excel**, lalu simpan dengan format:
   `CSV UTF-8 (Comma delimited) (*.csv)`
   
<img width="738" height="185" alt="image" src="https://github.com/user-attachments/assets/c9fd3706-19ec-409a-a68b-88ee91dc11ec" />

<img width="981" height="263" alt="image" src="https://github.com/user-attachments/assets/e7ffd47f-5d70-4da4-9a41-4be9c8dcabf8" />

   
2. ▶️ **Jalankan aplikasi** melalui NetBeans atau command line.
3. 🖱️ Klik tombol **“Upload”** pada tampilan GUI.
   
   <img width="799" height="472" alt="image" src="https://github.com/user-attachments/assets/75741b81-59d3-45e7-afd1-4d34b9593966" />

4. 📁 Pilih file CSV yang telah dibuat.
   
   <img width="725" height="531" alt="image" src="https://github.com/user-attachments/assets/d4aa470c-c83d-412e-b440-27ecac08ce4d" />
   
5. 👀 Data dari file akan otomatis ditampilkan di **JTable**.
   <img width="916" height="542" alt="image" src="https://github.com/user-attachments/assets/64d48230-5dc9-447c-9a45-176116f4aa21" />

    

---

## 📄 Contoh Struktur File CSV dengan pemisah koma(,)

<img width="884" height="751" alt="image" src="https://github.com/user-attachments/assets/da0de92d-5fc3-4fbc-b231-ddf0adb8fa25" />


## ⚙️ Penjelasan Teknis Singkat

Aplikasi ini menggunakan `BufferedReader` untuk membaca setiap baris dari file CSV dan memisahkan nilai antar kolom menggunakan metode `split(",")`.
Data yang diperoleh kemudian dimasukkan ke dalam model tabel (`DefaultTableModel`) dan ditampilkan melalui komponen **JTable** pada antarmuka Swing.

---

## 🧠 Kesimpulan

Dari hasil implementasi, proses pembacaan dan penampilan data dari file CSV menggunakan Java Swing dapat dilakukan dengan memanfaatkan kelas bawaan Java.
Format **CSV UTF-8 (Comma delimited)** penting agar karakter dan kolom data terbaca dengan benar.
Melalui proyek ini, pengguna dapat memahami konsep dasar **pengolahan data eksternal dan visualisasi data dalam GUI Java**.

---

## 👩‍💻 Identitas

**Nama:** Evania Dwi Ananta
**NIM:** 09010624007
**Kelas:** H7B.3 Sistem Informasi
**Mata Kuliah:** Pemrograman Berorientasi Objek
**Dosen Pengampu:** Bayu Adhi Nugroho, Ph.D
**Fakultas Sains dan Teknologi, UIN Sunan Ampel Surabaya – 2025**

---

Apakah kamu mau aku buatkan versi **file README.md**-nya (format Markdown siap diunggah ke GitHub)?
