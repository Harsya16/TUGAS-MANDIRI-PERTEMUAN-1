**Nama: Harsya Firmansyah**

**Kelas: 3B**

**Mata Kuliah: Algoritma dan Struktur Data**

# BAGIAN A
***CASE KELAS B: Algoritma Pendaftaran & Otentikasi Pengguna Baru di Aplikasi Mobile***

1. Mulai melakukan pendaftaran Aplikasi Mobile
2. Pengguna memasukkan alamat email dan password
3. Sistem akan memvalidasi email dan password
   - Jika format email atau password salah, sistem menampilkan keterangan "format (email/password) tidak valid"
   - Jika format email dan password benar, sistem akan menggulir ke slide berikutnya untuk pengguna mengisi kode OTP
4. Sistem mengirimkan Kode OTP lewat email pengguna
   - Jika kode OTP belum muncul, pengguna meminta sistem mengirimkan kode OTP terbaru
5. Pengguna menerima kode OTP dan memasukkannya ke dalam aplikasi
6. Sistem mengotentikasi kode yang dimasukkan dengan kode yang dikirimkan
   - Jika salah, sistem menampilkan keterangan "kode gagal terverifikasi"
   - Jika benar, status akun berubah menjadi aktif
7. Sistem menampilkan keterangan "Pendaftaran Berhasil"
8. Selesai
