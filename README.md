# Pertemuan 05 Perulangan Python

Nama: Zakiyatus Salsabila
NIM: 2225250225
Kelas: 3F

## Tujuan
Menggunakan for dan while untuk menyelesaikan masalah iteratif.

## Cara Menjalankan
python3 kuis/kuis2_deret_aritmetika.py

## Algoritma Kuis 2
1. Masukkan nilai suku pertama (a), beda (d), dan banyak suku (n).
2. Periksa nilai n. Jika n kurang dari atau sama dengan 0, masukkan kembali nilai n sampai valid.
3. Atur nilai total menjadi 0.
4. Gunakan perulangan for sebanyak n kali.
5. Hitung setiap suku dengan rumus a + i * d.
6. Tampilkan setiap suku dan tambahkan nilainya ke total.
7. Setelah perulangan selesai, tampilkan jumlah seluruh suku.


## Hasil Pengujian
| Test Case | Input | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|---|
| 1 | a=2, d=3, n=5 | Suku: 2, 5, 8, 11, 14; Jumlah: 40 | Suku: 2, 5, 8, 11, 14; Jumlah: 40 | Berhasil |
| 2 | a=10, d=-2, n=4 | Suku: 10, 8, 6, 4; Jumlah: 28 | Suku: 10, 8, 6, 4; Jumlah: 28 | Berhasil |
| 3 | a=1.5, d=0.5, n=3 | Suku: 1.5, 2.0, 2.5; Jumlah: 6.0 | Suku: 1.5, 2.0, 2.5; Jumlah: 6.0 | Berhasil |

## Refleksi
Pada tugas ini saya belajar menggunakan perulangan for dan while dalam program Python. Perulangan for digunakan untuk menghasilkan suku deret aritmatika sesuai dengan jumlah suku yang dimasukkan. Setiap perulangan akan menghitung nilai suku berdasarkan nilai awal, beda, dan posisi suku.

Saya juga belajar bahwa variabel total harus diberi nilai awal 0 sebelum perulangan dimulai. Setelah itu, setiap suku yang dihasilkan ditambahkan ke dalam total sehingga diperoleh jumlah seluruh suku.

Penggunaan while digunakan untuk melakukan validasi pada nilai n. Jika pengguna memasukkan n yang bernilai 0 atau negatif, program akan meminta pengguna memasukkan nilai kembali sampai mendapatkan nilai yang lebih dari 0. Dengan adanya validasi ini, program dapat berjalan sesuai dengan aturan yang sudah ditentukan.

Kesalahan yang dapat terjadi dalam program adalah salah menentukan batas perulangan, salah menuliskan rumus suku, atau lupa menginisialisasi variabel total. Kesalahan tersebut dapat menyebabkan jumlah suku atau hasil penjumlahan menjadi tidak sesuai.

Setelah melakukan pengujian dengan beberapa test case, hasil suku dan jumlah yang diperoleh sudah sesuai dengan hasil yang diharapkan. Dari tugas ini saya menjadi lebih memahami cara kerja perulangan, penggunaan validasi input, serta cara mengakumulasikan nilai dalam sebuah perulangan.