#### Latihan2
#### Nama :M Raffa Pramuditya
#### NIM  :312210181
#### Kelas:TI 22 A2

## tugas praktikum
###langkah pertama buat terlebih dahulu database dengan nama latihan2.
###untuk membuat database gunakan perintah sebagai berikut:
####create database [nama_database]
contohnya

##lalu, setelah kita membuat database selanjutnya kita masuk kedalam database tersebut dengan perintah sebagai berikut:

use latihan2;
##![image](https://user-images.githubusercontent.com/115911491/231303436-ffd1c502-2d48-4ad9-9bfb-52ee0be4a94d.png)

##2. buat sebuah tabel dengan nama biodata seperti nama, alamat didalam database latihan2.
## untuk membuat table gunakan perintah sebagai berikut:

##CREATE TABLE nama_tabel (nama_field1 tipe _data(ukuran), nama_field2 tipe_data(ukuran), ..., nama_fieldn tipe_data(ukuran));
CREATE TABLE biodata (nama VACHAR (15), alamat TEXT);
###3. tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom trakhir.
## ![image](https://user-images.githubusercontent.com/115911491/231303768-d2bac77f-5f45-4588-91f2-8f1cd3b054cd.png)

## 4. tambahkan kolom id(int11) di awal (sebagai kolom pertama).
### untuk menambahkan kolom pertama yaitu dengan perintah sebagai berikut:

alter table biodata add column id(int11) first;
## ![image](https://user-images.githubusercontent.com/115911491/231304210-1c5b2402-3894-4358-8d57-208ef8fa8eed.png)

## sisipkan sebuah kolom dengan nama phone (varchar 15) setelah kolom alamat.
#### untuk menambahkan kolom setelah kolom lain yaitu dengan perintah after
### ![image](https://user-images.githubusercontent.com/115911491/231304382-13b3641a-0b60-4419-9b90-b0a9abce4301.png)

