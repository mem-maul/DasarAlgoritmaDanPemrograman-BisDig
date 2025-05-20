1. Penjelasan dari soal, Seorang kasir toko ingin sistem sederhana untuk menghitung total harga pembelian 3 barang dan menampilkan totalnya.
- Gunakan fungsi `input()` untuk membaca input dan konversi ke tipe data `float` agar dapat melakukan perhitungan desimal.
- Jumlahkan ketiga harga barang yang telah dimasukkan untuk mendapatkan total harga.
- Kemudian membuat tampilan total harga dengan menggunakan fungsi `print()`, dengan format yang jelas agar pengguna dapat memahami hasilnya.

2. Penjelasan dari soal, Dalam sistem e-commerce, pelanggan mendapatkan diskon 10% jika belanja di atas Rp500.000.
   - kita dapat menggunakan struktur kontrol percabangan (seperti `if` statement) untuk menentukan apakah pelanggan berhak mendapatkan diskon atau tidak
   - Input: Ambil total belanja dari pelanggan.
   - Percabangan: - Jika total belanja lebih dari Rp500.000, maka pelanggan berhak mendapatkan diskon 10%.
                  - Jika tidak, pelanggan tidak mendapatkan diskon
   - Output: Hitung total bayar setelah diskon (jika ada) dan tampilkan hasilnya.

3. Penjelasan dari soal, seorang siswa ingin mengetahui apakah nilai ujiannya memenuhi syarat lulus.
   - `float`: Tipe data ini digunakan untuk menyimpan angka dengan koma desimal. Dalam program ini, tipe float digunakan untuk menyimpan 
              nilai mata pelajaran karena nilai ujian bisa berupa angka desimal (misal 85.5).
   - `int` (bisa saja digunakan): Jika nilai hanya bilangan bulat, tipe `int` juga bisa digunakan.
   - `str`: Tipe data string yang menjadi output dari fungsi input(). Karena input bertipe string, perlu dikonversi ke float agar dapat 
            dilakukan operasi matematika.
     
  - `+ `(penjumlahan): Untuk menjumlahkan ketiga nilai mata pelajaran.

  -  `/` (pembagian): Untuk menghitung rata-rata nilai dengan membagi jumlah total nilai dengan 3.

  - `>=` (operator perbandingan): Untuk membandingkan nilai rata-rata dengan batas kelulusan dan menentukan apakah siswa lulus atau tidak.

  - `=` (assignment): Untuk menyimpan nilai hasil perhitungan atau input ke dalam variabel.

4. Penjelasan dari soal, Anda diminta membuat fungsi untuk menghitung faktorial dari suatu bilangan menggunakan metode rekursif.
   - Modularitas: Fungsi memungkinkan kita untuk membagi program menjadi bagian-bagian yang lebih kecil dan lebih mudah dikelola. Dengan menggunakan fungsi, kita dapat mengisolasi logika perhitungan faktorial, sehingga lebih mudah untuk memahami dan memelihara kode.
   - Reusabilitas: Fungsi yang telah dibuat dapat digunakan kembali di bagian lain dari program atau di program lain tanpa perlu menulis ulang kode. Ini menghemat waktu dan usaha.
   - Abstraksi: Dengan menggunakan fungsi, kita dapat menyembunyikan detail implementasi dari pengguna fungsi. Pengguna hanya perlu tahu cara memanggil fungsi dan apa yang diharapkan sebagai hasilnya.
Cara Kerja Rekursi dalam Menghitung Faktorial
  - Rekursi adalah teknik di mana sebuah fungsi memanggil dirinya sendiri untuk

5. Penjelasan dari soal, Seorang guru ingin membuat sistem input nilai 5 siswa dan mencari nilai tertinggi.
   1.	Perulangan (Looping):
•	Dalam program di atas, kita menggunakan perulangan for untuk mengulangi proses input nilai sebanyak 5 kali.
•	range(5) menghasilkan urutan angka dari 0 hingga 4, yang digunakan untuk mengindeks siswa ke-1 hingga ke-5.
•	Setiap iterasi, program meminta pengguna untuk memasukkan nilai siswa dan menyimpannya dalam array nilai_siswa.
   2.	Array:
•	Array (atau dalam Python, kita menggunakan list) digunakan untuk menyimpan nilai-nilai yang dimasukkan oleh pengguna.
•	Dengan menggunakan array, kita dapat menyimpan beberapa nilai dalam satu variabel, yang memudahkan kita untuk mengelola dan memproses data tersebut.
•	Setelah semua nilai dimasukkan, kita menggunakan fungsi max() untuk mencari nilai tertinggi dari array nilai_siswa.

