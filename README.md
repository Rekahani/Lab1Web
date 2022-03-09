# Lab1Web

Dasar - dasar tag HTML (Praktikum 1)

HTML (HyperText Markup Language) adalah suatu bahasa yang menggunakan tanda-tanda tertentu (tag) untuk menyatakan kode-kode yang harus ditafsirkan oleh browser agar halaman tersebut dapat ditampilkan secara benar.

## Membuat Repository

1. login github buat repository baru dengan judul **Lab1web**

![1.png](img/1.png)

2. clone URL github Lab1web

![2.png](img/2.png)
![3.png](img/3.png)

setelah di clone maka akan ada folder dan file README

![4.png](img/4.png)
![5.png](img/5.png)

## Membuat halaman web dasar 

1. buka text editor (disini saya menggunakan VS Code sebagai editor)
2. kemudian kelik **file** pilih **open folder**, buka folde yang tadi di clone (**Lab1Web**)

![6.png](img/6.png)

3. maka akan tampil sebagai berikut

![7.png](img/7.png)

4. buat file baru dengan nama `lab1_tag_dasar.html`

![8.png](img/8.png)

5. buatlah struktur HTML 

![9.png](img/9.png)

dokumen masih kosong 

![11.png](img/11.png)

6. ubah title menjadi `Tag HTML dasar`

![10.png](img/10.png)
![13.png](img/13.png)

7. membuat 2 paragraf menggunakan tag `<p></p>`

![14.png](img/14.png)

maka akan tampil sebagai berikut

![15.png](img/15.png)

8. kemudian mengatur atribut paragraf dengan menggunkan `atribut align`

![16.png](img/16.png)
![17.png](img/17.png)

    atribut align="right" -> mengatur paragraf di posisi kanan
    atribut align="center" -> mengatur paragraf di posisi tengah
    atribut align="left" -> mengatur paragraf di posisi kiri

9. membuat judul halaman menggunakan tag `h1 dan h2`

![18.png](img/18.png)
maka akan tampil sebagaiberikut...
![19.png](img/19.png)

### Tag Heading
    Heading merupakan sebuah judul yang biasanya digunakan pada sebuah halaman artikel pada web.
    Atau terkadang dibeberapa bagian dari halaman web.
    Judul atau heading pada dokumen HTML dapat dibuat dengan menggunakan tag <h1> sampai <h6>.
    Tag <h1> merupakan judul pada lever pertama, kemudian level berikutnya atau sub judul pada tag
    <h2> dan seterusnya sampai tag <h6>.

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

![20.png](img/20.png)

### Contoh format teks

    <p>Teks <b>ini dicetak tebal</b></p>
    <p>Teks <i>ini dicetak miring</i></p>
    <p>Dan ini adalah <sub>subscript</sub> dan <sup>superscript</sup></p>

![30.png](img/30.png)

10. menambahkan gambar pada dokumen dengan menggunakan tag `img`

![21.png](img/21.png)

    <img src="..." alt="..." title="...">

maka akan tampil sebagai berikut

![22.png](img/22.png)


11. membuat link navigasi menggunakan tag `nav` dan tag `a`

![23.png](img/23.png)

    <nav>
      <a href="lab1_tag_dasar.html">Dasar HTML</a>
      <a href="lab1_halaman2.html">Halaman 2</a>
      <a href="https://www.google.co.id/">Halaman Web Eksternal Google</a>
    </nav>

tag `hr` berfungsi menambahkan garis 

![24.png](img/24.png)

## push ke halaman repository

1. pertama buka `git bas` 
2. masuk ke folder `Lab1Web`

    cd Lab1Web

![25.png](img/25.png)

    git status -> untuk memeriksa apakah ada perubahan di repository
    git add "nama file/folder" atau git add . -> untuk memasukan perubahan ke repository
    git commit -m "pesan" -> untuk memberikan pesan atau deskripsi apa saja yang berubah
    git push -> untuk mengirim file dari git bas ke github

![26.png](img/26.png)
![27.png](img/27.png)
![28.png](img/28.png)

maka akan ada file html di github 

![29.png](img/29.png)
