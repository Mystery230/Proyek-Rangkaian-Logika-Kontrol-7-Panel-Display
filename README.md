# Proyek Rangkaian Logika: Kontrol 7-Panel Display

Repositori ini berisi file desain, data, dan dokumentasi visual untuk proyek Ujian Akhir Semester (UAS) mata kuliah Sistem Digital. Proyek ini adalah implementasi nyata dari rangkaian logika kombinasional untuk menampilkan nama **"ADITYA"** pada tujuh buah 7-segment display.

---

## Desain Rangkaian Logika

Berikut adalah cuplikan layar dari desain rangkaian logika utama yang dibuat menggunakan software desain (kemungkinan besar Digital Works). Rangkaian ini memproses input untuk mengaktifkan segmen yang sesuai pada masing-masing dari tujuh display untuk membentuk huruf yang diinginkan.

![Desain Rangkaian Logika Proyek](<Cuplikan layar 2025-06-17 230850.png>)

---

## Struktur File

Repositori ini terdiri dari beberapa jenis file yang saling mendukung:

### 1. Gambar Desain (`.png`)
* `Cuplikan layar 2025-06-17 230850.png`
    * File ini adalah bukti visual dan referensi utama dari skema rangkaian logika yang telah dirancang.

### 2. File Desain Utama (`.dwm`)
* File inti dari proyek ini adalah sebuah file dengan ekstensi `.dwm`, yang skema lengkapnya dapat dilihat pada gambar di atas.
* **Saran:** Sangat disarankan untuk mengunggah file `.dwm` asli ke repositori ini. Hal ini akan memungkinkan desain untuk dianalisis, diuji, dan disimulasikan secara interaktif oleh orang lain yang memiliki software yang sesuai.

### 3. File Data Logika (`.csv`)
* File-file `.csv` ini diekspor dari Excel dan berisi tabel kebenaran atau data logika yang dibutuhkan untuk setiap komponen.
* **`Desain.csv`**: Kemungkinan berisi tabel kebenaran master yang memetakan semua kemungkinan input ke output yang diinginkan untuk seluruh panel.
* **`Panel1.csv` hingga `Panel7.csv`**: Setiap file ini mewakili data logika untuk satu panel display, yang secara berurutan berfungsi untuk menampilkan:
    * **Panel 1:** Huruf **'A'**
    * **Panel 2:** Huruf **'D'**
    * **Panel 3:** Huruf **'I'**
    * **Panel 4:** Huruf **'T'**
    * **Panel 5:** Huruf **'Y'**
    * **Panel 6:** Huruf **'A'**
    * **Panel 7:** (Kemungkinan kosong, karakter spesial, atau bagian dari NIM)

---

## Cara Menggunakan

* **Melihat Desain Rangkaian:**
    * Desain visual dapat dilihat langsung pada gambar `Cuplikan layar 2025-06-17 230850.png`.
    * Untuk membuka file desain interaktif (`.dwm`), gunakan software seperti **Digital Works**.

* **Melihat Data Logika:** File `.csv` dapat dibuka menggunakan program spreadsheet apa pun, seperti **Microsoft Excel**, **Google Sheets**, atau **LibreOffice Calc**, untuk menganalisis tabel kebenaran.
