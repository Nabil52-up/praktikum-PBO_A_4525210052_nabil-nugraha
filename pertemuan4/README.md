# LAPORAN PRAKTIKUM PEMROGRAMAN BERBASIS OBJEK

| Informasi Praktikan | Keterangan |
| :--- | :--- |
| **Nama** | Nabil Nugraha |
| **NPM** | 4525210052 |
| **Kelas** | A |
| **Mata Kuliah** | Pemrograman Berbasis Objek (PBO) |
| **Pertemuan** | 04 - Inheritance |
| **Tanggal** | [Kamis 24 September 2026] |

---

## 1. Implementasi Java

### 1.1. File: `Pegawai.java`, `PegawaiTetap.java`, dan `PegawaiKontrak.java`

**Penjelasan Kode:**

> Kelas `Pegawai` berfungsi sebagai kelas induk yang menyimpan data umum pegawai. Kelas `PegawaiTetap` dan `PegawaiKontrak` merupakan kelas turunan yang mewarisi atribut serta perilaku dari kelas induk dan memiliki karakteristik masing-masing.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before kelas Pegawai] <img width="827" height="725" alt="image" src="https://github.com/user-attachments/assets/fb5f622f-6bd6-4e33-aa0b-2ff7832bc88a" />


- **After**:
![After kelas Pegawai] <img width="894" height="829" alt="image" src="https://github.com/user-attachments/assets/661366b9-d461-4376-b5ea-0e26e7a74b73" />

### 1.2. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` membuat daftar objek pegawai, menampilkan informasi masing-masing pegawai, dan menghitung total beban gaji menggunakan perulangan.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java] <img width="978" height="516" alt="image" src="https://github.com/user-attachments/assets/50f1df04-00b9-48b3-a88e-eba4e328c0cf" />

- **After**:
![After Main.java] <img width="866" height="515" alt="image" src="https://github.com/user-attachments/assets/1b676dc7-b6da-41e7-9b83-51d325c6022b" />


### Output Java

![Output Java] <img width="991" height="177" alt="image" src="https://github.com/user-attachments/assets/a1ae86e2-86cb-4543-9e0d-f1ac88a16709" />


---

## 2. Implementasi PHP

### 2.1. File: `Pegawai.php`

**Penjelasan Kode:**

> File `Pegawai.php` berisi kelas induk `Pegawai` beserta kelas turunannya. Inheritance memungkinkan kelas turunan menggunakan atribut dan metode dari kelas induk tanpa harus menuliskan ulang seluruh kode yang sama.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Pegawai.php] <img width="849" height="929" alt="image" src="https://github.com/user-attachments/assets/2edfcbcf-d475-43a4-9414-eea1740531c0" />
<img width="747" height="792" alt="image" src="https://github.com/user-attachments/assets/a89024a8-5943-4ea4-aecd-18c93551dcbe" />



- **After**:
![After Pegawai.php] <img width="767" height="907" alt="image" src="https://github.com/user-attachments/assets/f1fcb5a1-dddc-41a5-9b21-f5cfbe9b533f" />
<img width="493" height="810" alt="image" src="https://github.com/user-attachments/assets/b423d0b7-167d-406b-965d-ca7a581a4e96" />



### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` membuat daftar pegawai dengan jenis yang berbeda, menampilkan informasi pegawai, dan menghitung total gaji menggunakan objek dari kelas induk.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php] <img width="720" height="423" alt="image" src="https://github.com/user-attachments/assets/00b3a061-cc03-451f-ae6b-58fec918474c" />


- **After**:
![After main.php] <img width="804" height="439" alt="image" src="https://github.com/user-attachments/assets/96d292ba-92c6-4fef-9a5c-d777ba096c24" />


### Output PHP

![Output PHP] <img width="845" height="209" alt="image" src="https://github.com/user-attachments/assets/6587d05e-9c87-47d7-882d-2c2ce09ae227" />

---

## 3. Kesimpulan

Inheritance memungkinkan kelas turunan menggunakan kembali atribut dan metode dari kelas induk. Dengan penerapan pewarisan, kode menjadi lebih terstruktur dan pengelolaan berbagai jenis pegawai dapat dilakukan dengan lebih mudah.
