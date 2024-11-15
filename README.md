# Labpy04
# Putri Melati Ramadhaniati (312410194)
# TI.24.A.2

# Latihan

• Buat sebuah list sebanyak 5 elemen dengan nilai bebas

• akses list:

      • tampilkan elemen ke 3

      • ambil nilai elemen ke 2 sampai elemen ke 4

      • ambil elemen terakhir

• ubah elemen list:

      • ubah elemen ke 4 dengan nilai lainnya

      • ubah elemen ke 4 sampai dengan elemen terakhir

• tambah elemen list:

      • ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)

      • tambah list B dengan nilai string

      • tambah list B dengan 3 nilai

      • gabungkan list B dengan list A

Kode Program dan Hasil Output:




# Tugas Praktikum

Buat program sederhana untuk menambahkan data kedalam sebuah
list dengan rincian sebagai berikut:

• Progam meminta memasukkan data sebanyak-banyaknya (gunakan
perulangan)

• Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban
t (Tidak), maka program akan menampilkan daftar datanya. • Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
uts: 35%, uas: 35%)

• Buat flowchart dan penjelasan programnya pada README.md. • Commit dan push repository ke github.

# Kode Program

![BASPEM 09 (kode 1)](https://github.com/user-attachments/assets/a8932eb2-74aa-45b1-b116-839452d551ab)
![BASPEM 09 (kode 2)](https://github.com/user-attachments/assets/70de1c86-80cf-49f3-be09-61c5d4ad4b8f)

# Hasil Run (Output)

![BASPEM 09 (RUN)](https://github.com/user-attachments/assets/29dec78b-6a8f-411f-903c-bd9a2cb5f488)

# Penjelasan Program

1. Inisialisasi List mahasiswa:

   membuat sebuah list kosong bernama mahasiswa yang akan digunakan untuk menyimpan data mahasiswa yang diinput.

2. Definisi Fungsi hitung_nilai_akhir:

   Fungsi ini menerima tiga parameter: tugas, uts, dan uas. Fungsi ini menghitung nilai akhir berdasarkan bobot yang ditentukan:

   ~Nilai tugas memiliki bobot 30% (0.3)
   
   ~Nilai UTS memiliki bobot 35% (0.35)
   
   ~Nilai UAS juga memiliki bobot 35% (0.35) Fungsi ini mengembalikan hasil perhitungan            nilai akhir.

3. Loop untuk Input Data Mahasiswa:

   Di dalam loop while True, program meminta pengguna untuk memasukkan data mahasiswa, termasuk nama, NIM, dan nilai tugas, UTS, dan UAS. Nilai tugas, UTS, dan UAS diubah menjadi tipe float untuk memungkinkan perhitungan desimal.

4. Menghitung Nilai Akhir:

   Program memanggil fungsi hitung_nilai_akhir untuk menghitung nilai akhir berdasarkan nilai yang diinput.

5. Menyimpan Data ke dalam List:

   Data mahasiswa disimpan dalam bentuk dictionary, yang berisi nama, NIM, nilai tugas, UTS, UAS, dan nilai akhir. Dictionary ini kemudian ditambahkan ke dalam list mahasiswa.

6. Menanyakan Apakah Ingin Menambah Data:

   Setelah data mahasiswa disimpan, program menanyakan kepada pengguna apakah mereka ingin menambah data mahasiswa lagi. Jika pengguna memasukkan 't' (tidak), loop akan berhenti.

7. Menampilkan Semua Data Mahasiswa:

   Setelah loop selesai, program mencetak header untuk tabel yang menampilkan data mahasiswa. Format string digunakan untuk memastikan kolom-kolom data teratur.

8. Iterasi dan Menampilkan Data Mahasiswa:

   Program kemudian melakukan iterasi melalui list mahasiswa dan mencetak setiap data mahasiswa dalam format yang telah ditentukan. Nilai akhir ditampilkan dengan dua angka desimal.

# Flowchart

![Baspem flowchart per 9](https://github.com/user-attachments/assets/3c2c74b3-b126-4d47-ae36-6e79cacf5fa7)

# Penjelasan Flowchart

1.	Mulai: Menandai awal program.
   
2.	Inisialisasi list data_nilai: Menyiapkan sebuah daftar kosong untuk menyimpan data nilai mahasiswa.
   
3.	Masukkan Nilai Mahasiswa: Meminta pengguna untuk memasukkan nilai mahasiswa, seperti nama dan NIM.
   
4.	Masukkan Nilai Tugas: Meminta pengguna untuk memasukkan nilai tugas.
   
5.	Masukkan Nilai UTS: Meminta pengguna untuk memasukkan nilai UTS.
    
6.	Hitung Nilai Akhir: Menghitung nilai akhir mahasiswa berdasarkan nilai tugas dan nilai UTS.
    
7.	Simpan Data ke dalam List: Menyimpan data mahasiswa yang sudah lengkap (nama, NIM, nilai tugas, nilai UTS, nilai akhir) ke dalam daftar yang sudah disiapkan.
    
8.	Apakah Anda ingin menambahkan data? (y/t): Menanyakan kepada pengguna apakah ingin menambahkan data mahasiswa lagi.
    
9.	Ya: Jika pengguna menjawab "Ya", program akan kembali ke langkah "Masukkan Nilai Mahasiswa" untuk memasukkan data baru.
    
10.	Tidak: Jika pengguna menjawab "Tidak", program akan lanjut ke langkah "Tampilkan Daftar Nilai".
    
11.	Tampilkan Daftar Nilai: Menampilkan semua data mahasiswa yang sudah tersimpan di dalam daftar.
    
12.	Selesai: Menandai akhir program.




   

   
   
