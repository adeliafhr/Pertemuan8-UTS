# Aplikasi CRUD Java Swing untuk Entitas Mata Kuliah
---
## 🗂️ Table Of Contents 
- [Koneksi Database dengan JDBC](https://github.com/adeliafhr/Pertemuan8-UTS/blob/main/Mata_Kuliah.java)
- [DB Utils](https://github.com/adeliafhr/Pertemuan8-UTS/blob/main/DBUtils.java)
- [Penerapan CRUD](https://github.com/adeliafhr/Pertemuan8-UTS/blob/main/Mata_Kuliah.java)

---
##  📋 Langkah - Langkah Penggunaan
### 1. Membuat database pada postgreSQL dengan nama `Mata_Kuliah`
![databaseMatkul](https://github.com/user-attachments/assets/c85a768b-c59e-4001-abdf-fdc4c75cf686)

---
### 2. Koneksi project dengan database 
Koneksikan project dengan database yang terdapat pada PostgreeSQL dan tambahkan library JAR PostgreeSQL pada project
![jdbc matkul](https://github.com/user-attachments/assets/adfe7fcf-c541-4237-afaa-7cbd159b1727) ![libraryMatkul](https://github.com/user-attachments/assets/dfdcfa84-6e3c-4072-ba9e-c6cd1716eae8)

---
### 3. Membuat java DB Utils
Buat kelas `DbUtils` (utilitas database) untuk mengkonversi objek ResultSet menjadi TableModel yang akan digunakan untuk menampilkan data dalam JTable

![dbUtilsMatkul](https://github.com/user-attachments/assets/15922226-b93e-4a34-8261-947abdd8de05)

---
### 4. Membuat design GUI
Komponen utama yang di gunakan adalah : 
- JTable yang digunakan untuk menampilkan data mata kuliah
- JButton yang digunakan untuk tombol insert, update, dan delete
- JLabel yang digunakan untuk menampilkan teks yang tetap
- JTextField yang digunakan untuk mengisi data Kode MK, SKS, Nama MK, dan Semester Ajar
![gui matkul](https://github.com/user-attachments/assets/22068bfa-3c92-43c5-9d50-440cd1af4451)

---
### 5. Buat kode untuk mengoneksi java dengan database
![koneksi matkul](https://github.com/user-attachments/assets/91e48e84-e5cd-4811-873a-9a3e6a792057)

---
### 6. Buat method tampil
method tampil digunakan untuk menampilkan semua data mata kuliah pada tabel
![tampilMatku](https://github.com/user-attachments/assets/cdf0eddc-1c53-4931-a651-b5ced92d3d00)

---
### 7. Buat kode untuk menambahkan data mata kuliah (button insert)
Pengguna dapat menambahkan data mata kuliah dan menulisnya pada JTextField lalu data mata kuliah akan tersimpan pada tabel
![insertMatkul](https://github.com/user-attachments/assets/b575be11-86bd-414f-8aa4-453555c25c8b)
 #### -Berikut adalah tampilan saat menambah data mata kuliah-
ketika kita menekan tombol insert, secara otomatis data berhasil di tambahkan dan muncul notifikasi data berhasil ditambah
![tampilanInsertMatkul](https://github.com/user-attachments/assets/fc73909e-db96-4e56-9963-c3c459fb2500)

   ---
### 8. Buat kode untuk mengubah data mata kuliah (button update)
Pengguna dapat mengupdate data mata kuliah dengan memilih data mana yang akan di update dan mengupdate sesuai dengan kemauan lalu data mata kuliah akan diupdate dan akan tersimpan pada tabel
![image](https://github.com/user-attachments/assets/1f8ad381-65bf-4f4b-bdaa-7a6d61681206)
##### -Berikut adalah tampilan saat mengupdate data-
ketika kita menekan tombol update, secara otomatis data yang kita pilih akan di update dan muncul notifikasi data berhasil di update

![tampilanUpdateMatkul](https://github.com/user-attachments/assets/f4bd8669-b560-44c7-b1cc-a8f643c1a2fc)

---
### 9. Buat kode untuk menghapus data mata kuliah (button delete)
Pengguna dapat menghapus data mata kuliah dengan cara memilih data mana yang akan di hapus maka data yang sudah terhapus tidak terdapat pada tabel

![deleteMatkul](https://github.com/user-attachments/assets/6bf0ef64-7011-4f05-8f15-8e46cdb873a3)
#### -Berikut adalah tampilan saat menghapus data-
ketika kita menekan tombol delete, secara otomatis data yang kita pilih akan terhapus dan muncul notifikasi data berhasil di hapus

![tampilanDeleteMatkul](https://github.com/user-attachments/assets/ef38c964-e571-467e-bc30-d917bad5ba6b)

---
### 10. Buat method TabelMouseClicked
method ini digunakan agar data yang kita pilih akan muncul pada JTextField secara otomatis
![mouseClickMatkul](https://github.com/user-attachments/assets/59265909-79df-4a86-98f5-faf06d25b4b8)

---
### 11. Buat method bersih
method bersih digunakan untuk menghapus isi dari textField

![bersihMatkul](https://github.com/user-attachments/assets/db73addf-6079-40f0-b55d-746a0780c3d5)

---
## 💡Selamat Belajar dan Selamat Mencoba dalam menggunakan Java Swing untuk pengembangan aplikasi GUI!📖
