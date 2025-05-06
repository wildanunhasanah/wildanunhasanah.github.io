---
layout: post
title: "JavaScript"
---

Penjelasan Tentang JavaScript

Apa Itu JavaScript?

**JavaScript** adalah bahasa pemrograman yang digunakan untuk membuat halaman web menjadi **interaktif** dan **dinamis**. Berbeda dengan HTML dan CSS yang hanya mengatur struktur dan tampilan, JavaScript memungkinkan halaman merespons aksi pengguna secara langsung.

Contoh interaksi yang bisa dibuat dengan JavaScript:
- Menanggapi klik tombol
- Mengubah teks atau warna secara dinamis
- Menampilkan/menghilangkan elemen tanpa reload halaman

---

## 🔧 Fungsi Utama JavaScript

JavaScript dapat digunakan untuk:

- **Mengubah elemen HTML dan CSS secara langsung**  
  (misalnya: mengganti warna, menyembunyikan bagian halaman)

- **Validasi formulir**  
  Memeriksa input sebelum dikirim ke server

- **Komunikasi dengan server**  
  Menggunakan teknik seperti **AJAX** atau **fetch** untuk mengambil data tanpa memuat ulang halaman

- **Membuat animasi dan efek transisi**

---

## 🧪 Contoh Dasar JavaScript

Contoh: Mengubah warna latar belakang saat tombol diklik.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Contoh JavaScript</title>
</head>
<body>

  <button onclick="ubahWarna()">Klik saya</button>

  <script>
    function ubahWarna() {
      document.body.style.backgroundColor = "lightblue";
    }
  </script>

</body>
</html>
