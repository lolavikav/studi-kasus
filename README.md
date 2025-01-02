# studi-kasus

# Validasi From Input

## Nama : Lola Seftyliani 
## Kelas : TI.24.A.4
## NIM : 312410339

# Validasi Input Pendaftaran Online 
Program ini dibuat untuk memvalidasi data input pada proses pendaftaran online. Validasi dilakukan pada tiga jenis data: nama lengkap, nomor telepon, dan email. Program ini memberikan pesan kesalahan yang spesifik jika ada input yang tidak valid dan menyatakan bahwa data pendaftaran valid jika semua input benar.

# Cara Kerja Program
1. Validasi nama

![Screenshot 2025-01-02 201431](https://github.com/user-attachments/assets/cfc40846-fd46-481b-aaa3-0a306e6a90f1)

Penjelasan:

- Fungsi isalpha() memastikan bahwa name hanya terdiri dari huruf.
- Jika nama berisi angka, spasi, atau karakter khusus, validasi akan gagal, dan pesan error ditambahkan ke daftar errors.

2. Validasi nomor telepon

![validasitelepon](https://github.com/user-attachments/assets/aa6a0137-54a9-4478-aceb-a4154880c3c4)

Penjelasan:

- Fungsi isdigit() memastikan bahwa phone hanya terdiri dari angka.
- Jika phone berisi huruf, spasi, atau karakter lain, validasi akan gagal.

3. Validasi Email

![validasiemail](https://github.com/user-attachments/assets/f0a2d499-ac56-4f89-8950-f940ca87f776)

Penjelasan:

- Ekspresi reguler ^\S+@\S+\.\S+$ memastikan bahwa:

   - Ada karakter sebelum @ (\S+ berarti non-spasi).
   - Ada karakter sebelum dan sesudah ..
   - Tidak ada spasi di seluruh string email.

- Jika format email tidak sesuai, validasi akan gagal.

4. Hail Validasi

![outputhasilvalidasi](https://github.com/user-attachments/assets/bfacfb63-28ec-4b90-8bbc-aa5172e16db3)

Penjelasan:

- Jika ada elemen dalam daftar errors, setiap pesan kesalahan akan ditampilkan.
- Jika tidak ada kesalahan, program akan menampilkan "Data pendaftaran valid."

# Persyaratan

- Python 3.x
- Library re (sudah termasuk dalam Python standar)

# Cara Menjalankan Program

1. Clone repositori ini atau salin file program ke komputer Anda.
2. Buka terminal atau command prompt.
3. Jalankan program menggunakan perintah: bash python nama_file.py
4. Masukkan data sesuai dengan permintaan program:

   - Nama lengkap
   - Nomor telepon
   - Email
5. Program akan menampilkan hasil validasi:

   - Pesan "Data pendaftaran valid" jika semua input benar.
   - Pesan kesalahan untuk setiap data yang tidak valid.

# Input dan Output

# Input




