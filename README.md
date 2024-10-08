# 📚 Aplikasi CRUD Java Swing MataKuliah - Pertemuan Kedelapan

**Topik Utama:** Aplikasi CRUD Java Swing untuk mengelola informasi matakuliah 📖

---

## 📑 Daftar Isi
- [🔗 Koneksi Database dengan JDBC](https://github.com/ervina0604/PBO8/blob/main/MataKuliah.java)
- [🛠️ DbUtils: Utilitas Database](https://github.com/ervina0604/PBO8/blob/main/DbUtils.java)
- [🛠️ Implementasi CRUD](https://github.com/ervina0604/PBO8/blob/main/MataKuliah.java)

---

## 🔧 Fitur Utama
Aplikasi ini mengelola informasi matakuliah dengan atribut berikut:
- **KODE MATAKULIAH**: Nomor unik MataKuliah 🔢.
- **SKS**: Sks MataKuliah 📚.
- **NAMA MATAKULIAH**: Nama MataKuliah 🏢.
- **SEMESTER AJAR**: Semester Ajar MataKuliah 📅.

---

## 📋 Langkah-Langkah Penggunaan

### 1. Koneksi Database PostgreSQL
Pastikan telah menambahkan **library PostgreSQL JDBC** ke dalam proyek dan membuat koneksi ke database PostgreSQL yang berisi tabel **matakuliah**. Ikuti langkah berikut:
- Tambahkan file JAR PostgreSQL JDBC ke dalam proyek Java Anda.
  ![image](https://github.com/user-attachments/assets/b3daecc2-afe5-4094-9d0e-7111a653349b)

  
- Buat koneksi ke database menggunakan URL koneksi, username, dan password PostgreSQL 🔗.
  ![image](https://github.com/user-attachments/assets/25851b06-9ed7-42a3-8516-826be3623fbb)


---


### 2. Membuat Java DB Utils
Buat kelas `DbUtils` untuk mengkonversi objek **ResultSet** menjadi **TableModel** yang akan digunakan untuk menampilkan data dalam **JTable** 📊.

![image](https://github.com/user-attachments/assets/bb2e5ad9-e93b-4faa-9f58-f3b8a6556605)


---

### 3. Membuat Desain GUI
Gunakan **Java Swing** untuk mendesain antarmuka pengguna. Komponen utama yang digunakan:
- **JTable**: Menampilkan data matakuliah yang disimpan 📑.
- **JTextField**: Input untuk KodeMataKuliah, Sks , Nama MataKuliah, SemesterAjar 🖊️.
- **JButton**: Tombol untuk operasi CRUD (Tambah, Update, Hapus, Clear) 🔘.
![image](https://github.com/user-attachments/assets/e79478da-d7e2-4539-aa76-d51ff7d72a21)


---

### 4. Method Tampil dan TableMouseClicked
- **Method Tampil**: Menampilkan seluruh data matakuliah yang tersimpan dalam database ke **JTable** 📋.
  ![image](https://github.com/user-attachments/assets/69a13017-ba1e-4c70-b81e-6316f39f71a0)

- **TableMouseClicked**: Ketika pengguna memilih baris di **JTable**, data matakuliah akan muncul di form input untuk diperbarui ✏️.
  ![image](https://github.com/user-attachments/assets/6a67d73b-e711-44a3-a939-ed6bd7a143a9)


---

### 5. Tambah Data (Button Add)
Pengguna dapat menambah matakuliah baru ke dalam database. Data yang diinput melalui **JTextField** akan divalidasi dan kemudian disimpan.
![image](https://github.com/user-attachments/assets/8da08e14-af09-404f-91ae-b47f152260c9)

**Tampilan saat menambah data:**
Setelah menekan tombol **Tambah**, data akan tersimpan dan ditampilkan di **JTable** ✅.
![image](https://github.com/user-attachments/assets/d830f3cd-697f-4598-af44-21de9a8bc2f8)


---

### 6. Perbarui Data (Button Update)
Pengguna dapat memperbarui informasi matakuliah yang sudah ada. Dengan memilih data dari **JTable**, data akan muncul di form input, dan pengguna dapat mengeditnya.
![image](https://github.com/user-attachments/assets/6310aef0-b715-44a2-a22f-9058ef574e38)

**Tampilan saat memperbarui data:**
Setelah menekan tombol **Update**, perubahan data akan disimpan dan diperbarui di **JTable** 🔄.
![image](https://github.com/user-attachments/assets/7afc3f8a-a0bc-4614-b515-8b9a89566c5d)


---

### 7. Hapus Data (Button Delete)
Pengguna dapat memilih matakuliah dari **JTable**, dan kemudian menekan tombol **Hapus** untuk menghapus matakuliah tersebut.
![image](https://github.com/user-attachments/assets/db29358a-2a2a-4a9f-8bce-2b0c218ed6f0)

**Tampilan saat menghapus data:**
Setelah menghapus data, matakuliah akan dihapus dari database dan **JTable** akan diperbarui ❌.
![image](https://github.com/user-attachments/assets/480917c9-fb66-4720-bc5e-b353c1c0f7b9)


---

### 8. Mengosongkan Input (Button Clear)
Tombol **Clear** digunakan untuk membersihkan semua field input agar siap untuk memasukkan data baru ✨.
![image](https://github.com/user-attachments/assets/445f9c74-387e-4cd3-81c8-3ab4097aebd7)


---

### 🚀 Selamat Belajar dan Selamat Menerapkan Java Swing serta JDBC dalam Pengembangan Aplikasi! 💻

--- 
