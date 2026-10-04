<img width="1365" height="767" alt="Screenshot 2026-10-04 103648" src="https://github.com/user-attachments/assets/0a4d47f9-fa7c-4cb6-8128-c941d6c74ce8" /># Lab1Web.
Tugas Post Test Praktikum 1
# Laporan Praktikum Pemrograman Web - Dasar HTML

Dokumentasi ini berisi penjelasan struktur file, elemen-elemen HTML yang digunakan, serta langkah-langkah dalam membuat halaman web **Profil Mahasiswa** sederhana.

---

## 📁 Struktur Direktori Project

```text
Web/
├── index.html
├── halaman2.html
└── Image/
    └── Ilyas Gemoy.jpg
```

---

## 📝 Penjelasan Langkah-Langkah Praktikum

---

### 1. Membuat Halaman Utam / Beranda (`index.html`)
<img width="1365" height="767" alt="Screenshot 2026-10-04 103648" src="https://github.com/user-attachments/assets/1a2fbe6e-585b-47a4-b195-aa3d468115bb" />

<img width="1359" height="767" alt="Screenshot 2026-10-04 103703" src="https://github.com/user-attachments/assets/261ec498-ee13-4cc4-918d-98d5d1ce6de4" />

Halaman `index.html` berfungsi sebagai halaman depan yang memuat navigasi utama, judul profil, dan gambar profil mahasiswa.

#### Kode & Penjelasan Elemen:

*   **`<!DOCTYPE html>`**  
    Mendeklarasikan tipe dokumen sebagai **HTML5** agar browser dapat merender halaman secara benar.
*   **`<html>` dan `<head>`**  
    Pembungkus utama dokumen web dan bagian *head* yang menyimpan metadata halaman.
*   **`<title>Profil Mahasiswa</title>`**  
    Menentukan judul yang akan muncul pada tab browser.
*   **`<nav>` (Navigasi Halaman)**  
    Mengelompokkan tautan (*link*) navigasi:
    *   `<a href="index.html">Beranda</a>`: Mengarah ke halaman utama.
    *   `<a href="halaman2.html">Halaman 2</a>`: Tautan relatif menuju file `halaman2.html`.
    *   `<a href="https://www.google.com">Website Eksternal</a>`: Tautan absolut menuju situs luar (Google).
*   **`<hr>` (Horizontal Rule)**  
    Membuat garis horizontal sebagai pemisah antara navigasi dan konten utama.
*   **`<h1>Profil Mahasiswa</h1>`**  
    Header level 1 untuk menampilkan judul utama halaman.
*   **`<img>` (Menyisipkan Gambar)**  
    Menampilkan gambar profil dengan atribut:
    *   `src="Image/Ilyas Gemoy.jpg"`: Menunjukkan jalur/lokasi file gambar dalam folder `Image/`.
    *   `width="200"`: Mengatur lebar gambar menjadi 200 piksel.
    *   `alt="Foto profil mahasiswa"`: Teks alternatif jika gambar gagal dimuat.
    *   `title="Foto Profil Mahasiswa"`: Teks petunjuk (tooltip) saat kursor diarahkan ke gambar.

---

### 2. Membuat Halaman Detail Data Diri (`halaman2.html`)
<img width="1359" height="767" alt="Screenshot 2026-10-04 103709" src="https://github.com/user-attachments/assets/6f8b29eb-8bf3-4e47-895e-4bcbf7334372" />
<img width="692" height="171" alt="Screenshot 2026-10-04 103725" src="https://github.com/user-attachments/assets/47ba720a-c2ff-4b80-bdc6-5a44ae651176" />

<img width="1361" height="767" alt="Screenshot 2026-10-04 103734" src="https://github.com/user-attachments/assets/0592f54a-95a1-46a2-bb8f-03e6da287115" />


Halaman `halaman2.html` menyajikan informasi detail data diri, format teks khusus, daftar keahlian, dan target belajar.

#### Penjelasan Bagian & Format Teks:

1.  **Header & Teks Biasa (`<h2>`, `<p>`)**
    *   `<h2>Data Diri</h2>`: Sub-judul halaman.
    *   `<p>`: Tag paragraf untuk menampilkan baris teks informasi seperti Nama dan NIM.

2.  **Format Cetak Tebal & Miring (`<b>`, `<i>`, `<strong>`)**
    *   `<b>Teknik Informatika</b>`: Membuat teks **Teknik Informatika** menjadi tebal (*bold*).
    *   `<i>dasar-dasar pengembangan aplikasi web</i>`: Membuat teks menjadi miring (*italic*).
    *   `<strong>Pemrograman Web</strong>`: Memberikan penekanan penting pada teks sehingga tampil tebal secara semantik.

3.  **Subscript dan Superscript (`<sub>`, `<sup>`)**
    *   `H<sub>2</sub>O`: Menggunakan tag `<sub>` untuk membuat angka 2 berada di bawah (*subscript*), penulisan simbol kimia air ($H_2O$).
    *   `x<sup>2</sup>`: Menggunakan tag `<sup>` untuk membuat angka 2 berada di atas (*superscript*), penulisan notasi pangkat ($x^2$).

4.  **Daftar Tak Berurutan (`<ul>` - Unordered List)**
    *   Digunakan pada bagian **Keahlian**.
    *   `<ul>` membuat daftar berbasis poin (*bullet points*), dengan setiap poin dibungkus tag `<li>` (*List Item*):
        *   HTML
        *   CSS
        *   JavaScript

5.  **Daftar Berurutan (`<ol>` - Ordered List)**
    *   Digunakan pada bagian **Target Belajar**.
    *   `<ol>` membuat daftar berurutan berbasis angka (1, 2, 3), dengan setiap item dibungkus tag `<li>`:
        1.  Menguasai HTML
        2.  Menguasai CSS
        3.  Menguasai JavaScript

---
