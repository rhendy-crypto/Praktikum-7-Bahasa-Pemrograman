# Aplikasi Manajemen Data Mahasiswa

## Deskripsi Proyek
Aplikasi manajemen data mahasiswa adalah program Python sederhana yang memungkinkan pengguna untuk melakukan operasi dasar pada data mahasiswa, seperti menambah, menampilkan, menghapus, dan mengubah data.

## Fitur Utama
- Tambah data mahasiswa baru
- Tampilkan seluruh data mahasiswa
- Hapus data mahasiswa
- Ubah data mahasiswa (nama dan nilai)

## Algoritma Program

### Flowchart

![WhatsApp Image 2024-12-02 at 21 45 10_65bd2146](https://github.com/user-attachments/assets/2f7a4a60-843d-407b-ac1a-919d235e711d)

### Struktur Data
Program menggunakan struktur data list untuk menyimpan data mahasiswa, dimana setiap mahasiswa direpresentasikan sebagai dictionary dengan dua kunci:
- 'nama': Menyimpan nama mahasiswa
- 'nilai': Menyimpan nilai mahasiswa

### Alur Algoritma Utama
1. *Inisialisasi*
   - Membuat list kosong mahasiswa untuk menyimpan data

2. *Fungsi Tambah Data*
   - Menerima input nama dan nilai
   - Membuat dictionary baru dengan data mahasiswa
   - Menambahkan dictionary ke list mahasiswa

3. *Fungsi Tampilkan Data*
   - Memeriksa apakah list mahasiswa kosong
   - Jika tidak kosong, iterasi dan tampilkan setiap data mahasiswa
   - Jika kosong, tampilkan pesan "Tidak ada data mahasiswa"

4. *Fungsi Hapus Data*
   - Menerima nama mahasiswa yang akan dihapus
   - Gunakan list comprehension untuk membuat list baru tanpa mahasiswa tersebut
   - Update list mahasiswa

5. *Fungsi Ubah Data*
   - Menerima nama lama, nama baru, dan nilai baru
   - Cari mahasiswa berdasarkan nama lama
   - Ubah nama dan nilai mahasiswa yang sesuai

6. *Menu Utama*
   - Tampilkan pilihan menu
   - Terima input pengguna
   - Jalankan fungsi sesuai pilihan
   - Lakukan perulangan sampai pengguna memilih keluar

## Struktur Kode

### Variabel Global
python
mahasiswa = []  # List untuk menyimpan data mahasiswa


### Fungsi-Fungsi Utama

#### tambah(nama, nilai)
- Parameter: nama mahasiswa dan nilai
- Menambahkan dictionary mahasiswa ke list
- Contoh: tambah("Budi", 85)

#### tampilkan()
- Menampilkan seluruh data mahasiswa
- Menangani kasus list kosong
- Mencetak nama dan nilai setiap mahasiswa

#### hapus(nama)
- Parameter: nama mahasiswa yang akan dihapus
- Menggunakan list comprehension untuk menyaring data
- Membuat list baru tanpa mahasiswa yang dimaksud

#### ubah(nama_lama, nama_baru, nilai_baru)
- Parameter: nama lama, nama baru, dan nilai baru
- Mencari mahasiswa dengan nama lama
- Memperbarui nama dan nilai mahasiswa

#### menu()
- Fungsi utama untuk menjalankan program
- Loop tak terbatas menampilkan pilihan menu
- Menerima dan memproses input pengguna
- Memanggil fungsi sesuai pilihan

## Contoh Penggunaan

### Menambahkan Data Mahasiswa

![WhatsApp Image 2024-12-03 at 00 37 06_7ab3da22](https://github.com/user-attachments/assets/c1ada771-ca73-49c3-ad52-a20d9cd0d410)

Fitur ini digunakan untuk menambah data Mahasiswa berupa nama dan nilai.

### Menampilkan Data Mahasiswa

![WhatsApp Image 2024-12-02 at 21 43 24_105a7d1d](https://github.com/user-attachments/assets/a0fb6222-c9c0-4b82-8947-3b3973b3c232)

Fitur ini digunakan untuk menampilkan Data mahasiswa yamg telah tersimpan.

### Hapus Data Mahasiswa

![WhatsApp Image 2024-12-02 at 21 43 25_a99dab59](https://github.com/user-attachments/assets/c4b4f7dd-e236-4347-9a83-bb87ce04ab5a)


Fitur ini digunakan untuk menghapus nama mahasiswa yang telah tersimpan dengan cara mengetik nama mahasiswa yang ingin dihapus.

### Ubah Data

![WhatsApp Image 2024-12-02 at 21 43 55_c685797d](https://github.com/user-attachments/assets/9078f397-567c-40f3-a43b-f90f1dcc60ad)

Fitur ini digunakan untuk mengubah nama mahasiswa yang telah tersimpan dengan cara mengetik nama mahasiswa yang ingin diubah.

### keluar

![WhatsApp Image 2024-12-02 at 21 44 26_bd9c50ad](https://github.com/user-attachments/assets/3cd72bc4-a9a4-40c0-8d41-7646eac5a250)

Fitur ini digunakan untuk mengakhiri program.


## Persyaratan
- Python 3.x

## Cara Menjalankan
bash
python manajemen_mahasiswa.py


## Author 

*Nama: Rhendy Zhaky Alvian*

*NIM: 312410377*

*Fakultas: Teknik Informatika UPB*
