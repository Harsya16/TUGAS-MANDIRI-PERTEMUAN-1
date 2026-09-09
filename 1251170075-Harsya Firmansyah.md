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

## 5 Karakteristik Utama ##
1. Input:
   - Memasukkan alamat email dan password
   - Memasukkan kode OTP
3. Output:
4. Definiteness:
   - 
6. Finiteness:
7. Effectiveness:


# BAGIAN B #
## ANALISIS PEMILIHAN STRUKTUR DATA ##
1. **Skenario 1 (Fitur Fitur Undo / Redo):**
   
   Sebuah aplikasi pengolah kata (Text Editor) membutuhkan fitur untuk membatalkan ketikan terakhir pengguna (Undo) dan mengembalikannya lagi (Redo).
   - Struktur Data Terpilih: **Stack**
   - Alasan: Stack bisa dikatakan sebagai LIFO (*Last In, First Out*), artinya ketikan terakhir yang di batalkan (undo) akan menjadi ketikan pertama yang dikembalikan (redo).

2. **Skenario 2 (Peta Navigasi Rute Perjalanan):**
   
   Sebuah aplikasi GPS membutuhkan cara untuk memodelkan lokasi-lokasi kota beserta jalan penghubungnya guna mencari rute tercepat.
   - Struktur Data Terpilih: **Graph**
   - Alasan: 
   
3. **Skenario 3 (Sistem Login Pengguna Berbasis Username):**
   
   Sistem butuh mencari data akun dari jutaan user secara instan berdasarkan Username saat proses login.
   - Struktur Data Terpilih: **Queue/Array**
   - Alasan:
