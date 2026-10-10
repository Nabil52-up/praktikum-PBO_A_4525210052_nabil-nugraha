# LAPORAN PRAKTIKUM PEMROGRAMAN BERBASIS OBJEK

| Informasi Praktikan | Keterangan |
| :--- | :--- |
| **Nama** | Nabil Nugraha |
| **NPM** | 4525210052 |
| **Kelas** | A |
| **Mata Kuliah** | Pemrograman Berbasis Objek (PBO) |
| **Pertemuan** | 06 - Abstract Class, Interface, dan Enum |
| **Tanggal** | [Kamis 8 Oktober 2026] |

---

## 1. Implementasi Java

### 1.1. File: `Kendaraan.java`, `Mobil.java`, dan `Sepeda.java`

**Penjelasan Kode:**

> Kelas `Kendaraan` merupakan abstract class yang menyimpan informasi umum kendaraan. Kelas `Mobil` dan `Sepeda` menjadi turunannya dengan karakteristik dan perilaku yang berbeda.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Kendaraan.java](images/pertemuan6-kendaraan-java-before.png)

- **After**:
![After Kendaraan.java](images/pertemuan6-kendaraan-java-after.png)

### 1.2. File: `Movable.java` dan `Fuelable.java`

**Penjelasan Kode:**

> Kedua interface mendefinisikan kemampuan yang dapat dimiliki oleh objek. `Movable` mengatur perilaku kendaraan yang dapat bergerak, sedangkan `Fuelable` mengatur perilaku kendaraan yang dapat menggunakan bahan bakar.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Interface](images/pertemuan6-interface-before.png)

- **After**:
![After Interface](images/pertemuan6-interface-after.png)

### 1.3. File: `TipeBahanBakar.java` dan `Main.java`

**Penjelasan Kode:**

> Enum `TipeBahanBakar` menyediakan pilihan jenis bahan bakar yang telah ditentukan. File `Main.java` menjalankan program untuk menampilkan perilaku kendaraan dan menghitung biaya pengisian bahan bakar.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java](images/pertemuan6-main-java-before.png)

- **After**:
![After Main.java](images/pertemuan6-main-java-after.png)

### Output Java

![Output Java](images/pertemuan6-output-java.png)

---

## 2. Implementasi PHP

### 2.1. File: `abstraksi.php`

**Penjelasan Kode:**

> File `abstraksi.php` berisi interface, enum, dan kelas kendaraan yang menerapkan konsep abstraksi. Setiap kelas memiliki kemampuan sesuai dengan kontrak yang telah ditentukan.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before abstraksi.php](images/pertemuan6-php-before.png)

- **After**:
![After abstraksi.php](images/pertemuan6-php-after.png)

### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` menjalankan program kendaraan, menampilkan kemampuan gerak, serta melakukan pengisian bahan bakar berdasarkan jenis kendaraan dan kapasitas tangkinya.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php](images/pertemuan6-main-php-before.png)

- **After**:
![After main.php](images/pertemuan6-main-php-after.png)

### Output PHP

![Output PHP](images/pertemuan6-output-php.png)

---

## 3. Kesimpulan

Abstract class digunakan untuk menyediakan struktur umum, interface menentukan kemampuan yang harus dimiliki suatu kelas, dan enum membatasi pilihan nilai agar lebih konsisten. Ketiganya membantu membangun program yang terstruktur dan mudah dikembangkan.