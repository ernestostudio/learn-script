## Pembelajaran Python 🐍 (Awal)

Python dikandung pada akhir 1980-an oleh Guido van Rossum di Centrum Wiskunde & Informatica (CWI) di Belanda sebagai penerus bahasa pemrograman ABC , yang terinspirasi oleh SETL , yang mampu menangani pengecualian (dari start plus kemampuan baru di Python 3.11) dan berinteraksi dengan sistem operasi Amoeba . Implementasinya dimulai pada Desember 1989. Van Rossum memikul tanggung jawab tunggal untuk proyek tersebut, sebagai pengembang utama, hingga 12 Juli 2018, ketika dia mengumumkan "liburan permanen" dari tanggung jawabnya sebagai "diktator yang baik hati seumur hidup" Python, sebuah gelar yang diberikan oleh komunitas Python kepadanya untuk mencerminkan dirinya. komitmen jangka panjang sebagai pembuat keputusan utama proyek. Pada Januari 2019, pengembang inti Python aktif memilih Dewan Pengarah beranggotakan lima orang untuk memimpin proyek.

## Syntax
Sytax adalah adalah aturan yang tanda digabungkan untuk membuat pernyataan. Jika Anda menganggap kata-kata dari bahasa menjadi tanda-tanda, maka sintaks adalah aturan yang menempatkan tanda-tanda sama untuk membuat pernyataan, mengajukan pertanyaan, dan menghasilkan ucapan-ucapan lainnya.

Contoh 1
```py
print("Hii 👋")
```
Contoh 2
```py
if 10 > 8:
  print("Nilai dari 10 lebih besar daripada 8")
```
> **Warning** <br/>
> Perhatian beberapa syntax pada script. contoh dibawah ini syntax yang salah karena kesalahan pada tab space
```py
if 10 > 8:
print("Nilai dari 10 lebih besar daripada 8")
```
Output:
```cmd
   File "<stdin>", line 2
   print("Nilai dari 10 lebih besar daripada 8")
         ^
IndentationError: expected an indented block after 'if' statement on line 1
```

## Komentar
pasti seringkali melihat komentar pada script yang seperti contoh dibawah ini
```js
/*
* @name Aktif
*/
function Aktif(nama, options) {
...
```
komentar diatas pada script javascript, namun bagai mana dengan python?

Contoh
```py
# Isi komentar
print("a")
```
Contoh ke 2
```py
"""
Komentar ini dapat menutup dari atas sampai bawah dengan " (tanda kutip tiga kali).
dan jangan lupa tutup komentar kembali dengan tanda kutip 3 kali
"""
```

## Variabel
mungkin pernah mendengarkan kata ini dipelajaran, ya kamu pernah mendengar.
variable sering sekali ada dipelajaran matematika, terkadang menggunakan kata `x` dan `z` untuk menjadi variabel.
variabel adalah setiap karakteristik, jumlah, atau kuantitas yang dapat diukur atau dihitung.

dalam bahasa pemrograman variabel dipakai untuk memudahkan menyimpan value sementara, atau permanen (tidak bisa diubah)

Contoh
```py
nama = "Aldiyansyah bin aziz"
print(nama)
```
