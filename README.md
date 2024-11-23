#Program Input Nilai Mahasiswa Program sederhana untuk mengelola data nilai mahasiswa menggunakan Python dengan struktur data Dictionary.

#Deskripsi Program ini adalah aplikasi berbasis teks untuk mengelola data nilai mahasiswa. Pengguna dapat menambah, mengubah, menghapus, melihat, dan mencari data nilai mahasiswa dengan menggunakan NIM (Nomor Induk Mahasiswa) sebagai identifikasi.

#Fitur Lihat Data: Menampilkan daftar semua data nilai mahasiswa. Tambah Data: Menambahkan data nilai mahasiswa baru. Ubah Data: Mengubah data nilai mahasiswa yang sudah ada. Hapus Data: Menghapus data nilai mahasiswa berdasarkan NIM. Cari Data: Mencari dan menampilkan data nilai mahasiswa berdasarkan NIM.

#Struktur Data Data disimpan dalam bentuk dictionary dengan format sebagai berikut: { 'NIM': { 'nama': 'Nama Mahasiswa', 'tugas': nilai_tugas, 'uts': nilai_uts, 'uas': nilai_uas } }

#Cara Menggunakan

Menjalankan Program: Jalankan program dengan interpreter Python.
Menu Utama: Setelah program berjalan, menu utama akan ditampilkan. Pilihan yang tersedia adalah: **(L)**ihat **(T)**ambah **(U)**bah **(H)**apus **(C)**ari **(K)**eluar
Input Pilihan: Masukkan huruf sesuai pilihan yang diinginkan.
Input Data: Jika memilih untuk menambah atau mengubah data, masukkan informasi yang diminta (NIM, Nama, Nilai Tugas, Nilai UTS, Nilai UAS).
Melihat Hasil: Setelah setiap aksi, daftar nilai mahasiswa akan ditampilkan kembali.
#Algoritma Program Inisialisasi Program

Buat instance class DataNilai Tampilkan menu utama Loop Utama Program

Terima input pilihan menu Jalankan metode sesuai pilihan Ulangi sampai pilihan 'K' (Keluar) Pengelolaan Data

Data disimpan dalam dictionary NIM sebagai key Data mahasiswa sebagai value dalam bentuk dictionary Perhitungan Nilai

Nilai Akhir = (Tugas * 30%) + (UTS * 35%) + (UAS * 35%) Hasil ditampilkan dengan 2 desimal

#Kontribusi Silakan berkontribusi dengan cara:

Fork repository Buat branch baru Commit perubahan Push ke branch Buat Pull Request

Lisensi Program ini dirilis di bawah lisensi MIT. Anda bebas menggunakan, mengubah, dan mendistribusikan program ini sesuai kebutuhan.

#author Dira Rohmaeni 312410465
