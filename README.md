# Smtr2-Praktikum4
# Buat Tabel pegawai dan isi data seperti berikut:
![gambar1](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/d9829bd9-8fee-41c6-bab2-09fce56fda97)
### Tugas Praktikum
1. Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !
2. Tampilkan pegawai yang tunjangannya NULL!
3. Tampilkan pegawai yang tunjangannya tidak NULL!
4. Tampilkan/hitung jumlah baris/record tabel pegawai!
5. Tampilkan/hitung jumlah total gaji di tabel pegawai!
6. Tampilkan/hitung rata-rata gaji pegawai!
7. Tampilkan gaji terkecil!
8. Tampilkan gaji terbesar!
#### 1. Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !
![gambar2](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/86ef07c9-2a00-4f75-acf6-85c3560c9fd4)
#### 2. Tampilkan pegawai yang tunjangannya NULL!
![gambar3](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/7a5a8918-3693-4241-a96d-517798ec1b38)
#### 3. Tampilkan pegawai yang tunjangannya tidak NULL!
![gambar4](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/1154ebad-e2b5-468a-aa05-768aea1ef418)
#### 4. Tampilkan/hitung jumlah baris/record tabel pegawai!
![gambar5](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/9ff15dc8-d879-4a42-9245-ad437a07a15d)
#### 5. Tampilkan/hitung jumlah total gaji di tabel pegawai!
![gambar6](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/7b23faa7-ee26-426a-b157-708e6b1f5056)
#### 6. Tampilkan/hitung rata-rata gaji pegawai!
![gambar7](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/e5c33709-8e3f-4ec4-91b2-6faf542c12d4)
#### 7. Tampilkan gaji terkecil!
![gambar8](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/4804e204-d290-446d-82dd-94d1f440a8dd)
#### 8. Tampilkan gaji terbesar!
![gambar9](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/ed520bd1-1981-4f3f-8c43-e4d580d3e963)

### Kesimpulan
#### Berdasarkan perintah-perintah SQL yang telah dijalankan, kita dapat mencapai beberapa kesimpulan terkait pegawai data dalam tabel "pegawai":
#### - Jumlah pegawai: Jumlah baris atau record dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT COUNT(*) FROM pegawai;. kita perlu menjalankan perintah tersebut untuk mendapatkan jumlah pegawai secara akurat.
#### - Total gaji pegawai: Total gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT SUM(gaji) FROM pegawai;. Perintah ini akan menghasilkan jumlah total gaji dari seluruh pegawai.
#### - Rata-rata gaji pegawai: Rata-rata gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT AVG(gaji) FROM pegawai;. Perintah ini akan menghasilkan nilai rata-rata gaji dari seluruh pegawai.
#### - Gaji terkecil: Nilai gaji terkecil dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MIN(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji terendah.
#### - Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.
#### Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.

## Buat table hewan dan isi datanya seperti berikut:
![gambar10](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/c5ed1ec7-23c5-4680-8dff-b828b004af2b)

@@ -80,5 +88,11 @@

![gambar11](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/a0d73114-9578-44b0-9912-0e7dda8e793b)

## Evaluasi dan Pertanyaan
### Beri kesimpulan Anda!
### Kesimpulan
#### Dalam MySQL, kita dapat menggunakan query untuk menampilkan jumlah hewan berdasarkan kriteria tertentu. Kesimpulannya adalah:
#### - Jumlah hewan berdasarkan pemilik (owner): Dengan menggunakan klausa group by antara kolom "owners" dan "id", serta fungsi COUNT, kita dapat menghitung jumlah hewan yang dimiliki oleh setiap pemilik.
#### - Jumlah hewan berdasarkan spesies: Dengan menggunakan klausa GROUP BY pada kolom "species" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap spesies.
#### - Jumlah hewan berdasarkan jenis kelamin: Dengan menggunakan klausa GROUP BY pada kolom "sex" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap jenis kelamin.
#### - Jumlah hewan berdasarkan spesies dan jenis kelamin (khusus cat dan dog): Dengan menggunakan klausa WHERE untuk memfilter spesies yang diinginkan dan klausa GROUP BY pada kolom "species" dan "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk kombinasi spesies dan jenis kelamin tertentu.
#### - Jumlah hewan berdasarkan jenis kelamin yang diketahui: Dengan menggunakan klausa WHERE untuk memfilter jenis kelamin yang tidak NULL (diketahui) dan klausa GROUP BY pada kolom "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk jenis kelamin yang diketahui.
#### Dengan menggunakan query-query ini, kita dapat memperoleh informasi statistik tentang jumlah hewan berdasarkan kriteria yang relevan dalam basis data MySQL
