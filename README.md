# H1D024115-Pertemuan1-PrakKB
Pengumpulan tugas praktikum Kecerdasan Buatan pertemuan 1.

#Pengimplementasian 3 Konsep Sesuai Instruksi pada Soal
1. Struktur Kontrol

Konsep struktur kontrol yang diimplementasikan pada program ini terdiri dari:

a. Perulangan (Looping)

Perulangan for terdapat pada baris ke-20.
Perulangan ini digunakan untuk mengambil setiap pertanyaan yang terdapat di dalam list pertanyaan, kemudian menampilkannya kepada pengguna serta menerima jawaban dari pengguna.

Perulangan while terdapat pada baris ke-34.
Perulangan ini digunakan untuk memastikan bahwa pengguna hanya memasukkan pilihan “y” atau “n” ketika ditanya apakah ingin melihat skor.

b. Percabangan

Percabangan if-else terdapat pada baris ke-26 sampai 30.
Percabangan ini digunakan untuk mengecek apakah jawaban yang dimasukkan pengguna sesuai dengan jawaban yang benar. Jika jawaban benar maka skor akan bertambah, sedangkan jika salah maka akan muncul pesan bahwa jawaban salah.

Percabangan if terdapat pada baris ke-38.
Percabangan ini digunakan untuk menampilkan skor akhir pengguna jika pengguna memilih “y” untuk melihat skor.

2. Struktur Data

Konsep struktur data yang digunakan dalam program ini adalah list.

List digunakan untuk menyimpan kumpulan pertanyaan kuis yang terdapat pada baris ke-4 sampai 10.
Di dalam list tersebut terdapat tuple yang berisi pasangan antara pertanyaan dan jawaban yang benar.

3. Library

Library yang digunakan pada program ini adalah:

a. random

Library random digunakan untuk mengacak urutan pertanyaan menggunakan fungsi random.shuffle() yang terdapat pada baris ke-12, sehingga urutan soal akan berbeda setiap kali program dijalankan.

b. datetime

Library datetime digunakan untuk menampilkan waktu saat kuis dimulai dengan menggunakan fungsi datetime.datetime.now() pada baris ke-16.
