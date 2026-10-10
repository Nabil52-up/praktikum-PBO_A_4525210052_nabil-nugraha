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
![Before kelas Pegawai](images/pertemuan4-java-before.png)

- **After**:
![After kelas Pegawai](images/pertemuan4-java-after.png)

### 1.2. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` membuat daftar objek pegawai, menampilkan informasi masing-masing pegawai, dan menghitung total beban gaji menggunakan perulangan.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java](images/pertemuan4-main-java-before.png)

- **After**:
![After Main.java](images/pertemuan4-main-java-after.png)

### Output Java

![Output Java](images/pertemuan4-output-java.png)

---

## 2. Implementasi PHP

### 2.1. File: `Pegawai.php`

**Penjelasan Kode:**

> File `Pegawai.php` berisi kelas induk `Pegawai` beserta kelas turunannya. Inheritance memungkinkan kelas turunan menggunakan atribut dan metode dari kelas induk tanpa harus menuliskan ulang seluruh kode yang sama.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Pegawai.php](images/pertemuan4-php-before.png)

- **After**:
![After Pegawai.php](images/pertemuan4-php-after.png)

### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` membuat daftar pegawai dengan jenis yang berbeda, menampilkan informasi pegawai, dan menghitung total gaji menggunakan objek dari kelas induk.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php](images/pertemuan4-main-php-before.png)

- **After**:
![After main.php](images/pertemuan4-main-php-after.png)

### Output PHP

![Output PHP](images/pertemuan4-output-php.png)

---

## 3. Kesimpulan

Inheritance memungkinkan kelas turunan menggunakan kembali atribut dan metode dari kelas induk. Dengan penerapan pewarisan, kode menjadi lebih terstruktur dan pengelolaan berbagai jenis pegawai dapat dilakukan dengan lebih mudah.