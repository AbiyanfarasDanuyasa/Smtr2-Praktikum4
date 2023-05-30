# Smtr2-Praktikum4
Buat Table pegawai dan isi datanya seperti berikut:
gambar 1 ok
Tugas Praktikum
Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !
Tampilkan pegawai yang tunjangannya NULL!
Tampilkan pegawai yang tunjangannya tidak NULL!
Tampilkan/hitung jumlah baris/record tabel pegawai!
Tampilkan/hitung jumlah total gaji di tabel pegawai!
Tampilkan/hitung rata-rata gaji pegawai!
Tampilkan gaji terkecil!
Tampilkan gaji terbesar!
1. Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !
gambar Praktikum 1 ok
2. Tampilkan pegawai yang tunjangannya NULL!
gambar praktikum 2 ok
3. Tampilkan pegawai yang tunjangannya tidak NULL!
gambar praktikum 3 ok
4. Tampilkan/hitung jumlah baris/record tabel pegawai!
gambar 4 praktikum ok

5. Tampilkan/hitung jumlah total gaji di tabel pegawai!
gambar praktikum 5 ok
6. Tampilkan/hitung rata-rata gaji pegawai!
gambar 6 praktikum ok
7. Tampilkan gaji terkecil!
gambar 7 praktikum ok
8. Tampilkan gaji terbesar!
gambar 8 praktikum ok
Kesimpulan
Berdasarkan perintah-perintah SQL yang telah dijalankan, kita dapat mencapai beberapa kesimpulan terkait pegawai data dalam tabel "pegawai":
- Jumlah pegawai: Jumlah baris atau record dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT COUNT(*) FROM pegawai;. kita perlu menjalankan perintah tersebut untuk mendapatkan jumlah pegawai secara akurat.
- Total gaji pegawai: Total gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT SUM(gaji) FROM pegawai;. Perintah ini akan menghasilkan jumlah total gaji dari seluruh pegawai.
- Rata-rata gaji pegawai: Rata-rata gaji dari semua pegawai dalam tabel "pegawai" dapat dihitung menggunakan perintah SELECT AVG(gaji) FROM pegawai;. Perintah ini akan menghasilkan nilai rata-rata gaji dari seluruh pegawai.
- Gaji terkecil: Nilai gaji terkecil dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MIN(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji terendah.
- Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.
Gaji terbesar: Nilai gaji terbesar dari seluruh pegawai dalam tabel "pegawai" dapat ditemukan menggunakan perintah SELECT MAX(gaji) FROM pegawai;. Perintah ini akan mengembalikan nilai gaji tertinggi.
Buat table hewan dan isi datanya seperti berikut:
gambar table hewan
Tugas Praktikum
Tampilkan jumlah hewan yang dimiliki setiap owner.
Tampilkan jumlah hewan berdasarkan spesies
Tampilkan jumlah hewan berdasarkan jenis kelamin
Tampilkan jumlah hewan berdasarkan spesies dan jenis kelamin
Tampilkan jumlah hewan berdasarkan spesis (cat dan dog saja) dan jenis kelamin
Tampilkan jumlah hewan berdasarkan jenis kelamin yang diketahui saja
1. Tampilkan jumlah hewan yang dimiliki setiap owner.
gambar 1 hewan
2. Tampilkan jumlah hewan berdasarkan spesies
gambar 2 hewan
3. Tampilkan jumlah hewan berdasarkan jenis kelamin
gambar 3 hewan
4. Tampilkan jumlah hewan berdasarkan spesies dan jenis kelamin
gambar 4 hewan
5. Tampilkan jumlah hewan berdasarkan spesis (cat dan dog saja) dan jenis kelamin
gambar 5 hewan

6. Tampilkan jumlah hewan berdasarkan jenis kelamin yang diketahui saja
gambar 6 hewan

Kesimpulan
Dalam MySQL, kita dapat menggunakan query untuk menampilkan jumlah hewan berdasarkan kriteria tertentu. Kesimpulannya adalah:
- Jumlah hewan berdasarkan pemilik (owner): Dengan menggunakan klausa group by antara kolom "owners" dan "id", serta fungsi COUNT, kita dapat menghitung jumlah hewan yang dimiliki oleh setiap pemilik.
- Jumlah hewan berdasarkan spesies: Dengan menggunakan klausa GROUP BY pada kolom "species" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap spesies.
- Jumlah hewan berdasarkan jenis kelamin: Dengan menggunakan klausa GROUP BY pada kolom "sex" dan fungsi COUNT, kita dapat menghitung jumlah hewan untuk setiap jenis kelamin.
- Jumlah hewan berdasarkan spesies dan jenis kelamin (khusus cat dan dog): Dengan menggunakan klausa WHERE untuk memfilter spesies yang diinginkan dan klausa GROUP BY pada kolom "species" dan "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk kombinasi spesies dan jenis kelamin tertentu.
- Jumlah hewan berdasarkan jenis kelamin yang diketahui: Dengan menggunakan klausa WHERE untuk memfilter jenis kelamin yang tidak NULL (diketahui) dan klausa GROUP BY pada kolom "sex" serta fungsi COUNT, kita dapat menghitung jumlah hewan untuk jenis kelamin yang diketahui.
Dengan menggunakan query-query ini, kita dapat memperoleh informasi statistik tentang jumlah hewan berdasarkan kriteria yang relevan dalam basis data MySQL.
