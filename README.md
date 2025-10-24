# Lab5Web
# Muhamad Wafa Mufida Zulfi
# 312410334
# TI.24.A4
# Pemograman Web 1
# Agung Nugroho, S.Kom,. M.Kom.

## Tugas 
<img width="510" height="110" alt="image" src="https://github.com/user-attachments/assets/459ef5ea-8b20-4d6b-a5e9-549c13601cd8" />

Tujuan
Mempelajari dasar pemrograman JavaScript, meliputi cara menulis script di dalam HTML, penggunaan alert, prompt, function, operator aritmatika, kondisi, perulangan, serta manipulasi elemen form dan HTML DOM.

1. Pengenalan JavaScript
Contoh penggunaan document.write dan console.log untuk menampilkan teks di halaman dan di konsol.
```
<!DOCTYPE html>
<html>
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <p>Contoh document.write dan console.log</p>

    <script>
        document.write("Hello World<br>");
        console.log("hello world");
    </script>
</body>
</html>
```
Penjelasan:

document.write() menulis teks langsung ke halaman web.
console.log() menampilkan teks ke konsol (bisa dilihat lewat Inspect → Console).
2. JavaScript Dasar

## a. Pemakaian Alert sebagai Property Window
```
<html>
<head>
    <title>alert box</title>
</head>
<body>
<script language="javascript">
<!--
    window.alert("ini merupakan pesan untuk anda");
//-->
</script>
</body>
</html>
```
Penjelasan: Menampilkan pesan ke pengguna melalui pop-up alert box.

## b. Pemakaian Method dalam Objek
```
<html>
<head>
    <title>skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
<script language="javascript">
<!--
    document.write("selamat mencoba javascript<br>");
    document.write("semoga sukses!");
//-->
</script>
</body>
</html>
```
Penjelasan:
document.write() digunakan untuk menulis teks secara langsung di halaman web.
Teks dapat digabung dengan tag HTML seperti <br> untuk ganti baris.
## C. Pemakaian Prompt
```
<html>
<head>
    <title>pemasukan data</title>
</head>
<body>
<script language="javascript">
<!--
    var nama = prompt("siapa nama anda?", "masukkan nama anda");
    document.write("hai, " + nama);
//-->
</script>
</body>
</html>
```
Penjelasan: prompt() meminta input teks dari pengguna, lalu hasilnya ditampilkan dengan document.write().

## d. Pembuatan Fungsi dan Cara Pemanggilannya
```
<html>
<head>
    <title>contoh program javascript</title>
<script language="javascript">
    function pesan() {
        alert("memanggil javascript lewat body onload");
    }
</script>
</head>
<body onload=pesan()>
</body>
</html>
```
Penjelasan: Fungsi pesan() akan dijalankan otomatis saat halaman dimuat (onload).

# 3. Dasar Pemrograman di JavaScript
## a. Operasi Dasar Aritmatika
```
<html>
<head>
    <title>contoh program javascript</title>
<script language="javascript">
    function test(val1, val2) {
        document.write("<br>perkalian : val1*val2 = " + val1 * val2 + "<br>");
        document.write("pembagian : val1/val2 = " + val1 / val2 + "<br>");
        document.write("penjumlahan : val1+val2 = " + (val1 + val2) + "<br>");
        document.write("pengurangan : val1-val2 = " + (val1 - val2) + "<br>");
        document.write("modulus : val1%val2 = " + (val1 % val2) + "<br>");
    }
</script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick="test(9,4)">
</body>
</html>
```
Penjelasan: Menampilkan hasil operasi aritmatika sederhana menggunakan dua nilai (9 dan 4).

## b. Seleksi Kondisi (if...else)
```
<html>
<head>
    <title>contoh if-else</title>
</head>
<body>
<script language="javascript">
<!--
    var nilai = prompt("nilai (0-100): ", 0);
    var hasil = "";
    if (nilai >= 60)
        hasil = "lulus";
    else
        hasil = "tidak lulus";
    document.write("hasil: " + hasil);
//-->
</script>
</body>
</html>
```
Penjelasan: Membandingkan nilai input pengguna dan menampilkan hasil lulus atau tidak lulus.

## c. Penggunaan Operator Switch untuk Seleksi Kondisi
```
<html>
<head>
    <title>contoh program javascript</title>
<script language="javascript">
    function test() {
        val = window.prompt("input nilai (1-5):");
        switch (val) {
            case "1": document.write("bilangan satu"); break;
            case "2": document.write("bilangan dua"); break;
            case "3": document.write("bilangan tiga"); break;
            case "4": document.write("bilangan empat"); break;
            case "5": document.write("bilangan lima"); break;
            default: document.write("bilangan lainnya");
        }
    }
</script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick="test()">
</body>
</html>
```
Penjelasan: switch digunakan untuk menyeleksi kondisi berdasarkan nilai tertentu.


