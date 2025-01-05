rogram ini adalah sistem manajemen perpustakaan sederhana dengan antarmuka berbasis teks. Berikut adalah penjelasan komponen utama dalam program ini:

1. Class DataBuku (Penyimpanan Data Buku)
Class ini bertanggung jawab untuk menyimpan data buku dalam sebuah list yang disebut daftar_buku.
Metode:
tambah_buku(judul, penulis, tahun): Menambahkan buku baru ke dalam daftar dengan judul (judul), penulis (penulis), dan tahun terbit (tahun).
tampilkan_buku(): Menampilkan semua buku dalam daftar. Jika tidak ada buku, akan menampilkan pesan "Tidak ada buku yang terdaftar."
2. Class ProsesBuku (Proses Buku)
Class ini menangani proses-proses terkait dengan buku. Class ini berinteraksi dengan class DataBuku untuk menambah dan menampilkan buku.
Metode:
tambah_data(judul, penulis, tahun): Menambahkan buku ke dalam penyimpanan data dengan memanggil tambah_buku dari class DataBuku.
tampilkan_data(): Mengambil dan menampilkan daftar buku dengan memanggil tampilkan_buku dari class DataBuku.
3. Class TampilanBuku (Antarmuka Pengguna)
Class ini menangani interaksi pengguna. Class ini menyediakan menu berbasis teks dan memproses input dari pengguna.
Metode:
tampilkan_menu(): Menampilkan menu utama dengan pilihan untuk menambah buku, melihat daftar buku, atau keluar dari program.
tambah_buku(): Meminta pengguna untuk memasukkan detail buku dan kemudian menambahkannya menggunakan class ProsesBuku.
tampilkan_buku(): Menampilkan daftar buku saat ini melalui class ProsesBuku.
jalankan(): Merupakan loop utama dari program. Program ini akan terus menampilkan menu dan menangani pilihan pengguna hingga pengguna memilih untuk keluar.
Program Utama:
Membuat objek dari class DataBuku, ProsesBuku, dan TampilanBuku, kemudian menjalankan metode jalankan() untuk memulai program.
Program ini akan terus berjalan hingga pengguna memilih "3" untuk keluar.
Cara Kerja Program:
Pengguna akan diberikan pilihan menu dengan tiga opsi:

Pilihan 1: Menambah buku baru dengan memasukkan judul, penulis, dan tahun terbit buku.
Pilihan 2: Menampilkan daftar buku yang telah ditambahkan.
Pilihan 3: Keluar dari program.
Sistem ini menyimpan detail buku dalam memori dan memungkinkan pengguna untuk melihat atau menambah buku. Data tidak disimpan secara permanen antara sesi program.

Contoh Penggunaan:
Menambah Buku: Pilih opsi 1, masukkan detail buku, dan buku akan ditambahkan ke daftar.
Melihat Daftar Buku: Pilih opsi 2, dan program akan menampilkan daftar buku yang telah ditambahkan.
Keluar Program: Pilih opsi 3 untuk keluar.
Program ini adalah contoh dasar dari penerapan prinsip objektif dalam Python, yang menunjukkan bagaimana class dan metode dapat digunakan untuk mengelola dan memanipulasi data, dengan antarmuka berbasis teks yang sederhana untuk berinteraksi dengan pengguna.
