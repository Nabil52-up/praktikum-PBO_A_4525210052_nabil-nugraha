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
![Before BangunDatar.java] <img width="796" height="504" alt="image" src="https://github.com/user-attachments/assets/1eb4ca37-bc74-4103-b3d5-32e4050895ed" />


- **After**:
![After BangunDatar.java] <img width="847" height="471" alt="image" src="https://github.com/user-attachments/assets/3a1e0102-dbbb-46fb-a7ad-f58ccf789c48" />


### 1.2. File: `AntiPattern.java` dan `AntiPattermRefaktor.java`

**Penjelasan Kode:**

> Kedua file ini membandingkan pendekatan pemeriksaan tipe objek secara manual dengan pendekatan polimorfisme. Refaktorisasi membuat kode lebih sederhana dan memudahkan penambahan jenis objek baru.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before AntiPattern.java] <img width="676" height="617" alt="image" src="https://github.com/user-attachments/assets/453c9d8a-bc2d-47e9-bdb5-a66dc440be4e" />


- **After**:
![After AntiPatternRefaktor.java] <img width="795" height="625" alt="image" src="https://github.com/user-attachments/assets/564d8cfc-93c0-4181-8506-44dd13b716e6" />


### 1.3. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` menyimpan berbagai objek bangun datar dalam array bertipe `BangunDatar[]`. Program kemudian memanggil metode luas dan keliling setiap objek tanpa harus memeriksa jenis bangunnya secara manual.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java] <img width="869" height="605" alt="image" src="https://github.com/user-attachments/assets/e10d85c2-6850-4ec6-9625-5fa092ba4081" />


- **After**:
![After Main.java] <img width="934" height="652" alt="image" src="https://github.com/user-attachments/assets/4a296818-fafb-4244-8769-978a18443369" />


### Output Java

![Output Java] <img width="571" height="254" alt="image" src="https://github.com/user-attachments/assets/49bad0c8-da6a-43c4-88f8-f239f8617002" />


---

## 2. Implementasi PHP

### 2.1. File: `BangunDatar.php`

**Penjelasan Kode:**

> Kelas `BangunDatar` merupakan kelas abstrak yang mendefinisikan metode luas dan keliling. Kelas turunan mengimplementasikan metode tersebut sesuai dengan karakteristik masing-masing bangun datar.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before BangunDatar.php] <img width="679" height="921" alt="image" src="https://github.com/user-attachments/assets/27d39162-3ee3-4900-ba6d-75e77e6f6a98" />


- **After**:
![After BangunDatar.php] <img width="966" height="924" alt="image" src="https://github.com/user-attachments/assets/926a7f88-e3c9-4703-ad62-08e40d1db832" />
<img width="829" height="886" alt="image" src="https://github.com/user-attachments/assets/0dd5e6a0-0ec1-46a2-bafe-6a3752233492" />
<img width="898" height="907" alt="image" src="https://github.com/user-attachments/assets/290ba2ed-4ceb-4850-9779-f3dc6ad3fad4" />
<img width="886" height="896" alt="image" src="https://github.com/user-attachments/assets/ff408c73-df87-4ac2-a878-8d0b80be35b5" />




### 2.2. File: `notifikasi.php` dan `main.php`

**Penjelasan Kode:**

> File `notifikasi.php` menunjukkan penerapan polimorfisme pada beberapa jenis notifikasi, seperti email, SMS, dan WhatsApp. File `main.php` digunakan untuk menjalankan program dan menampilkan hasilnya.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php] <img width="747" height="420" alt="image" src="https://github.com/user-attachments/assets/d6bdcef1-335d-4543-bc91-0ba4a54109d9" />


- **After**:
![After main.php] <img width="738" height="440" alt="image" src="https://github.com/user-attachments/assets/94864eee-0ec0-45f9-b2d2-9e46e051f385" />

### Output PHP

![Output PHP] <img width="785" height="267" alt="image" src="https://github.com/user-attachments/assets/4c813615-5c45-4897-9de7-22682b165056" />

---

## 3. Kesimpulan

Polimorfisme memungkinkan objek yang berbeda menggunakan metode dengan nama yang sama tetapi memiliki perilaku berbeda. Pendekatan ini membuat kode lebih fleksibel, mudah dikembangkan, dan mengurangi kebutuhan pemeriksaan tipe objek secara manual.
