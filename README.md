# Technical Project Assignment 2 Dewi Lestari MBI Calkulator

Nama : Dewi Lestari
Email : dewilestari300401@gmail.com
Github : Dwdylestari
Tim : FE-4

1. index.html yaitu koding yang berisi penjelasan singkat mengenai pentingnya pengecekan berat badan denagn menggunakan tautan ke halaman kalkulator BMI.

2. calculator.html yaitu koding yang akan menampilkan halaman MBI Calculator, pada halaman ini anda akan manginputkan berat dan tinggi badan anda, kemudian klik button "Menghitung MBI" setelah itu akan muncul hasilnya.

   - Tag <html> yang menandakan bahwa ini adalah halaman HTML.
   - Tag <head> yang berisi informasi tentang halaman, yaitu judul, meta data, dan link ke file CSS.
   - Tag <body> yang berisi konten utama halaman.
   - Tag <main> yang menandakan bahwa ini adalah bagian utama dari halaman.
   - Tag <div id="container"> untuk membagi halaman menjadi beberapa bagian.
   - Tag <nav> untuk menampilkan navigasi halaman.
   - Tag <h1> untuk menampilkan judul utama halaman.
   - Tag <div class="project"> yang berisi tabel yang berisi form untuk memasukkan berat badan dan tinggi badan dan tombol untuk menghitung BMI.
   - Tag <input> untuk memasukkan nilai berat badan dan tinggi badan.
   - Tag <button> untuk tombol "Menghitung BMI".
   - Tag <div class="result-container"> untuk menampilkan hasil BMI dan status berat badan.
   - Tag <script> untuk memasukkan kode JavaScript.
   - Tag <footer> untuk menampilkan informasi hak cipta.

3. scrip.js yaitu kode yang digunakan untuk menghitung dan menampilkan hasil Body Mass Index (BMI) berdasarkan input berat dan tinggi yang diisi oleh pengguna. Di dalam kode tersebut memiliki beberapa variabel:
   - variabel "hitungBtn" yang digunakan untuk mengambil elemen button dengan id hitung-btn.
   - variabel "beratInput" untuk mengambil elemen input dengan id berat.
   - variabel "tinggiInput" untuk mengambil elemen input dengan id tinggi.
   - variabel "bmiResult" untuk mengambil elemen dengan id bmi.
   - variabel "statusResult" untuk mengambil elemen dengan id status.

Setelah itu, terdapat event listener pada:

- button "hitungBtn" dengan metode addEventListener(). Ketika button tersebut di klik, maka akan dihitung BMI berdasarkan nilai berat dan tinggi yang diambil dari beratInput dan tinggiInput. Jika kedua nilai tersebut valid, maka akan dihitung nilai BMI dengan rumus berat / (tinggi \* tinggi).
- kemudian nilai tersebut akan ditampilkan pada "bmiResult".
- Selain itu, nilai kategori BMI yang sesuai dengan hasil perhitungan juga akan ditampilkan pada "statusResult".
- Jika salah satu atau kedua nilai berat dan tinggi tidak valid, maka pesan error akan ditampilkan pada "statusResult".

4. style.css yaitu kode untuk mempercantik tampilan dari segi warna, gaya huruf, dan gambar pada halaman index.html dan calculator.html.
