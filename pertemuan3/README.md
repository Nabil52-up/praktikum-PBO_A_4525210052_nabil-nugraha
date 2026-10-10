# LAPORAN PRAKTIKUM PEMROGRAMAN BERBASIS OBJEK

| Informasi Praktikan | Keterangan |
| :--- | :--- |
| **Nama** | Nabil Nugraha |
| **NPM** | 4525210052 |
| **Kelas** | A |
| **Mata Kuliah** | Pemrograman Berbasis Objek (PBO) |
| **Pertemuan** | 03 - Constructor, Konstanta, dan Anggota Statis |
| **Tanggal** | [Kamis 17 September 2026] |

---

## 1. Implementasi Java

### 1.1. File: `RekeningBank.java`

**Penjelasan Kode:**

> Kelas `RekeningBank` digunakan untuk mengelola data rekening, seperti nomor rekening, nama pemilik, dan saldo. Constructor digunakan untuk membuat objek rekening, sedangkan konstanta menyimpan nilai tetap seperti bunga tahunan, biaya administrasi, dan batas penarikan.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before RekeningBank.java](images/pertemuan3-java-before.png)

- **After**:
![After RekeningBank.java](images/pertemuan3-java-after.png)

### 1.2. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` membuat beberapa objek rekening dan menguji operasi setoran, penarikan, serta penghitungan jumlah rekening menggunakan anggota statis.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java](images/pertemuan3-main-java-before.png)

- **After**:
![After Main.java](images/pertemuan3-main-java-after.png)

### Output Java

![Output Java](images/pertemuan3-output-java.png)

---

## 2. Implementasi PHP

### 2.1. File: `RekeningBank.php`

**Penjelasan Kode:**

> Kelas `RekeningBank` menerapkan constructor dengan parameter bawaan dan named constructor untuk menyediakan cara alternatif dalam membuat rekening. Kelas ini juga menggunakan konstanta dan anggota statis untuk mengatur data rekening.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before RekeningBank.php](images/pertemuan3-php-before.png)

- **After**:
![After RekeningBank.php](images/pertemuan3-php-after.png)

### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` membuat objek rekening, menampilkan jumlah rekening, dan menjalankan operasi setoran serta penarikan untuk menunjukkan cara kerja kelas `RekeningBank`.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php](images/pertemuan3-main-php-before.png)

- **After**:
![After main.php](images/pertemuan3-main-php-after.png)

### Output PHP

![Output PHP](images/pertemuan3-output-php.png)

---

## 3. Kesimpulan

Constructor mempermudah proses pembuatan objek, sedangkan konstanta digunakan untuk menyimpan nilai tetap. Anggota statis memungkinkan data tertentu, seperti jumlah rekening, dikelola bersama oleh seluruh objek dalam kelas yang sama.