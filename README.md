# Penjelasan dari setiap Langkah Praktikum

 
Persiapan membuat dokumen HTML dengan nama file **lab3_list.html** seperti berikut
  <img width="600" alt="doctype" src="https://user-images.githubusercontent.com/81312138/114306428-35397880-9b06-11eb-9f26-515538524773.PNG">

## Membuat Ordered List
Ordered List adalah list yang terurut,  Ordered list dibuat dengan tag `<ol>`. Lalu di dalamnya diisi dengan item-item yang akan dimasukkan ke dalam list. Item dibuat dengan tag `<li>` (list item) Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.

<img width="600" alt="ordered_code" src="https://user-images.githubusercontent.com/81312138/114307936-2e156900-9b0c-11eb-838b-1f7dcc888c5e.PNG">
<img width="600" alt="ordered" src="https://user-images.githubusercontent.com/81312138/114307985-69179c80-9b0c-11eb-891c-5d1c33cfa790.PNG">

## Membuat Unorderd List
Unordered list adalah list yang tak terurut yang menggunakan simbol-simbol pada item-nya. Unordered list dibuat dengan tag `<ul>`dan untuk item-nya dibuat juga dengan tag `<li>`.
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada 
section unordered-list, seperti berikut.
<img width="600" alt="Unorderd List_code" src="https://user-images.githubusercontent.com/81312138/114308177-230f0880-9b0d-11eb-8daf-cda4cd880bac.PNG">
<img width="600" alt="unordered" src="https://user-images.githubusercontent.com/81312138/114308180-25716280-9b0d-11eb-9e5c-8afb4ff5fcf8.PNG">

## Membuat Description List
Description List adalah list yang berisi deksripsi atau penjelasan dari sesuatu.

Ada tiga tag yang digunakan untuk membuat description list:

`<dl>` (description list) tag untuk memulai description list;
`<dt>` (description term) tag untuk membuat kata yang akan dideskripsikan;
`<dd>` (description description) tag untuk membuat penjelasan dari kata.
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.

<img width="600" alt="Description_code" src="https://user-images.githubusercontent.com/81312138/114308328-a6c8f500-9b0d-11eb-8b5b-2893b5cd73cf.PNG">
<img width="600" alt="description" src="https://user-images.githubusercontent.com/81312138/114308325-a4669b00-9b0d-11eb-8148-72334a83ac1f.PNG">

## Membuat Tabel
Buat file baru dengan nama **lab3_tabel.html** seperti berikut
<img width="600" alt="doctype_table" src="https://user-images.githubusercontent.com/81312138/114308410-12ab5d80-9b0e-11eb-8a10-6e5169bf7ecd.PNG">

Digunakan untuk menyajikan data dalam bentuk kolom dan baris, tujuannya agar informasi dapat 
ditampilkan secara lebih terstruktur dan tabular.
HTML Table dapat dibuat dengan tag sebagai berikut.
Element Keterangan
`<table>` Mendefinisikan sebuah tabel dalam dokumen HTML.
Atribut: border, cellpadding, cellspacing
`<thead>` untuk membungkus bagian kepala tabel,
`<tbody>` untuk membungkus bagian body dari tabel ,
`<th>` Membuat judul kolom ,
`<tr>` Mendefinisikan baris dalam tabel ,
Atribut: align (left, center, right), valign (top, middle, 
bottom) ,
`<td>` Mendefinisikan kolom tabel ,
Atribut: align (left, center, right), valign (top, middle, 
bottom), colspan, rowspan ,
Tag yang paling penting untuk diingat adalah tag `<table>`, `<tr>`, dan `<td>`. Sementara tag yang lain 
adalah tambahan (opsional), boleh digunakan boleh tidak.
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:

<img width="500" alt="doctype_table" src="https://user-images.githubusercontent.com/81312138/114308696-ecd28880-9b0e-11eb-8314-289dccb499d0.PNG">
<img width="500" alt="table_code" src="https://user-images.githubusercontent.com/81312138/114308688-eb08c500-9b0e-11eb-8392-622af4510a05.PNG">
<img width="500" alt="table" src="https://user-images.githubusercontent.com/81312138/114308698-ed6b1f00-9b0e-11eb-81c5-f4bd43106631.PNG">

## Menggabungkan Sel Data
Sel data pada tabel dapat digambugkan untuk keperluan tertentu. Untuk menggabungkan sel secara 
vertikal menggunakan atribut `rowspan` dan untuk menggabungkan sel secara horizontal
menggunakan atribut `colspan`. Atribut tersebut dapat ditambahkan pada tag `td` (tabel data) dengan 
nilai atributnya adalah jumlah sel yang akan digabungkan. 
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk 
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara 
horizontal). 

<img width="600" alt="rowspan_code" src="https://user-images.githubusercontent.com/81312138/114308852-6c605780-9b0f-11eb-85f7-ee127a5c74a1.PNG">
<img width="600" alt="rowspan" src="https://user-images.githubusercontent.com/81312138/114308850-6a969400-9b0f-11eb-840a-db97958ec666.PNG">

## Membuat Form
Web tidak hanya berfungsi untuk menampilkan informasi, namun dapat juga menerima data dari 
pengunjungnya. Salah satu cara untuk mengambil data dari pengunjung adalah dengan 
menggunakan form. Form pada web berlaku sama halnya dengan formulir di dunia nyata. Form 
dapat diisi kemudian diproses dengan program tertentu, baik dari sisi server ataupun dari sisi 
client. 
Untuk membuat form digunakan tag `<form>` dengan atribut `action` dan `method`. Atribut action
untuk menentukan aksi yang akan digunakan pada saat form dikirim. Dan method adalah untuk 
menentukan metode yang digunakan dalam mengirimkan data.
Atribut `action` dapat diisi dengan url endpoint yang akan memproses data.
Atribut `enctype`: Mendefinsikan cara encoding data sebelum dikirimkan. Biasanya digunakan 
jika ingin meng-upload file.
Atribut `method`: Metode pengiriman data.
`GE`T: Data dikirimkan bersama URL.
`POST`: Data dikirimkan terpisah dari URL.

<img width="600" alt="doc_form_code" src="https://user-images.githubusercontent.com/81312138/114309068-1b9d2e80-9b10-11eb-901f-d34e759c1eb5.PNG">
<img width="600" alt="form_code" src="https://user-images.githubusercontent.com/81312138/114309065-193ad480-9b10-11eb-8dec-82a597462acc.PNG">
<img width="600" alt="form" src="https://user-images.githubusercontent.com/81312138/114309073-1d66f200-9b10-11eb-910c-ede1399c4994.PNG">

## Menambahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan **CSS** seperti berikut.
ile CSS berada terpisah dari dokumen HTML. Karena itu, dibutuhkan jembatan untuk menghubungkan kedua file ini. Jika tidak terhubung, browser akan gagal menyatukan desain dari file CSS. `<link rel="stylesheet" href="Masukkan file CSS">`
Style sheet dalam atribut link rel bermakna untuk memberitahu browser bahwa file eksternal yang disisipkan berjenis style sheet dengan ekstensi .css.
<img width="600" alt="style_code" src="https://user-images.githubusercontent.com/81312138/114309133-66b74180-9b10-11eb-8915-a7f29681a9f9.PNG">
<img width="600" alt="style" src="https://user-images.githubusercontent.com/81312138/114309139-69199b80-9b10-11eb-8079-a55c8906ea4b.PNG">
