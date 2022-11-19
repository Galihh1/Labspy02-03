# Labspy02

# PROGRAM MENENTUKAN BILANGAN TERBESAR DARI 3 BUAH BILANGAN
- Solusi yang kita inginkan adalah menggunakan hanya percabangan saja.
- Logikanya simpel karena angkanya hanya terbatas untuk 3 angka
# Bagaimana logikanya?
- Misal kita punya 3 variabel a, b, dan c.
- Kapan variabel b dikatakan yang paling besar?
- Jawabannya adalah:
- Variabel b akan dikatakan yang paling besar, ketika ia lebih besar dari nilai a dan juga lebih besar dari nilai c.
# Persiapan Variabel
Baik, kita mulai langsung dengan menyiapkan 3 buah variabel, yaitu a, b, dan c.
**Ketiga variabel ini kita isi dari inputan user seperti berikut:**
- a = int(input('masukan bilangan ke-1: '))
- b = int(input('masukan bilangan ke-2: '))
- c = int(input('masukan bilangan ke-3: '))
# Mencari Angka Terbesar Antara a, b, dan c
Langkah selanjutnya adalah menulis logika untuk mencari angka terbesar, apakah itu a? b? atau c?
Berikut ini kira-kira implementasi logikanya:
![image1.png](screenshot/labspy021.png)

- Lalu kita masukan angka untuk mengisi 3 buah bilangan, setelah itu kita enter maka kita akan tau hasil bilangan yang terbesar seperti dibawah ini
![image2.png](screenshot/labspy02.png)

**FLOWCHART DARI PROGRAM DIATAS**
- Berikut adalah gambaran flowchart dari menentukan bilangan terbesar dari 3 buah bilangan
![image3.png](screenshot/flowchart1.jpg)


# Labspy03

# LATIHAN MENAMPILKAN BILANGAN ACAK YANG LEBIH KECIL DARI 0,5
- Buat kodingan seperti pada gambar dibawah ini
- menggunakan fungsi random() untuk membangkitkan nilai random
![image4.png](screenshot/latihan1.png)
# Penjelasan
- Berikut penjelasan Latihan1.py
- "print"  : berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
- "import" : fungsi lanjut yang dipanggil oleh statement import.
- "random" : untuk menentukan suatu pilihan. 
- "range"  : merupakan fungsi yang menghasilkan list. Fungsi ini akan menciptakan sebuah list baru dengan rentang nilai tertentu. 
- "uniform": digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y.
**Maka Hasilnya seperti dibawah ini**
![image5.png](screenshot/hasillat1.png)
**FLOWCHART DARI PROGRAM DIATAS**
![image6.png](screenshot/flowchart2.png)

# LATIHAN MENAMPILKAN BILANGAN TERBESAR DARI BUAH DATA YANG DIINPUTKAN LALU ANGKA 0 UNTUK BERHENTI
- Buat kodingan seperti pada gambar dibawah ini
- Menggunakan angka nol untuk berhenti yaitu menggunakan fungsi break
![image7.png](screenshot/latihan2.png)
# Penjelasan
- Berikut penjelasan Latihan2.py
- "max" : fungsi bulid-in untuk mencari nilai tertinggi. Fungsi ini dapat diberikan sebuah parameter berupa angka.
- "while" : disebut uncounted loop (perulangan yang tak terhitung), untuk perulangan yang memiliki syarat dan tidak tentu berapa banyak perulangannya.
- "int" : berfungsi mengkonversi bilangan maupun string angka menjadi bilangan bulat (integer).
- "if" = Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu.
- "input" : masukan yang kita berikan ke program.
- "break" : fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai.
- "print" : berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
**Maka hasilnya seperti dibawah ini**
![image8.png](screenshot/hasillat2.png)
**FLOWCHART DARI PROGRAM DIATAS**
![image9.png](screenshot/flowchart3.png)

## Alur Algoritma program1.py

- Buat program sederhana dengan perulangan,
- Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya
- Dengan modal awal 100 juta
- Pada bulan pertama dan kedua belum mendapatkan laba
- Pada bulan ketiga baru mulai mendapatkan laba sebesar 1%
- Pada bulan kelima pendapatan meningkat 5%
- Selanjutnya pada bulan ke-8 mengalami penurunan keuntungan sebesar 2%
- Sehingga laba menjadi 3%
- Hitung total keuntungan selama 8 bulan berjalan usahanya

- Kita mulai cara membuat program diatas 👆

**FLOWCHART**
![image10.png](screenshot/flowchart4.png)
- Lakukan kodingan seperti dibawah ini
![image11.png](screenshot/program1.png)
- Jika sudah kalian bisa save program kalian dengan tekan **CTRL+S** atau mengklik menu file - save as dan beri nama pada program kalian
- lalu menjalankan program kalian dengan menekan **f5** atau mengklik menu **RUN**
- Hasilnya akan seperti gambar dibawah ini
![image12.png](screenshot/hasilprogram1.png)
# Penjelasan
- Berikut Penjelasan Program1.py
- masukkan nilai a
- gunakan for untuk perulangan dari 1 sampai 8.Perulangan for disebut counted loop (perulangan yang terhitung)
- lalu gunakan if pertama untuk menentukan laba bulan ke 1 dan ke 2.masukan variabel (b) kalikan nilai (a) dengan data bulan 1 dan 2. cetak (x) dan (b)
- lalu gunakan if kedua untuk menentukan laba bulan ke 3 dan ke 4.masukan variabel (b) kalikan nilai (a) dengan data bulan 3 dan 4. cetak (x) dan (c)
- lalu gunakan if ketiga untuk menentukan laba bulan ke 5 sampai ke 7.masukan variabel (b) kalikan nilai (a) dengan data bulan 5 sampai 7. cetak (x) dan (d)
- lalu gunakan if keempat untuk menentukan laba bulan ke 8.masukan variabel (b) kalikan nilai (a) dengan data bulan 8. cetak (x) dan (e)
- lalu total keseluruhan.
- cetak total

## STRUKTUR KONDISI DAN PERULANGAN
# PENJELASAN LOOPING

- Repository ini menjelaskan tentang **LOOPING** pada program python
- **LOOPING** sendiri artinya perulangan,dalam bahasa pemrograman merupakan suatu pernyataan untuk 
- menguntruksi komputer agar melakukan sesuatu secara berulang.
- Terdapat 2 jenis perulangan dalam bahasa pemrograman *python* ,yaitu perulangan **for** & **while** .
- Dan seperti inilah contoh dari program looping pada python.
# Latihan Perulangan
## MEMBUAT PROGRAM DENGAN PERULANGAN BERTINGKAT 

- Buatlah kodingan Nested for seperti dibawah ini
![image13.png](screenshot/perulangan1.png)
- Lalu akan keluar hasilnya seperti dibawah ini
![image14.png](screenshot/perulangan2.png)

# Latihan Struktur Kondisi
## PROGRAM MENGURUTKAN DATA BERDASARKAN INPUT SEJUMLAH DATA
- Buatlah kodingan mengurutkan angka seperti dibawah ini
![image15.png](screenshot/urutan1.png)
- Lalu akan keluar hasilnya seperti dibawah ini
![image16.png](screenshot/urutan2.png)