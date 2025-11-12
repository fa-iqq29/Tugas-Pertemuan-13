# 🧩 Tugas Pertemuan 13 — Penerapan Login dengan Java Persistence API (JPA)

Proyek ini merupakan implementasi sistem **Login dan Manajemen Akun** menggunakan **Java Swing** dan **JPA (EclipseLink)** yang terhubung ke **database PostgreSQL**.  
Aplikasi ini dikembangkan sebagai tugas mata kuliah **Pemrograman Berorientasi Objek (PBO)**, dengan fokus pada penerapan **Java Persistence** dan **Entity Relationship** dalam aplikasi GUI.

---

## 🚀 Fitur Utama

### 🔐 1. Login User
- Validasi `username` dan `password` menggunakan data dari tabel `akun` di database.
- Jika login berhasil, pengguna diarahkan ke halaman utama (`GuiDatabase`) dengan sapaan “Selamat datang, *username*!”.
- Jika gagal, muncul notifikasi kesalahan.

### 🧾 2. Register (Buat Akun)
- Pengguna dapat membuat akun baru melalui form pendaftaran.
- Data tersimpan otomatis ke tabel `akun` dengan validasi agar tidak ada username duplikat.

### 🔁 3. Lupa/Ubah Password
- Pengguna dapat mencari username-nya.
- Jika username ditemukan, field untuk memasukkan password baru akan muncul.
- Password diperbarui langsung di database menggunakan `EntityManager` JPA.

### 💾 4. Integrasi Database
- Menggunakan **PostgreSQL** sebagai sistem manajemen basis data.
- Dikelola melalui `persistence.xml` dengan `EclipseLink (JPA 2.2)`.

---

## ⚙️ Teknologi yang Digunakan
- Java 17+
- NetBeans IDE
- PostgreSQL
- EclipseLink (JPA 2.2)
- Swing GUI

---

## 🧰 Langkah-Langkah
1. Membuat database yang menampung data username dan password
<img width="400" height="420" alt="image" src="https://github.com/user-attachments/assets/c06db5c2-910b-4b0a-bbcd-3c5de005b4d2" />

2. Membuat jFrame Login
<img width="500" height="425" alt="image" src="https://github.com/user-attachments/assets/3a01c103-d689-4392-97eb-a94219258ebe" />

3. Membuat jDialog Buat Akun
<img width="500" height="425" alt="image" src="https://github.com/user-attachments/assets/437f25b5-e62a-45f7-b74e-e2ec0f26efa3" />

4.Membuat jDialog Ubah Password

<img width="500" height="425" alt="image" src="https://github.com/user-attachments/assets/bd48ba9a-169f-4e0d-90d9-dc26c961065f" />

---

### 📸 Tampilan Aplikasi
1. Login
<img width="500" height="459" alt="image" src="https://github.com/user-attachments/assets/2e4abf96-8bfc-402d-b2a9-35f30d2a8367" />

2. Buat Akun
<img width="500" height="459" alt="image" src="https://github.com/user-attachments/assets/3fa69cc5-1d55-42cb-aaae-425658bf52ae" />

3. Lupa Password
   
   a. Cari Username terlebih dahulu
   
   <img width="500" height="459" alt="image" src="https://github.com/user-attachments/assets/1f552e27-db35-4bff-bf30-50378cb583ca" />

   b. Ganti password setelah ditemukan
   
   <img width="500" height="458" alt="image" src="https://github.com/user-attachments/assets/2099e25f-2560-49b7-bd62-209804c784e8" />

---

### ✍️ Penulis
Faiq

Mahasiswa Sistem Informasi

Semester 3

Universitas Islam Negeri Sunan Ampel Surabaya
