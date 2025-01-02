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
-Ada karakter sebelum @ (\S+ berarti non-spasi).
-Ada karakter sebelum dan sesudah ..
-Tidak ada spasi di seluruh string email.
- Jika format email tidak sesuai, validasi akan gagal.




