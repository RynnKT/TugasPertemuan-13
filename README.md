#  Login System — PBO Pertemuan 13

Project ini dibuat untuk memenuhi tugas **Pemrograman Berorientasi Objek (PBO)** Pertemuan ke-13.  
Isinya implementasi fitur login lengkap dengan register dan lupa password, plus koneksi database buat nyimpen username & password.

---

##  Fitur Utama

### 1. **Database User**
Menyimpan:
- Username  
- Password  

Struktur tabel dibuat simple biar fokus ke alur login.

---

### 2. **Login Form**
Frame utama tempat user masuk ke aplikasi.  
Terdapat validasi username & password.  
Jika salah, bakal muncul pesan error.

---

### 3. **Register / Daftar Akun**
Terdiri dari:
- Frame form pendaftaran akun
- Tombol daftar yang terhubung ke database
- Validasi data sebelum disimpan

Output-nya: data user baru masuk ke database.

---

### 4. **Lupa Password / Reset Password**
Flow-nya:
1. User masuk ke frame “Lupa Password”
2. Isi username → klik tombol **Cari**
3. Jika username ditemukan → muncul form ubah password
4. Jika tidak ditemukan → muncul notifikasi error

Fitur ini terdiri dari:
- Frame halaman awal
- Tombol cari + pengecekan username
- Frame ubah password
- Tombol update password di database

---

##  Teknologi yang Dipakai
- **Java Swing** untuk UI
- **Java Persistence / JPA / JDBC** (sesuai implementasi lo)
- **Database SQL** (format basic: username & password)

---

