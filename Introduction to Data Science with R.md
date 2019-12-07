# Introduction to Data Science with R

## Data Scientist dan R
Halo, selamat datang di course perkenalan DQLab yang menandai perjalanan Anda sebagai _Data Scientist_! <br/>
_Data Scientist_ sendiri adalah profesi yang sangat menjanjikan saat ini, dimana Anda akan merubah data-data yang sebelumnya tidak kelihatan berguna menjadi informasi yang berharga. Untuk mewujudkan hal itu, seorang _data scientist_ tetap memerlukan suatu software yang penggunaan cukup simpel namun kuat (_simple but powerful_). Nah, software tersebut dinamakan R yang merupakan software pemrograman untuk data.

## Apa dan kenapa R?
R adalah nama sebuah bahasa pemrograman sekaligus software untuk pengolahan data dan grafik. <br/>
R sangat popular saat ini karena tiga hal berikut: <br/>
- Banyak pilihan pengolahan data dengan jumlah fitur yang sangat komplit dari grafik sampai _machine learning_.
- Lebih cepat dipelajari dan dijalankan untuk mengolah data dibandingkan dengan bahasa lain. 
- R bersifat gratis dan _open source_ yang artinya tidak perlu biaya lisensi yang biasanya sangat mahal untuk software pengolahan data.

## Perusahaan mana yang sudah menggunakan R?
"Tidak ada asap tanpa api", demikian suatu peribahasa yang menyatakan tidak ada rumor tanpa ada fakta yang menyertai. R sedemikian populer juga disebabkan karena digunakan perusahaan-perusahaan besar dunia. Beberapa diantaranya adalah AirBnB untuk _data science_, Microsoft untuk menambahkan fungsionalitas di produk-produknya, Uber untuk analisa statistik, Facebook untuk _behavior analysis_, dan lain-lain.

## (Quiz) Kenapa menggunakan R?
Pilih beberapa jawaban, kenapa banyak Data Scientist di seluruh dunia menggunakan R?
- [x] Lebih mudah dipelajari
- [ ] Lebih berkualitas, walaupun mahal
- [x] Kaya akan fitur
- [x] Bersifat gratis dan _open source_

## (Coding) "Hello World"
Dalam setiap pembelajaran pemograman, memunculkan tulisan "Hello World" sebagai tradisi dunia pada saat mulai belajar programming :)
Mari kita lakukan hal yang sama untuk R dengan halaman Live Code Editor ini. <br/>
**Tugas Praktek** <br/>
Cobalah ketikkan "Hello World" (tulis persis dengan huruf besar, huruf kecil dan tanda kutipnya) pada bagian Code Editor. <br/>
Klik tombol Run Code untuk menjalankan R dan mengeluarkan hasil di bagian Console.

Code Editor: <br/>
```
"Hello World"
```

Console: <br/>
```
> "Hello World"
[1] "Hello World"
```

## (Coding) Praktek Angka dan Perhitungan
Mari kita lanjutkan kembali praktek sederhana dengan R, kali ini Anda diminta untuk melakukan perhitungan sederhana dengan angka dan penjumlahan sederhana. <br/>
**Tugas Praktek** <br/>
Ketikkan pada Code Editor rumus 10 + 7, dan jalankan dengan tombol Run Code. <br/>
17 adalah hasil perhitungan dari rumus 10 + 7. Abaikan simbol > dan [1] untuk saat ini.

Code Editor: <br/>
```
10+7
```

Console: <br/>
```
> 10+7
[1] 17
```

## (Coding) Variable dalam R
Penggunaan variable pada pemrograman sangat penting untuk menampung angka maupun teks di R dengan suatu nama. <br/>
**Tugas Praktek** <br/>
Pada Code Editor masukan code untuk membuat variable `a = 5`. Ini artinya variable a diisi dengan angka 5. Selanjutnya tambahkan lagi `print(a)`. Ini digunakan untuk mencetak isi variable a. Klik tombol Run Code dan amati yang dimuncul di Console.

Code Editor: <br/>
```
a = 5
print(a)
```

Console: <br/>
```
> a = 5
> print(a)
[1] 5
```

## (Coding) Comment pada R
Comment merupakan teks untuk menambahkan keterangan pada code kita, sehingga kita akan ingat apa yang dilakukan ketika membuka kembali code tersebut. Comment tidak dianggap sebagai code yang bisa dieksekusi. <br/>
Pada R penggunaan comment adalah dengan mengawali suatu teks dengan tanda '#'. <br/>
**Tugas Praktek** <br/>
Ketikkan suatu komentar setelah perhitungan matematika `10 + 7 #Ini adalah baris komentar`. Cobalah jalankan dengan Run Code. Dari proses ini kelihatan bahwa comment tidak diproses oleh R, jadi yang ditampilkan hanya hasil perhitungan matematika.

Code Editor: <br/>
```
10 + 7 #Ini adalah baris komentar
```

Console: <br/>
```
> 10 + 7 #Ini adalah baris komentar
[1] 17
```

## Vector pada R
Vector adalah suatu struktur data yang dapat menyimpan lebih dari satu data yang digunakan pada di R. Penggunaannya sangat sederhana, yaitu menggunakan fungsi c disertai data-data yang ingin disimpan.

```c(5, 10, 20)```

Ini artinya Anda menyimpan nilai 5, 10 dan 20 dalam satu struktur. Dan jika Anda ingin menyimpan rangkaian angka yang terutut, misalkan angka 1 sampai dengan 20 dapat diketikkan sebagai berikut.

```c(1:20)```

## (Coding) Praktek Penggunaan Vector - Bagian Satu
Ketikkan perintah c(3, 10, 15) pada Code Editor. Klik tombol Run Code dan perhatikan output yang dihasilkan pada bagian Console. Terlihat perintah c(3, 10, 15) ini membuat tiga rangkaian angka yaitu 3, 10 dan 15 yang disimpan dan ditampilkan bersamaan dalam suatu vector.

Code Editor: <br/>
```
c(3, 10, 15)
```

Console: <br/>
```
> c(3, 10, 15)
[1]  3 10 15
```

## (Coding) Praktek Penggunaan Vector - Bagian Dua
Selain mengetikkan satu per satu data pada vector, kita juga bisa membuat rangkaian data dengan operator titik dua. Cobalah ketik perintah c(1:5) pada Code Editor. Klik tombol Run Code dan perhatikan output yang dihasilkan pada bagian Console sebagai berikut. Terlihat perintah c(1:5) membuat vector dengan lima rangkaian angka yang dimulai dari 1 dan diakhiri nilai 5. <br/>

Code Editor: <br/>
```
c(1:5)
```

Console: <br/>
```
> c(1:5)
[1] 1 2 3 4 5
```

## (Coding) Menggunakan Fungsi Summary
Kekuatan di R adalah fungsi analisa yang kaya, salah satunya adalah fungsi bernama summary yang bisa digunakan 
untuk mensimpulkan data yang lagi kita proses. Cobalah ketik perintah untuk melihat karakteristik dari vector berikut.

```summary(c(1:5))```

Jalankan dan Anda akan mendapatkan hasil pada Console seperti berikut. Ini artinya dari vector tersebut terdapat angka paling kecil 1 (Min), angka paling besar 5 (Max), angka rata-rata 3 (Mean), dan angka tengah 3 (Median). Untuk 1st Qu dan 3rd Qu kita abaikan dulu.

Code Editor: <br/>
```
summary(c(1:5))
```

Console: <br/>
```
> summary(c(1:5))
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
      1       2       3       3       4       5
```
---

Selamat untuk Anda!<br/>
Anda baru saja mempelajari dasar awal Bahasa Pemrograman R sebagai langkah awal menjadi seorang Data Scientist. <br/>
Masih banyak modul pelajaran yang akan Anda pelajari lebih dalam  untuk mengaplikasikan teknik _data science_ secara tepat menggunakan berbagai studi kasus Industri.
