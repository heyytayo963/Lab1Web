# lab1web

## Membuat Paragraf
```
 <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
  Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
  yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
  tag-tag dasar HTML.</p>
```

![image](https://github.com/adityaputrawijaya/lab1web/assets/115687055/b3feda99-12f7-481c-8c22-0fe9add41796)

## Menambahkan judul
```
<h1 align = "center">BELAJAR HTML</h1>
```

![image](https://github.com/adityaputrawijaya/lab1web/assets/115687055/93326364-2a8a-4ca1-9d3e-8ccb67d889f2)

## Memformat Text
```
<p align = "center">Kami sedang belajar HTML dasar, pada matakuliah <b>Pemrograman Web di Prodi
 Teknik Informatika</b> <a href="https://www.pelitabangsa.ac.id/">Universitas Pelita Bangsa.</a> Pelajaran pertama yang kami dapat
 adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
 </p>
```

![image](https://github.com/adityaputrawijaya/lab1web/assets/115687055/4545d837-ceee-4fff-be09-06860667f7af)


## Menyisipkan Gambar
```
<div class="gambar">
  <h3 align = "center">Menambahkan Gambar</h3>
  <img src="upb.png" alt="logo UPB">
</div>
```

![image](https://github.com/adityaputrawijaya/lab1web/assets/115687055/c85d3da4-7030-4020-9ea3-e6f9e1132a59)


## Menambahkan Hyperlink
```
<a href="https://www.pelitabangsa.ac.id/">Universitas Pelita Bangsa.</a>
```

![image](https://github.com/adityaputrawijaya/lab1web/assets/115687055/b5fe8bb1-fe86-4430-b197-8a73330917b7)


# Latihan Soal
```
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
   error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
   proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
   _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
# Jawaban
2. Tag ```<p>``` pada html diperuntukan untuk membuat paragraf sedangkan tag ```<br>``` pada html diperuntkan untuk membuat line break pada halaman html.
3. Atribute ```<alt>``` pada tag ```<img>``` berfungsi sebagai pemberi deskripsi singkat sedang atribute ```<title>``` memberikan informasi tambahan kepada user tentang       gambar.
4. Tidak, mengisi salah satunya saja sudah cukup

   jika anda ingin mengisi keduanya maka itu akan mengatur gambar secaara presisi dan gambar yang ditampilkan akan persis dan tidak mengubah proporsinya

   jika anda mengisi salah satunya maka akan mempertahankan proporsi gambar aslinya dan hanya mengubah ukuran gambar sesuai atribut yang diisi.
5. _blank
   Efek: Tautan akan membuka halaman yang terkait dalam jendela atau tab browser baru.
   
   _self
   Efek: Tautan akan membuka halaman yang terkait di jendela atau tab yang sama di mana tautan tersebut berada.
   
   _top
   Efek: Tautan akan membuka halaman yang terkait di jendela atau tab baru, menggantikan seluruh halaman web saat ini jika ada beberapa frame atau iframe.
