# Proyek Rangkaian Logika: Kontrol 7-Panel Display

Repositori ini berisi file desain, data untuk proyek Ujian Akhir Semester (UAS) mata kuliah Sistem Digital. Proyek ini bertujuan untuk mengontrol tujuh panel display terpisah berdasarkan serangkaian input.

---

## Deskripsi Proyek

Proyek ini adalah implementasi dari sebuah sistem digital di mana sebuah rangkaian logika utama memproses input untuk menghasilkan output yang ditampilkan pada tujuh panel. Berdasarkan nama file, kemungkinan besar panel tersebut adalah 7-segment display yang digunakan untuk menampilkan angka atau karakter.

---

## Struktur File

Repositori ini terdiri dari beberapa jenis file yang saling mendukung:

### 1. File Desain Utama (`.dwm`)
* File inti dari proyek ini adalah sebuah file dengan ekstensi `.dwm`, yang skema lengkapnya dapat dilihat pada gambar di atas.
* **Saran:** Sangat disarankan untuk mengunggah file `.dwm` asli ke repositori ini. Hal ini akan memungkinkan desain untuk dianalisis, diuji, dan disimulasikan secara interaktif oleh orang lain yang memiliki software yang sesuai.

### 2. File Data Logika (`.csv`)
* File-file `.csv` ini diekspor dari Excel dan berisi tabel kebenaran atau data logika yang dibutuhkan untuk setiap komponen.
* **`Desain.csv`**: Kemungkinan berisi tabel kebenaran master yang memetakan semua kemungkinan input ke output yang diinginkan untuk seluruh panel.
* **`Panel1.csv` hingga `Panel7.csv`**: Setiap file ini mewakili data logika untuk satu panel display, yang secara berurutan berfungsi untuk menampilkan:
    * **Panel 1:** Huruf **'M'**
    * **Panel 2:** Huruf **'I'**
    * **Panel 3:** Huruf **'S'**
    * **Panel 4:** Huruf **'H'**
    * **Panel 5:** Huruf **'B'**
    * **Panel 6:** Huruf **'A'**
    * **Panel 7:** Huruf **'H'**

---

## Cara Menggunakan

* **Melihat Desain Rangkaian:**
    * Desain visual dapat dilihat langsung pada gambar `Cuplikan layar 2025-06-17 230850.png`.
    * Untuk membuka file desain interaktif (`.dwm`), gunakan software seperti **Digital Works**.

* **Melihat Data Logika:** File `.csv` dapat dibuka menggunakan program spreadsheet apa pun, seperti **Microsoft Excel**, **Google Sheets**, atau **LibreOffice Calc**, untuk menganalisis tabel kebenaran.
