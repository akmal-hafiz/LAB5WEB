# LAB5WEB
<title>Penjelasan Langkah-Langkah Praktikum 5</title>

<h1>Langkah Pertama: Membuat Dokumen HTML Sederhana</h1>
<p align="justify">
    Pada langkah pertama, saya membuat dokumen HTML sederhana dengan nama <code>lab5_javascript.html</code>. 
    Di dalam file ini, saya mempraktikkan penggunaan <code>document.write()</code> dan <code>console.log()</code> untuk menampilkan teks di halaman dan konsol browser.
</p>
<pre>
<code>
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
</code>
</pre>
<img src="" width="300" height="auto" alt="Langkah pertama: Hello World">

<h2>Hasil Langkah Pertama</h2>
<p>Hasil dari langkah ini adalah menampilkan teks "Hello World" di halaman web dan di konsol browser.</p>
<img src="Screenshot 2024-10-29 104005.png" width="300" height="auto" title="Hasil Hello World" alt="Hasil langkah pertama: Hello World">

<h1>Langkah Kedua: Menggunakan Eksternal JavaScript</h1>
<p align="justify">
    Pada langkah kedua, saya membuat file JavaScript eksternal dengan nama <code>eksternal.js</code> dan menghubungkannya ke dokumen HTML melalui tag <code>&lt;script&gt;</code>.
    Dengan cara ini, kode JavaScript terpisah dari HTML sehingga lebih mudah diorganisasi.
</p>
<pre>
<code>
<head>
    <script type="text/JavaScript" src="eksternal.js"></script>
</head>
</code>
</pre>
<img src="" width="300" height="auto" alt="Langkah kedua: Eksternal JavaScript">

<h2>Hasil Langkah Kedua</h2>
<p>Hasil dari langkah ini adalah memisahkan kode JavaScript dari HTML, sehingga lebih mudah dikelola dan dapat digunakan ulang di halaman lain.</p>

<h1>Langkah Ketiga: Menggunakan window.alert()</h1>
<p align="justify">
    Pada langkah ketiga, saya mempraktikkan penggunaan <code>window.alert()</code> untuk menampilkan kotak dialog alert di browser. Alert ini akan muncul ketika halaman dibuka.
</p>
<pre>
<code>
<script>
    window.alert("Selamat datang di JavaScript!");
</script>
</code>
</pre>
<img src="Screenshot 2024-10-29 104131.png" width="300" height="auto" alt="Langkah ketiga: window.alert">

<h2>Hasil Langkah Ketiga</h2>
<p>Hasil dari langkah ini adalah munculnya kotak dialog "ini merupakan pesan untuk anda" setiap kali halaman dibuka.</p>

<h1>Langkah Keempat: Menggunakan Prompt</h1>
<p align="justify">
    Pada langkah ini, saya mempraktikkan penggunaan <code>prompt()</code> untuk menerima input dari pengguna dan menampilkannya kembali di halaman.
</p>
<pre>
<code>
<script>
    var nama = prompt("Masukkan nama Anda:");
    document.write("Selamat datang, " + nama);
</script>
</code>
</pre>
<img src="Screenshot 2024-10-29 104517.png" width="300" height="auto" alt="Langkah keempat: Prompt">

<h2>Hasil Langkah Keempat</h2>
<p>Hasil dari langkah ini adalah munculnya kotak dialog untuk memasukkan nama, dan kemudian nama yang dimasukkan akan ditampilkan di halaman web.</p>

<h1>Langkah Kelima: Dasar Operasi Aritmatika</h1>
<p align="justify">
    Pada langkah ini, saya mencoba operasi dasar aritmatika di JavaScript seperti penjumlahan, pengurangan, perkalian, dan pembagian.
</p>
<pre>
<code>
<script>
    var a = 10;
    var b = 5;
    var hasil = a + b;
    document.write("Hasil penjumlahan: " + hasil);
</script>
</code>
</pre>
<img src="Screenshot 2024-10-29 112716.png" width="300" height="auto" alt="Langkah kelima: Operasi Aritmatika">

<h2>Hasil Langkah Kelima</h2>
<p>Hasil dari langkah ini adalah menampilkan hasil penjumlahan dari variabel <code>a</code> dan <code>b</code> di halaman web.</p>

<h1>Langkah Keenam: Menggunakan Kondisi If-Else</h1>
<p align="justify">
    Pada langkah ini, saya mempraktikkan penggunaan pernyataan <code>if-else</code> untuk membuat kondisi sederhana yang akan memeriksa nilai variabel.
</p>
<pre>
<code>
<script>
    var nilai = 75;
    if (nilai >= 60) {
        document.write("Lulus");
    } else {
        document.write("Tidak Lulus");
    }
</script>
</code>
</pre>
<img src="Screenshot 2024-10-29 113143.png" width="300" height="auto" alt="Langkah keenam: If-Else">

<h2>Hasil Langkah Keenam</h2>
<p>Hasil dari langkah ini adalah menampilkan status kelulusan berdasarkan nilai yang diberikan.</p>

<h1>Langkah Ketujuh: Menggunakan Switch Case</h1>
<p align="justify">
    Pada langkah ini, saya menggunakan pernyataan <code>switch</code> untuk mengecek nilai variabel dan menampilkan pesan berdasarkan nilai tersebut.
</p>
<pre>
<code>
<script>
    var grade = 'B';
    switch(grade) {
        case 'A':
            document.write("Sangat Baik");
            break;
        case 'B':
            document.write("Baik");
            break;
        case 'C':
            document.write("Cukup");
            break;
        default:
            document.write("Tidak Valid");
    }
</script>
</code>
</pre>
<img src="" width="300" height="auto" alt="Langkah ketujuh: Switch Case">

<h2>Hasil Langkah Ketujuh</h2>
<p>Hasil dari langkah ini adalah menampilkan penilaian sesuai dengan nilai yang dimasukkan di variabel <code>grade</code>.</p>

<h1>Langkah Kedelapan: Membuat Form Input</h1>
<p align="justify">
    Pada langkah ini, saya membuat form input sederhana untuk menerima masukan dari pengguna.
</p>
<pre>
<code>
<form>
    Nama: <input type="text" name="nama"><br>
    <input type="submit" value="Submit">
</form>
</code>
</pre>
<img src="" width="300" height="auto" alt="Langkah kedelapan: Form Input">

<h2>Hasil Langkah Kedelapan</h2>
<p>Hasil dari langkah ini adalah sebuah form input sederhana yang dapat menerima masukan nama dari pengguna.</p>

<h1>Langkah Kesembilan: Menggunakan Checkbox</h1>
<p align="justify">
    Pada langkah ini, saya membuat form dengan checkbox yang memungkinkan pengguna untuk memilih beberapa opsi.
</p>
<pre>
<code>
<form>
    <input type="checkbox" name="item1" value="Item 1"> Item 1<br>
    <input type="checkbox" name="item2" value="Item 2"> Item 2<br>
    <input type="checkbox" name="item3" value="Item 3"> Item 3<br>
</form>
</code>
</pre>
<img src="" width="300" height="auto" alt="Langkah kesembilan: Checkbox">

<h2>Hasil Langkah Kesembilan</h2>
<p>Hasil dari langkah ini adalah form dengan checkbox yang bisa digunakan untuk memilih beberapa item.</p>
