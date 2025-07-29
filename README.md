# Aplikasi Toko Buku (CLI)
Aplikasi ini merupakan sistem sederhana berbasis CLI (Command Line Interface) yang digunakan untuk mengelola data penjualan dan stok buku di sebuah toko. Data tersimpan dalam format JSON agar mudah diakses dan disimpan secara lokal.
## Fitur Utama

- Menambahkan buku baru ke dalam toko.
- Melihat daftar buku yang tersedia.
- Menjual buku dan mencatat transaksi.
- Mencari buku berdasarkan *judul* atau *penulis*.
- Menampilkan riwayat transaksi.
- Menyimpan data secara permanen ke file .json.
## 🗂 Struktur File
aplikasi_toko_buku_CLI/ 

├── main.py        ← File utama untuk menjalankan aplikasi 

├── data_buku.json ←  File penyimpanan data buku 

├── transaksi.json ← File penyimpanan data transaksi 

├── laporan_panduan_pengguanaan_aplikasi_toko_buku_cli ← panduan program untuk orang awam menggunakan aplikasi ini

├── assets/        ← Folder untuk screenshot

└── README.md      ← Dokumentasi dan petunjuk penggunaan

## Cara Menjalankan Program
1. jalankan file 'toko_buku.jpynb' menggunakan phython
2. gunakan menu yang tersedia dengan memilih angka 1-7
3. data yang sudah dimasukkan bisa disimpan ke file 'data_buku.json' atau jika melakukan transaksi akan dimasukkan ke 'transaksi.json'
## Data Tersimpan

data_buku.json akan menyimpan informasi buku (judul, penulis, harga, stok)

transaksi.json akan menyimpan catatan penjualan (judul, jumlah, total)

## Screenshot/preview CLI
Masukkan screenshot hasil program CLI kamu ke folder assets/, lalu lampirkan di bawah ini:

di atas merupakan contoh hasil dari salah satu transaksi yang terjadi pada buku yang terjual dengan menggunakan aplikasi ini
## catatan tambahan
- file 'main.jpynb' berisi logika program CLI. data yang di input pengguna akan disimpan sementara di memori, lalu dapat disimpan permanen ke dalam file 'data_buku.json'
- program ini berjalan di lingkungan terminal/CLI seperti cmd, terminal linux, atau google colab (dengan input manual)
- file 'data_siswa.json' akan terupdate setiap kali menu simpan digunakan
- setiap transaksi penjualan buku terjadi, akan tersimpan di file 'transaksi.json'

  ## pembuat

nama: fio lola karmila

nim: 24110310027

kelas: 2a

tugas: algoritma dan dasar pemrograman
