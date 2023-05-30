# Smtr2-Praktikum4
# Buat Tabel pegawai dan isi data seperti berikut:
![gambar1](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/81b1ef31-e138-4427-baa7-0c299b1b586d)
# Tugas Praktikum
1. Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !
2. Tampilkan pegawai yang tunjangannya NULL!
3. Tampilkan pegawai yang tunjangannya tidak NULL!
4. Tampilkan/hitung jumlah baris/record tabel pegawai!
5. Tampilkan/hitung jumlah total gaji di tabel pegawai!
6. Tampilkan/hitung rata-rata gaji pegawai!
7. Tampilkan gaji terkecil!
8. Tampilkan gaji terbesar!
# 1. Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !
![gambar2](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/c229f444-f3ee-43b8-9eab-3ea02da74584)
#### 2. Tampilkan pegawai yang tunjangannya NULL!
![gambar3](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/7d64c9e1-fd86-4a43-bf4a-da162e3d8e4a)
#### 3. Tampilkan pegawai yang tunjangannya tidak NULL!
![gambar4](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/39dd8a0d-f195-44d6-8775-d08e30c3cbc3)
#### 4. Tampilkan/hitung jumlah baris/record tabel pegawai!
![gambar5](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/176bd267-8bc2-4de5-a5f6-88fd1c2de337)
#### 5. Tampilkan/hitung jumlah total gaji di tabel pegawai!
![gambar6](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/43663a3d-d3f1-4143-a39d-b71d94cc69c5)
#### 6. Tampilkan/hitung rata-rata gaji pegawai!
![gambar7](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/ca53e017-bff9-4e8a-9ced-f84124af2407)
#### 7. Tampilkan gaji terkecil!
![gambar8](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/d92fc34a-48f6-49fe-b489-9c62dbf5a8fb)
#### 8. Tampilkan gaji terbesar!
![gambar9](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/2e1eaf51-13f7-42d6-9211-c567f5363adf)
### Kesimpulan
#### Berdasarkan perintah-perintah SQL yang telah dijalankan, kita dapat mencapai beberapa kesimpulan terkait pegawai data dalam tabel "pegawai":
#### - Jumlah pegawai: Jumlah baris atau record dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT COUNT(*) FROM pegawai;. kita perlu menjalankan perintah tersebut untuk mendapatkan jumlah pegawai secara akurat.
#### - Total gaji pegawai: Total gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT SUM(gaji) FROM pegawai;. Perintah ini akan menghasilkan jumlah total gaji dari seluruh pegawai.
#### - Rata-rata gaji pegawai: Rata-rata gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT AVG(gaji) FROM pegawai;. Perintah ini akan menghasilkan nilai rata-rata gaji dari seluruh pegawai.
#### - Gaji terkecil: Nilai gaji terkecil dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MIN(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji terendah.
#### - Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.
#### Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.

## Buat table hewan dan isi datanya seperti berikut:
![gambar10](https://github.com/AbiyanfarasDanuyasa/Smtr2-Praktikum4/assets/115562487/951ab20a-1ad8-4bad-b837-d82d7a36945a)

![gambar 6 hewan](https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/2b1c31c7-e922-4da6-abcd-90a29c98c3be)

## Evaluasi dan Pertanyaan
### Beri kesimpulan Anda!
### Kesimpulan
#### Dalam MySQL, kita dapat menggunakan query untuk menampilkan jumlah hewan berdasarkan kriteria tertentu. Kesimpulannya adalah:
#### - Jumlah hewan berdasarkan pemilik (owner): Dengan menggunakan klausa group by antara kolom "owners" dan "id", serta fungsi COUNT, kita dapat menghitung jumlah hewan yang dimiliki oleh setiap pemilik.
#### - Jumlah hewan berdasarkan spesies: Dengan menggunakan klausa GROUP BY pada kolom "species" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap spesies.
#### - Jumlah hewan berdasarkan jenis kelamin: Dengan menggunakan klausa GROUP BY pada kolom "sex" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap jenis kelamin.
#### - Jumlah hewan berdasarkan spesies dan jenis kelamin (khusus cat dan dog): Dengan menggunakan klausa WHERE untuk memfilter spesies yang diinginkan dan klausa GROUP BY pada kolom "species" dan "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk kombinasi spesies dan jenis kelamin tertentu.
#### - Jumlah hewan berdasarkan jenis kelamin yang diketahui: Dengan menggunakan klausa WHERE untuk memfilter jenis kelamin yang tidak NULL (diketahui) dan klausa GROUP BY pada kolom "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk jenis kelamin yang diketahui.
#### Dengan menggunakan query-query ini, kita dapat memperoleh informasi statistik tentang jumlah hewan berdasarkan kriteria yang relevan dalam basis data MySQL.
