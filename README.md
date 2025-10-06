# hello_world

A new Flutter project.

Nama : Muhammad Bhimantara Wira Eka Putra
Kelas : SIB 3C
Nomor Absen : 25
Matkul : Pemrograman Mobile
Jurusan : Teknologi Informasi
Program Studi : D-IV Sistem Informasi Bisnis

---

# Praktikum 1

Berhasil membuat project Flutter di VSCode.
Langkah ini merupakan dasar untuk memulai pengembangan aplikasi Flutter menggunakan struktur proyek bawaan.

![Praktikum 1 Langkah ke 1-4](image/Screenshot%202025-10-04%20180518.png)
![Gambar](image/Screenshot%20\(267\).png)

---

# Praktikum 2

Menghubungkan perangkat Android dan emulator.

Namun, terjadi masalah pada SDK dan NDK di Android Studio sehingga tampilan hanya muncul di VSCode dan belum bisa dijalankan di emulator.
Sebagai alternatif, digunakan perangkat fisik (smartphone) untuk menjalankan aplikasi Flutter.

![Praktikum 2](image/Screenshot%20\(268\).png)
![Perangkat fisik](image/Gambar%20WhatsApp%202025-10-06%20pukul%2022.56.37_15e2fd12.jpg)
![Perangkat fisik](image/Gambar%20WhatsApp%202025-10-06%20pukul%2022.56.37_8c61babd.jpg)
![Perangkat fisik](image/Screenshot%20\(275\).png)

---

# Praktikum 3

Membuat repository di GitHub dan melakukan commit project Flutter.
Tujuannya adalah untuk menyimpan, memantau perubahan, serta memudahkan kolaborasi dalam pengembangan aplikasi.

![Repository](image/Screenshot%20\(270\).png)
![Commit gitignore](image/Screenshot%202025-10-04%20181410.png)
![Commit Readme](image/Screenshot%202025-10-04%20181410.png)

---

# Praktikum 4 (Menerapkan Widget Dasar)

## Langkah 1

Membuat folder `basic_widgets` di dalam folder `lib` dan membuat file baru bernama `text_widget.dart`.
File ini berfungsi menampilkan teks dengan gaya tertentu.

![Folder basic\_widget](image/Screenshot%202025-10-06%20232949.png)
![Membuat file text\_widget dan mengganti nama](image/Screenshot%202025-10-06%20233028.png)
![Import text\_widget ke main.dart](image/Screenshot%202025-10-06%20234047.png)

**Hasil:**
![Hasil](image/Screenshot%20\(272\).png)

---

## Langkah 2

Membuat file `image_widget.dart` di dalam folder `basic_widgets`.
Kemudian menambahkan folder `assets` untuk menyimpan gambar (misalnya logo Polinema) dan menyesuaikan pengaturan pada file `pubspec.yaml`.

![Membuat file image\_widget](image/Screenshot%202025-10-06%20234255.png)
![Isi file image\_widget](image/Screenshot%202025-10-06%20234431.png)
![Membuat folder assets](image/Screenshot%202025-10-06%20234639.png)
![Menyesuaikan pubspec.yaml](image/Screenshot%202025-10-06%20234548.png)
![Import image\_widget](image/Screenshot%202025-10-06%20235053.png)

Menjalankan perintah:

```
flutter pub get
```

Tujuannya adalah untuk mengambil semua dependencies dan asset yang dibutuhkan oleh proyek.

**Hasil:**
![Hasil](image/Screenshot%20\(273\).png)

---

# Praktikum 5 (Menerapkan Widget Material Design dan iOS Cupertino)

## Langkah 1: Cupertino Button dan Loading Bar

Membuat file `loading_cupertino.dart` di dalam folder `basic_widgets`.
File ini menampilkan tombol dan indikator loading khas iOS (Cupertino Style).

![Membuat file](image/Screenshot%202025-10-07%20002328.png)
![Isi file](image/Screenshot%202025-10-07%20002406.png)
![Penyesuaian main.dart](image/Screenshot%202025-10-07%20002512.png)

**Hasil:**
![Hasil](image/Screenshot%202025-10-07%20002637.png)

---

## Langkah 2: Floating Action Button (FAB)

Membuat file `fab_widget.dart` untuk menampilkan tombol melayang yang dapat menambah nilai counter.

![Membuat file](image/Screenshot%202025-10-07%20003212.png)
![Isi file](image/Screenshot%202025-10-07%20003237.png)
![Penyesuaian main.dart](image/Screenshot%202025-10-07%20003259.png)

**Hasil:**
![Hasil](image/Screenshot%202025-10-07%20003318.png)

---

## Langkah 3: Scaffold Widget

Menyesuaikan file `main.dart` dengan widget `Scaffold` untuk mengatur tata letak aplikasi berdasarkan Material Design.

![Penyesuaian](image/Screenshot%202025-10-07%20004341.png)

---

## Langkah 4: Dialog Widget

Menambahkan fitur dialog untuk menampilkan pesan pop-up interaktif pada pengguna.

![Penyesuaian](image/Screenshot%202025-10-07%20004648.png)
![Penyesuaian](image/Screenshot%202025-10-07%20004706.png)

---

## Langkah 5: Input dan Selection Widget

Menambahkan `TextField` untuk menerima input teks dari pengguna.

![Penyesuaian](image/Screenshot%202025-10-07%20010227.png)

---

## Langkah 6: Date and Time Pickers

Menambahkan fitur pemilihan tanggal menggunakan widget `showDatePicker`.
Fitur ini memungkinkan pengguna memilih tanggal dari kalender interaktif.

**Sebelum diubah:**
![Penyesuaian](image/Screenshot%202025-10-07%20010525.png)

**Setelah diubah:**
![Penyesuaian](image/Screenshot%202025-10-07%20010606.png)

---

# Kesimpulan

Dari serangkaian praktikum di atas, dapat disimpulkan bahwa Flutter menyediakan beragam **widget bawaan** yang memudahkan pengembang dalam membuat antarmuka pengguna.
Flutter juga mendukung gaya **Material Design (Android)** dan **Cupertino (iOS)**, sehingga aplikasi dapat tampil konsisten di berbagai platform.

Selain itu, integrasi dengan **GitHub** serta penggunaan **VSCode** menjadikan proses pengembangan dan manajemen proyek lebih efisien.
Dengan memahami widget dasar dan elemen interaktif seperti tombol, input, serta picker, pengembang dapat membangun aplikasi Flutter dengan tampilan menarik dan fungsional.

---
