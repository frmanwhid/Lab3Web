1. penjelasan dalam pembuatan list

Deklarasi DOCTYPE Baris pertama <!DOCTYPE html>adalah deklarasi tipe dokumen, yang memberi tahu browser bahwa dokumen tersebut ditulis dalam HTML5.

Elemen HTML Elemen <html>adalah elemen akar dokumen HTML, yang berisi semua elemen lainnya.

Pengodean Bahasa dan Karakter Elemen tersebut <head>berisi metadata tentang dokumen, seperti pengodean bahasa dan karakter. Dalam hal ini:

lang="en"menentukan bahwa bahasa dokumen adalah bahasa Inggris.
<meta charset="UTF-8">menentukan pengkodean karakter dokumen, yaitu UTF-8.
Pengaturan Viewport Mengatur <meta name="viewport" content="width=device-width, initial-scale=1.0">pengaturan viewport untuk dokumen, yang mengendalikan bagaimana halaman ditampilkan pada perangkat yang berbeda.

Elemen Judul Elemen ini <title>menetapkan judul halaman, yang muncul di bilah judul browser dan di hasil mesin pencari. Dalam hal ini, judulnya adalah "HTML Lanjutan".

Elemen Body Elemen <body>berisi konten dokumen HTML.

Elemen Header Elemen ini <header>mendefinisikan bagian header dalam dokumen. Dalam hal ini, elemen ini berisi elemen <h1>dengan teks "Membuat List".

Elemen Bagian Kode tersebut menggunakan tiga <section>elemen, masing-masing dengan atribut unik id:

#order-listberisi daftar berurutan (OL)
#unorder-listberisi daftar tidak berurutan (UL)
#unorder-list(sekali lagi, dengan ID yang sama) berisi daftar deskripsi (DL)
Daftar Berurut (OL) Elemen ini <ol>mendefinisikan daftar berurut, yaitu daftar item yang diberi nomor dalam urutan tertentu. Dalam hal ini, daftar tersebut berisi tiga item:

<li>Pemrograman Web</li>
<li>Sistem Infromasi</li>
<li>Basis Data</li>
Daftar Tak Berurut (UL) Elemen ini <ul>mendefinisikan daftar tak berurut, yaitu daftar item yang tidak diberi nomor. Dalam kasus ini, daftar tersebut berisi tiga item, dan type="square"atribut menentukan bahwa item daftar tersebut harus ditampilkan dengan poin persegi:

<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma & Pemrograman</li>
Daftar Deskripsi (DL) Elemen ini <dl>mendefinisikan daftar deskripsi, yaitu daftar istilah dan deskripsinya. Dalam hal ini, daftar tersebut berisi dua istilah dengan beberapa deskripsi masing-masing:

<dt>Fakultas Teknik</dt>adalah sebuah istilah, dan unsur-unsur berikut <dd>adalah deskripsinya:
<dd>Teknik Industri</dd>
<dd>Teknik Informatika</dd>
<dd>Teknik Lingkungan</dd>
<dt>Fakultas Ekonomi dan Bisnis</dt>adalah istilah lain, dan unsur-unsur berikut <dd>adalah deskripsinya:
<dd>Akutansi</dd>
<dd>Manajemen</dd>
<dd>Bisnis Digital</dd>

2. penjelasan dalam pembuatan form

Deklarasi DOCTYPE Baris pertama <!DOCTYPE html>adalah deklarasi tipe dokumen, yang memberi tahu browser bahwa dokumen tersebut ditulis dalam HTML5.

Elemen HTML Elemen <html>adalah elemen akar dokumen HTML, yang berisi semua elemen lainnya.

Pengodean Bahasa dan Karakter Elemen tersebut <head>berisi metadata tentang dokumen, seperti pengodean bahasa dan karakter. Dalam hal ini:

lang="en"menentukan bahwa bahasa dokumen adalah bahasa Inggris.
<meta charset="UTF-8">menentukan pengkodean karakter dokumen, yaitu UTF-8.
Pengaturan Viewport Mengatur <meta name="viewport" content="width=device-width, initial-scale=1.0">pengaturan viewport untuk dokumen, yang mengendalikan bagaimana halaman ditampilkan pada perangkat yang berbeda.

Elemen Judul Elemen ini <title>menetapkan judul halaman, yang muncul di bilah judul browser dan di hasil mesin pencari. Dalam hal ini, judulnya adalah "HTML Lanjutan".

Elemen Gaya Elemen <style>mendefinisikan blok gaya CSS untuk dokumen.

Gaya CSS Gaya CSS didefinisikan sebagai berikut:

form p > labelmemilih semua labelelemen yang merupakan anak langsung dari pelemen dalam suatu formelemen, dan menerapkan gaya berikut:
display: inline-block;membuat label ditampilkan sebagai elemen blok sebaris.
width: 100%;menetapkan lebar label menjadi 100% dari elemen induknya.
form input[type="text"], form textareamemilih semua inputelemen dengan tipe "teks" dan semua textareaelemen di dalam formelemen, dan menerapkan gaya berikut:
border: 1px solid #197a43;menetapkan batas padat 1 piksel dengan warna #197a43.
form input[type="submit"]memilih semua inputelemen dengan tipe "submit" di dalam formelemen, dan menerapkan gaya berikut:
border: 1px solid #197a43;menetapkan batas padat 1 piksel dengan warna #197a43.
background-color: #197a43;mengatur warna latar belakang tombol kirim ke #197a43.
color: #ffffff;mengatur warna teks tombol kirim menjadi putih.
font-weight: bold;mengatur ketebalan font tombol kirim menjadi tebal.
padding: 5px 15px;Mengatur bantalan tombol kirim menjadi 5 piksel di bagian atas dan bawah, dan 15 piksel di bagian kiri dan kanan.
Elemen Body Elemen <body>berisi konten dokumen HTML.

Elemen Header Elemen ini <header>mendefinisikan bagian header dalam dokumen. Dalam hal ini, elemen ini berisi elemen <h1>dengan teks "Membuat Form".

Elemen Formulir Elemen ini <form>mendefinisikan formulir dalam dokumen, yang berisi kontrol formulir seperti kolom input, kotak centang, dan tombol kirim. Dalam hal ini, formulir memiliki atribut berikut:

action="proses.php"menentukan URL skrip sisi server yang akan memproses data formulir.
method="post"menentukan metode HTTP yang digunakan untuk mengirimkan data formulir.
Elemen Fieldset Elemen <fieldset>mengelompokkan sekumpulan kontrol formulir bersama-sama, dan menyediakan legenda yang menjelaskan pengelompokan tersebut. Dalam hal ini, legendanya adalah "Data Pelanggan".

Kontrol Formulir Formulir berisi kontrol formulir berikut:

Elemen labeldengan teks "Nama", dikaitkan dengan inputelemen dengan tipe "teks" dan ID "nama".
Elemen labeldengan teks "Alamat", dikaitkan dengan textareaelemen dengan ID "alamat".
Elemen labeldengan teks "Jenis Kelamin", terkait dengan dua inputelemen dengan tipe "radio" dan ID "jk_l" dan "jk_p", masing-masing.
Tombol submitdengan nilai "Login".

3. Penjelasan dalam membuat tabel

Deklarasi DOCTYPE Baris pertama <!DOCTYPE html>adalah deklarasi tipe dokumen, yang memberi tahu browser bahwa dokumen tersebut ditulis dalam HTML5.

Elemen HTML Elemen <html>adalah elemen akar dokumen HTML, yang berisi semua elemen lainnya.

Pengodean Bahasa dan Karakter Elemen tersebut <head>berisi metadata tentang dokumen, seperti pengodean bahasa dan karakter. Dalam hal ini:

lang="en"menentukan bahwa bahasa dokumen adalah bahasa Inggris.
<meta charset="UTF-8">menentukan pengkodean karakter dokumen, yaitu UTF-8.
Pengaturan Viewport Mengatur <meta name="viewport" content="width=device-width, initial-scale=1.0">pengaturan viewport untuk dokumen, yang mengendalikan bagaimana halaman ditampilkan pada perangkat yang berbeda.

Elemen Judul Elemen ini <title>menetapkan judul halaman, yang muncul di bilah judul browser dan di hasil mesin pencari. Dalam hal ini, judulnya adalah "HTML Lanjutan".

Elemen Body Elemen <body>berisi konten dokumen HTML.

Elemen Header Elemen ini <header>mendefinisikan bagian header dalam dokumen. Dalam hal ini, elemen ini berisi elemen <h1>dengan teks "Membuat Tabel".

Elemen Tabel Elemen ini <table>mendefinisikan tabel dalam dokumen. Dalam hal ini, ada dua tabel dengan atribut berikut:

border="1"menentukan lebar batas tabel.
cellpadding="4"menentukan bantalan antara konten sel dan batas sel.
cellspacing="0"menentukan jarak antar sel.
Elemen Kepala Tabel (THEAD) Elemen ini <thead>mendefinisikan bagian kepala tabel, yang berisi tajuk kolom. Dalam hal ini, kepala tabel berisi satu baris dengan tiga kolom:

<th>No.</th>mendefinisikan sel tajuk tabel dengan teks "No."
<th>Fakultas</th>mendefinisikan sel tajuk tabel dengan teks "Fakultas".
<th>Program Studi</th>mendefinisikan sel header tabel dengan teks "Program Studi".
Elemen Badan Tabel (TBODY) Elemen ini <tbody>mendefinisikan bagian badan tabel, yang berisi data tabel. Dalam hal ini, badan tabel berisi tiga baris dengan tiga kolom masing-masing:

Baris pertama berisi data "1.", "Teknik", dan "Teknik Informatika".
Baris kedua berisi data "2.", "Teknik", dan "Teknik Industri".
Baris ketiga berisi data "3.", "Teknik", dan "Teknik Lingkungan".
Atribut Rowspan Pada tabel kedua, rowspanatribut digunakan untuk membentangkan sel di beberapa baris. Dalam kasus ini, sel dengan teks "Teknik" membentang di tiga baris.
