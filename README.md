# **Laporan Praktikum Flutter – Hello World App**

**Nama:** Muhammad Bhimantara Wira Eka Putra
**Kelas:** SIB 3C
**No. Absen:** 25
**Mata Kuliah:** Pemrograman Mobile
**Jurusan:** Teknologi Informasi
**Program Studi:** D-IV Sistem Informasi Bisnis

---

## **Praktikum 1 – Membuat Project Flutter**

Pada tahap ini, dilakukan pembuatan project Flutter baru di VS Code. Proses ini melibatkan pembuatan struktur folder proyek, file `main.dart`, dan menjalankan aplikasi dasar “Hello World”.

📸 **Dokumentasi:**

* Membuat project Flutter di VS Code
  ![Langkah ke 1–4](image/Screenshot%202025-10-04%20180518.png)
* Tampilan hasil proyek
  ![Tampilan aplikasi](image/Screenshot%20\(267\).png)

---

## **Praktikum 2 – Menghubungkan Perangkat Android dan Emulator**

Tujuan praktikum ini adalah menghubungkan aplikasi Flutter dengan emulator atau perangkat fisik Android.
Namun, terdapat kendala pada konfigurasi SDK dan NDK di Android Studio, sehingga emulator tidak berjalan sempurna.
Sebagai alternatif, dilakukan uji coba menggunakan perangkat fisik.

📸 **Dokumentasi:**

* Emulator tidak terdeteksi sepenuhnya
  ![Emulator](image/Screenshot%20\(268\).png)
* Uji coba perangkat fisik
  ![Perangkat fisik 1](image/Gambar%20WhatsApp%202025-10-06%20pukul%2022.56.37_15e2fd12.jpg)
  ![Perangkat fisik 2](image/Gambar%20WhatsApp%202025-10-06%20pukul%2022.56.37_8c61babd.jpg)
* Tampilan di Android Studio
  ![Tidak terdeteksi](image/Screenshot%20\(275\).png)

---

## **Praktikum 3 – Git dan GitHub**

Langkah ini bertujuan untuk menghubungkan proyek Flutter dengan repositori GitHub.
Proses meliputi inisialisasi repository, commit awal, dan push ke GitHub.

📸 **Dokumentasi:**

* Repository GitHub
  ![Repository](image/Screenshot%20\(270\).png)
* Commit pertama dan kedua
  ![Commit .gitignore](image/Screenshot%202025-10-04%20181410.png)
  ![Commit README](image/Screenshot%202025-10-04%20181410.png)

---

## **Praktikum 4 – Menerapkan Widget Dasar**

### **Langkah 1: Text Widget**

Membuat folder `basic_widgets` dan menambahkan file `text_widget.dart`.
Kemudian dilakukan import ke `main.dart` untuk menampilkan teks dengan gaya tertentu.

📸 **Dokumentasi:**

* Struktur folder dan file
  ![Folder basic\_widgets](image/Screenshot%202025-10-06%20232949.png)
* Isi file `text_widget.dart`
  ![Isi file text\_widget](image/Screenshot%202025-10-06%20233028.png)
* Import ke `main.dart`
  ![Import text\_widget](image/Screenshot%202025-10-06%20234047.png)
* Hasil tampilan
  ![Hasil text\_widget](image/Screenshot%20\(272\).png)

---

### **Langkah 2: Image Widget**

Menambahkan file `image_widget.dart` untuk menampilkan gambar dari folder `assets`.
File `pubspec.yaml` juga disesuaikan untuk menambahkan path gambar.

📸 **Dokumentasi:**

* File `image_widget.dart`
  ![File image\_widget](image/Screenshot%202025-10-06%20234255.png)
* Isi file
  ![Isi image\_widget](image/Screenshot%202025-10-06%20234431.png)
* Folder assets dan gambar logo Polinema
  ![Folder assets](image/Screenshot%202025-10-06%20234639.png)
* Penyesuaian `pubspec.yaml`
  ![pubspec.yaml](image/Screenshot%202025-10-06%20234548.png)
* Perintah `flutter pub get`
  ![flutter pub get](image/Screenshot%202025-10-06%20235240.png)
* Hasil tampilan gambar
  ![Hasil image](image/Screenshot%20\(273\).png)

---

## **Praktikum 5 – Widget Material Design dan Cupertino**

### **Langkah 1: Cupertino Button dan Loading Bar**

Menambahkan file `loading_cupertino.dart` untuk menampilkan tombol bergaya iOS dan indikator loading.

📸 **Dokumentasi:**
![File loading\_cupertino](image/Screenshot%202025-10-07%20002328.png)
![Isi file loading\_cupertino](image/Screenshot%202025-10-07%20002406.png)
![Import di main.dart](image/Screenshot%202025-10-07%20002512.png)
![Hasil Cupertino](image/Screenshot%202025-10-07%20002637.png)

---

### **Langkah 2: Floating Action Button (FAB)**

Menambahkan tombol aksi mengambang (FAB) di tengah bawah layar menggunakan Scaffold.

📸 **Dokumentasi:**
![File fab\_widget](image/Screenshot%202025-10-07%20003212.png)
![Isi file fab\_widget](image/Screenshot%202025-10-07%20003237.png)
![Penyesuaian main.dart](image/Screenshot%202025-10-07%20003259.png)
![Hasil FAB](image/Screenshot%202025-10-07%20003318.png)

---

### **Langkah 3: Scaffold Widget**

Scaffold digunakan untuk membangun struktur tata letak aplikasi berdasarkan Material Design.

📸 **Dokumentasi:**
![Scaffold main.dart](image/Screenshot%202025-10-07%20004341.png)

---

### **Langkah 4: Dialog Widget**

Menambahkan fitur dialog sederhana untuk menampilkan pesan ke pengguna.

📸 **Dokumentasi:**
![Dialog Widget 1](image/Screenshot%202025-10-07%20004648.png)
![Dialog Widget 2](image/Screenshot%202025-10-07%20004706.png)

---

### **Langkah 5: Input dan Selection Widget**

Menggunakan `TextField` untuk menerima input teks dari pengguna.

📸 **Dokumentasi:**
![TextField](image/Screenshot%202025-10-07%20010227.png)

---

### **Langkah 6: Date and Time Picker**

Menambahkan fitur pemilihan tanggal menggunakan `showDatePicker`.

📸 **Dokumentasi:**

* Tampilan sebelum memilih tanggal
  ![Sebelum ubah](image/Screenshot%202025-10-07%20010525.png)
* Tampilan setelah memilih tanggal
  ![Setelah ubah](image/Screenshot%202025-10-07%20010606.png)

---

## **Kesimpulan**


Berdasarkan seluruh rangkaian praktikum yang telah dilakukan, dapat disimpulkan bahwa:

1.Flutter merupakan framework yang efisien untuk membangun aplikasi lintas platform (Android & iOS) menggunakan bahasa Dart.
2.Melalui praktikum ini, mahasiswa telah memahami langkah-langkah dasar dalam pengembangan aplikasi Flutter — mulai dari pembuatan proyek, pengaturan emulator atau perangkat fisik, hingga koneksi dengan GitHub.
3.Mahasiswa mampu menggunakan berbagai widget dasar dan lanjutan, seperti Text, Image, Scaffold, FloatingActionButton, Dialog, TextField, dan DatePicker.
4.Pemahaman tentang struktur layout dan komponen Material Design maupun Cupertino berhasil diterapkan, sehingga aplikasi dapat memiliki tampilan dan interaksi yang sesuai standar UI modern.
5.Praktikum ini menjadi dasar penting sebelum melangkah ke tahap pengembangan aplikasi yang lebih kompleks dengan logika bisnis, state management, dan integrasi backend.
