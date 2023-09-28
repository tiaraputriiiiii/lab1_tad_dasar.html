# lab1_tad_dasar.html

Persiapan membuka VSCode dengan browser


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/8ca8effb-2ac8-49b7-85a5-362b9275ff9b)


kemudian buat file baru dengan nama #lab1_tag_dasar.html# dan tambahkna tag dasar dokumen HTML


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/3942875e-6920-4971-902a-aecba08c45fd)


kemudian selanjutnya, buka file tersebut pada web browser, misalnya #chrome#


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/93c70efd-ee20-47d1-ab61-7742bf3ce069)


# 1. Membuat paragraf 

Selanjutnya buatlah beberapa paragraf sederhana sebagai berikut

            <!--Ini adalah paragraf pertama-->
            <p align>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman WEb di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
    
            <!--ini adalah paragraf kedua-->
            <p align>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehungga menjadi satu kesatuan. paragraf dibuat dengan menggunakan tag dasr html.</p>


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/f40aa676-e5d7-4c7b-bea0-bb7e002d1bef)


Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser, lihat hasilnya.


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/687674b1-55a8-46dc-9b37-f4f09acac66f)


kemudian atur atribut paragraf seperti berikut, dan amati perubahannya


            <!--Ini adalah paragraf pertama-->
            <p align="centere">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman WEb di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>

            <!--ini adalah paragraf kedua-->
            <p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehungga menjadi satu kesatuan. paragraf dibuat dengan menggunakan tag dasr html.</p>


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/8e9b2db7-af3c-406f-9ad5-01c6848d291b)


simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. selanjutnya silahkan ubah - ubah nilai atributnya (align=justify, left, right, dan center)

align= center dan right


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/f3fe3c8f-db0c-41bc-a002-8c558b97ddd3)


align= justify dan left
![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/6ddf4a00-9a18-4958-89cf-e98b976f1bd2)


hasilnya 


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/7e2b70ec-8cb6-4df1-92e5-bf4cf4e4af86)


# 2. Menambahkan judul 

seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu h1 sampai h6. kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.

            <!--judul paragraf pertama-->
            <h1>Belajar Dasar HTML</h1>
            
            <!--judul paragraf kedua-->
            <h2>Paragraf pada HTML</h2>


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/ca5b31b7-a732-4c67-b55b-1def4fa4d5ac)


simpan perubahannya dan lihat hasilnya dengan melakukan refresh pada browser.


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/be187414-dc78-424c-a79f-0be53c8c95bd)


# 3. Memformat teks 

Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/1dc395f6-e337-4f5a-a371-8f141246b8b7)


# Code 

            <!--judul paragraf pertama-->
            <h1>Belajar Dasar HTML</h1>
            <!--Ini adalah paragraf pertama-->
            <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman WEb</b> di Prodi <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>

# 4. Menyisipkan gambar 

Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external.


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/82d7b9a1-bb4a-4b76-9b13-cc0789961c88)


kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.

            <!--sub judul paragraf-->
            <h3>Menambahkan Gambar</h3>
            <!--menambahkan gambar pada dokumen-->
            <img src="Logo_UPB.jpg" tittle="Logo Universitas Pelita Bangsa">
            

![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/47548423-9ddb-4783-8800-e1c093d5481a)


Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.

            <!--sub judul paragraf-->
            <h3>Menambahkan Gambar</h3>
            <!--menambahkan gambar pada dokumen-->
            <img src="Logo_UPB.jpg" width="200" tittle="Logo Universitas Pelita Bangsa">

# 5. Menambahkan hyperlink 

Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.

            <!--menambahkan link navigasi-->
                <nav>
                    <a href="lab1_tag_dasar.html">Dasar HTML</a>
                    <a href="lab1_halaman2.html">Halaman 2</a>
                    <a href="http://www.google.com">Halaman Web Eksternal</a>
                </nav>
                <hr>

Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag
html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.


![image](https://github.com/tiaraputriiiiii/lab1_tad_dasar.html/assets/115775237/2f829172-3d52-4799-965d-b06713462369)


## Jawab Pertanyaan Berikut

1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

# jawaban:

1. ya, kesalahan penulisan tag dalam kode HTML dapat menyebabkan error atau masalah dalam halaman web. Kesalahan tersebut dapat mencakup tag yang tidak ditutup dengan benar, tag yang tidak valid, atau atribut yang salah
   
2. ya, kesalahan penulisan tag dalam kode HTML dapat menyebabkan error atau masalah dalam halaman web. Kesalahan tersebut dapat mencakup tag yang tidak ditutup dengan benar, tag yang tidak valid, atau atribut yang salah

3.
  1. Atribut `alt` (Alternative Text):
     - Atribut `alt` digunakan untuk memberikan teks alternatif atau deskripsi gambar.
     - Ini memiliki peran penting dalam aksesibilitas web, karena digunakan oleh pembaca layar untuk membantu pengguna yang memiliki masalah penglihatan memahami konten gambar
     - Jika gambar tidak dapat ditampilkan (misalnya, jika berkas gambar tidak dapat dimuat), teks `alt` akan muncul sebagai teks pengganti.
     - Contoh penggunaan: `<img src="gambar.jpg" alt="Sebuah gambar bukit yang indah">`

   2. Atribut `title`:
      - Atribut `title` digunakan untuk memberikan informasi tambahan atau tooltip ketika pengguna mengarahkan kursor mouse ke gambar.
      - Ini tidak memiliki dampak pada aksesibilitas web, tetapi dapat memberikan informasi tambahan kepada pengguna tentang gambar tersebut.
      - Contoh penggunaan: `<img src="gambar.jpg" alt="Sebuah gambar bukit yang indah" title="Pemandangan bukit di musim panas">`

Jadi, perbedaan utama adalah bahwa `alt` digunakan untuk memberikan teks alternatif untuk gambar dan penting untuk aksesibilitas, sementara `title` digunakan untuk memberikan informasi tambahan yang muncul sebagai tooltip saat pengguna mengarahkan kursor mouse ke gambar.

4. Untuk mengatur ukuran gambar dalam HTML, dapat menggunakan atribut `width` (lebar) dan `height` (tinggi). Agar tampilan gambar tetap proporsional, sebaiknya mengisi hanya salah satu dari kedua atribut tersebut, biasanya `width` atau `height`, sementara yang lainnya akan dihitung secara otomatis oleh browser.

Ini dilakukan karena gambar memiliki rasio aspek (aspect ratio), yang merupakan perbandingan antara lebar dan tingginya. Jika mengisi baik `width` maupun `height`, tanpa memperhatikan rasio aspek gambar, gambar tersebut dapat terlihat terdistorsi atau tidak proporsional.

5.
1. `_blank`:
   - Ketika `target="_blank"` digunakan, tautan akan membuka halaman yang ditautkan dalam tab atau jendela browser baru, terpisah dari halaman asal. Ini berguna ketika Anda ingin menjaga pengguna tetap di halaman asal dan membuka tautan eksternal atau tautan yang tidak ingin menggantikan halaman asal.

2. `_self`:
   - Ini adalah nilai default untuk atribut `target`. Ketika `target="_self"` digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab yang sama di mana halaman asal berada. Ini berarti halaman asal akan digantikan dengan halaman yang baru.

3. `_top`:
   - Ketika `target="_top"` digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab paling atas atau paling tinggi dalam tumpukan jendela browser. Jadi, jika halaman asal ada dalam bingkai (frame), tautan akan membuka halaman baru di luar bingkai tersebut.

4. `_parent`:
   - `target="_parent"` digunakan ketika halaman web memiliki bingkai (frame) yang saling terkait. Ini akan membuka tautan di jendela atau tab yang menggantikan bingkai "induk" yang berisi tautan tersebut.
