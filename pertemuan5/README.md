# LAPORAN PRAKTIKUM PEMROGRAMAN BERBASIS OBJEK

| Informasi Praktikan | Keterangan |
| :--- | :--- |
| **Nama** | Nabil Nugraha |
| **NPM** | 4525210052 |
| **Kelas** | A |
| **Mata Kuliah** | Pemrograman Berbasis Objek (PBO) |
| **Pertemuan** | 05 - Polimorfisme |
| **Tanggal** | [Kamis 1 Oktober 2026] |

---

## 1. Implementasi Java

### 1.1. File: `BangunDatar.java`, `Lingkaran.java`, `Persegi.java`, `Segitiga.java`, dan `Trapesium.java`

**Penjelasan Kode:**

> Kelas `BangunDatar` menjadi kelas induk bagi berbagai bentuk bangun datar. Setiap kelas turunan memiliki implementasi metode `luas()` dan `keliling()` sesuai dengan rumus masing-masing bangun.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before BangunDatar.java](images/pertemuan5-bangundatar-java-before.png)

- **After**:
![After BangunDatar.java](images/pertemuan5-bangundatar-java-after.png)

### 1.2. File: `AntiPattern.java` dan `AntiPattermRefaktor.java`

**Penjelasan Kode:**

> Kedua file ini membandingkan pendekatan pemeriksaan tipe objek secara manual dengan pendekatan polimorfisme. Refaktorisasi membuat kode lebih sederhana dan memudahkan penambahan jenis objek baru.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before AntiPattern.java](images/pertemuan5-antipattern-before.png)

- **After**:
![After AntiPatternRefaktor.java](images/pertemuan5-antipattern-after.png)

### 1.3. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` menyimpan berbagai objek bangun datar dalam array bertipe `BangunDatar[]`. Program kemudian memanggil metode luas dan keliling setiap objek tanpa harus memeriksa jenis bangunnya secara manual.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java](images/pertemuan5-main-java-before.png)

- **After**:
![After Main.java](images/pertemuan5-main-java-after.png)

### Output Java

![Output Java](images/pertemuan5-output-java.png)

---

## 2. Implementasi PHP

### 2.1. File: `BangunDatar.php`

**Penjelasan Kode:**

> Kelas `BangunDatar` merupakan kelas abstrak yang mendefinisikan metode luas dan keliling. Kelas turunan mengimplementasikan metode tersebut sesuai dengan karakteristik masing-masing bangun datar.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before BangunDatar.php](images/pertemuan5-bangundatar-php-before.png)

- **After**:
![After BangunDatar.php](images/pertemuan5-bangundatar-php-after.png)

### 2.2. File: `notifikasi.php` dan `main.php`

**Penjelasan Kode:**

> File `notifikasi.php` menunjukkan penerapan polimorfisme pada beberapa jenis notifikasi, seperti email, SMS, dan WhatsApp. File `main.php` digunakan untuk menjalankan program dan menampilkan hasilnya.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php](images/pertemuan5-main-php-before.png)

- **After**:
![After main.php](images/pertemuan5-main-php-after.png)

### Output PHP

![Output PHP](images/pertemuan5-output-php.png)

---

## 3. Kesimpulan

Polimorfisme memungkinkan objek yang berbeda menggunakan metode dengan nama yang sama tetapi memiliki perilaku berbeda. Pendekatan ini membuat kode lebih fleksibel, mudah dikembangkan, dan mengurangi kebutuhan pemeriksaan tipe objek secara manual.