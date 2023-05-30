# Smtr2-Praktikum4
<img width="960" alt="gambar 1 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/3caf29b3-da21-428b-b3cc-7fb36496be23">
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
<img width="736" alt="gambar Praktikum 1 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/c108dd9d-438d-42df-a934-92096374a03f">
#### 2. Tampilkan pegawai yang tunjangannya NULL!
<img width="714" alt="gambar praktikum 2 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/1916828d-63e7-4fa7-a00e-a235aad55942">
#### 3. Tampilkan pegawai yang tunjangannya tidak NULL!
<img width="800" alt="gambar praktikum 3 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/372b7aef-fda5-478a-8b8a-307d760eac65">
#### 4. Tampilkan/hitung jumlah baris/record tabel pegawai!
![gambar 4 praktikum ok](https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/7232b419-97e6-4ef3-bed9-8528897e0bae)
#### 5. Tampilkan/hitung jumlah total gaji di tabel pegawai!
<img width="625" alt="gambar praktikum 5 ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/c09e86ec-4470-4b24-9eb7-75705aa19697">
#### 6. Tampilkan/hitung rata-rata gaji pegawai!
<img width="772" alt="gambar 6 praktikum ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/46b45923-6389-4a55-b660-938be82f1855">
#### 7. Tampilkan gaji terkecil!
<img width="555" alt="gambar 7 praktikum ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/c3f1ee1f-ef9a-41ba-9da2-016c89d60b33">
#### 8. Tampilkan gaji terbesar!

<img width="495" alt="gambar 8 praktikum ok" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/172a73c8-fe71-466b-bf7d-65da5e304053">

### Kesimpulan
#### Berdasarkan perintah-perintah SQL yang telah dijalankan, kita dapat mencapai beberapa kesimpulan terkait pegawai data dalam tabel "pegawai":
#### - Jumlah pegawai: Jumlah baris atau record dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT COUNT(*) FROM pegawai;. kita perlu menjalankan perintah tersebut untuk mendapatkan jumlah pegawai secara akurat.
#### - Total gaji pegawai: Total gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT SUM(gaji) FROM pegawai;. Perintah ini akan menghasilkan jumlah total gaji dari seluruh pegawai.
#### - Rata-rata gaji pegawai: Rata-rata gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT AVG(gaji) FROM pegawai;. Perintah ini akan menghasilkan nilai rata-rata gaji dari seluruh pegawai.
#### - Gaji terkecil: Nilai gaji terkecil dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MIN(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji terendah.
#### - Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.
#### Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.

## Buat table hewan dan isi datanya seperti berikut:
<img width="371" alt="gambar table hewan" src="https://github.com/Akramfarrasanto/Praktikum-4-Basis-Data/assets/115552876/1aed8694-0460-4c82-83f8-09e7d3e9c2a8">
@@ -80,5 +88,11 @@

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
