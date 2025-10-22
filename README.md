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
   
   <img width="666" height="172" alt="image" src="https://github.com/user-attachments/assets/bbe10dcc-7c1c-484e-a00b-fe8ae9f81d8a" />
   
   <img width="981" height="263" alt="image" src="https://github.com/user-attachments/assets/f892631e-ed14-470b-b250-4bb70e18a071" />
   
2. ▶️ **Jalankan aplikasi** melalui NetBeans atau command line.
3. 🖱️ Klik tombol **“Upload”** pada tampilan GUI.
   
   <img width="694" height="411" alt="image" src="https://github.com/user-attachments/assets/5bc21658-dfe4-4d10-8bb7-e957f12dd7cd" />
   
4. 📁 Pilih file CSV yang telah dibuat.
   
   <img width="606" height="444" alt="image" src="https://github.com/user-attachments/assets/0e33df3b-f57f-4dc1-90b0-1166058b07ef" />
   
   <img width="413" height="234" alt="image" src="https://github.com/user-attachments/assets/ffe69153-87f7-49a9-85a1-c1a282118cd1" />
   
5. 👀 Data dari file akan otomatis ditampilkan di **JTable**.
   
    

---

## 📄 Contoh Struktur File CSV dengan pemisah koma(,)

<img width="1013" height="751" alt="image" src="https://github.com/user-attachments/assets/68fff34e-0df1-4a74-8ad3-4606e3b452cf" />


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
