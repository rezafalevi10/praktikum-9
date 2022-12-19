# praktikum-9

Mencari
Dasbor
Tarik permintaan s
Masalah
Ruang kode
Pasar
Mengeksplorasi
Sponsor
Pengaturan
@rezafalevi10 rezafalevi10
 1 kontributor
53 baris (30 slok)  2,72 KB
Praktikum 9
Nama : mochammad reza falevi
NIM : 312210156
Kelas : TI. 22.B1
Contoh dan Penjelasan Modul Praktikum 13
1. Berikut adalah fungsi yang mengubah suhu dari derajat Kelvin menjadi derajat Fahrenheit. Karena tidak ada derajat Kelvin yang didapat, fungsi tersebut ditebus jika melihat suhu negatif.
208232159-2b286b13-53a9-4d40-b83e-efa40f909c42

Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback... AssertionError artinya terjadi error pada pernyataan pernyataan.

2. Contoh ini untuk membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.
prak 9

208232774-4146e137-d051-47c8-8432-8e1f8936e12a

hasil: Konten tertulis dalam file berhasil

3. Contoh ini mencoba membuka file di mana Anda tidak memiliki izin menulis, sehingga menimbulkan kekhawatiran.
208233322-41ef7a58-a485-4632-99a5-29a10950fae6

Mengapa hasilnya error? r adalah read - Membuka file untuk membaca, akan error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, coba dan ditampilkan lagi.

4. Contoh keempat
208242848-5e8f3f5d-5a07-4bb7-81c2-c211f3c23da0

Hasil diatas bukan error, karena finally dijalankan ketika try dan exception dijalankan. Dan berhasil dibuat filenya setelah dijalankan.

5. Contoh pengecualian tunggal
208243105-f48bd09a-f68c-4cda-ad11-64b3b7b4950b

Hasilnya : Argumen tidak mengandung angka invalid literal for int() dengan basis 10: 'xyz' ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di kecuali ValueError, Argument: ganti koma dengan seperti kecuali ValueError sebagai Argument:agar tidak error. Jika dijalankan akan muncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.

6. Contoh dan argumen keenam
208243725-a8418191-cedb-436b-8719-2c4d27a95c3a

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada kenaikan "Level tidak valid!", ganti level tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1.
