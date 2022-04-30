# Simakor

## Deskripsi
**Simakor** adalah akronim dari *Sistem Keuangan Organisasi*, yaitu sistem aplikasi berbasis web yang
bertujuan untuk mempermudah manajemen keuangan terutama bagi organisasi dilingkungan kampus atau perguruan tinggi,
namun secara umum sistem manajemen keuangan Simakor dapat digunakan secara luas oleh jenis-jenis organisasi lain.

## Curhat
Projek dari 2016 iseng-iseng diskusi dengan `Userferdi` sebagai bendahara (kalau tidak salah), dan dicoba untuk diwujudkan dengan kapasitas kemampuan programming pada saat itu.
Karena merasa ini salah satu karya jadi, saya coba bug fixing yang errornya 😂. Lucu memang kalau lihat kode sendiri beberapa tahun yang lalu.

## Install
1. Buat database, katakanlah `simakor` dan import file `simakor .sql`
2. Copy file `config-example.php` dan rename menjadi `config.php`. Lalu sesuaikan konfigurasi url, database nya. Catatan, `IS_DEV` hanya dipakai untuk menampilkan error atau tidak. Katakanlah projeknya di set di http://localhost/simakor
3. Pergi ke http://localhost/simakor/setup.php lalu buat pOrganisasi dan pengguna baru. 1 Organisasi = 1 Pengguna (*silly? kinda lol*).
4. Jika tidak ada niatan untuk multiple organisasi/divisi, bisa hapus setup.php (basically it is a registration page)
5. *Congratulations, Your done already*!


# Usage
Please belasjar sendiri aja, sederhana sekali fiturnya hanya:
- Register / Setup
- Login / Logout
- Input Kegiatan (Tambah/Ubah/Hapus/Export Excel)
- Input Rincian Kegiatan (Tambah/Ubah/Hapus/Export Excel), termasuk :
  - Kredit / Debit / Saldo (auto calculate)
  - Foto Bukti (export zip available), 1 Rincian = 1 Foto Bukti 

# *Cheers*
## *Cheers*
### *Cheers*
#### *Cheers*
##### *Cheers*
###### *Cheers*
