# LAPORAN PRAKTIKUM PEMROGRAMAN BERBASIS OBJEK

| Informasi Praktikan | Keterangan |
| :--- | :--- |
| **Nama** | Nabil Nugraha |
| **NPM** | 4525210052 |
| **Kelas** | A |
| **Mata Kuliah** | Pemrograman Berbasis Objek (PBO) |
| **Pertemuan** | 02 - Enkapsulasi |
| **Tanggal** | [Kamis 10 September 2026] |

---

## 1. Implementasi Java

### 1.1. File: `Mahasiswa.java`

**Penjelasan Kode:**

> Kelas `Mahasiswa` digunakan untuk menyimpan data mahasiswa dan nilai tugas, UTS, serta UAS. Enkapsulasi diterapkan untuk menjaga data agar tidak diubah sembarangan. Program juga menghitung nilai akhir berdasarkan bobot setiap komponen dan melakukan validasi nilai.

**Bukti Eksekusi (Screenshot):**

- **Before** (Kondisi awal):
![Before Mahasiswa.java](images/pertemuan2-java-before.png)

- **After** (Kondisi akhir):
![After Mahasiswa.java](images/pertemuan2-java-after.png)

### 1.2. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` digunakan untuk membuat beberapa objek mahasiswa, menampilkan rekap nilai, dan menguji validasi data yang telah diterapkan pada kelas `Mahasiswa`.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java](images/pertemuan2-main-java-before.png)

- **After**:
![After Main.java](images/pertemuan2-main-java-after.png)

### Output Java

![Output Java](images/pertemuan2-output-java.png)

---

## 2. Implementasi PHP

### 2.1. File: `Mahasiswa.php`

**Penjelasan Kode:**

> Kelas `Mahasiswa` menerapkan enkapsulasi menggunakan properti privat, konstanta bobot nilai, dan validasi data. Perhitungan nilai akhir dilakukan berdasarkan bobot tugas, UTS, dan UAS.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Mahasiswa.php](images/pertemuan2-php-before.png)

- **After**:
![After Mahasiswa.php](images/pertemuan2-php-after.png)

### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` membuat objek mahasiswa, menampilkan rekap nilai, serta menguji penolakan data yang tidak sesuai dengan aturan yang telah ditentukan.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php](images/pertemuan2-main-php-before.png)

- **After**:
![After main.php](images/pertemuan2-main-php-after.png)

### Output PHP

![Output PHP](images/pertemuan2-output-php.png)

---

## 3. Kesimpulan

Enkapsulasi membantu menjaga keamanan dan konsistensi data pada objek. Dengan validasi yang tepat, data yang tidak sesuai aturan dapat ditolak sehingga program menjadi lebih terstruktur dan dapat diandalkan.