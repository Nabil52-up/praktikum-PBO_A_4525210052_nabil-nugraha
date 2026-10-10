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
![Before RekeningBank.java] <img width="1023" height="930" alt="image" src="https://github.com/user-attachments/assets/57c10b08-5ddf-4c2e-b91e-d0a679a5550e" />

- **After**:
![After RekeningBank.java] <img width="967" height="911" alt="image" src="https://github.com/user-attachments/assets/00956ac1-2926-4976-a1db-e740cefd7097" />


### 1.2. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` membuat beberapa objek rekening dan menguji operasi setoran, penarikan, serta penghitungan jumlah rekening menggunakan anggota statis.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java] <img width="895" height="628" alt="image" src="https://github.com/user-attachments/assets/b787e21a-c7b9-4e95-aab7-85e8300b1808" />

- **After**:
![After Main.java] <img width="926" height="620" alt="image" src="https://github.com/user-attachments/assets/022216b7-ced9-4537-9e26-751d52312621" />

### Output Java

![Output Java] <img width="1010" height="219" alt="image" src="https://github.com/user-attachments/assets/60136a22-01e1-41a6-aa91-2b879b712b20" />

---

## 2. Implementasi PHP

### 2.1. File: `RekeningBank.php`

**Penjelasan Kode:**

> Kelas `RekeningBank` menerapkan constructor dengan parameter bawaan dan named constructor untuk menyediakan cara alternatif dalam membuat rekening. Kelas ini juga menggunakan konstanta dan anggota statis untuk mengatur data rekening.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before RekeningBank.php] <img width="958" height="898" alt="image" src="https://github.com/user-attachments/assets/a956f09a-d5e3-4098-9858-04f7cef6f976" />
<img width="674" height="556" alt="image" src="https://github.com/user-attachments/assets/f537fa20-0eb5-4753-97cd-4f2db531b9cc" />



- **After**:
![After RekeningBank.php] <img width="930" height="905" alt="image" src="https://github.com/user-attachments/assets/d6ff0906-4a5d-4245-baf0-90d7e1ad0cc9" />
<img width="856" height="875" alt="image" src="https://github.com/user-attachments/assets/6d9a3caf-2d39-45fb-8ce4-c0de4a1a46c4" />



### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` membuat objek rekening, menampilkan jumlah rekening, dan menjalankan operasi setoran serta penarikan untuk menunjukkan cara kerja kelas `RekeningBank`.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php] <img width="786" height="568" alt="image" src="https://github.com/user-attachments/assets/57ae6db7-1237-4ea9-913d-df888eeace71" />

- **After**:
![After main.php] <img width="897" height="560" alt="image" src="https://github.com/user-attachments/assets/687066ea-974f-4a20-b2e7-b1e0dcb3d516" />


### Output PHP

![Output PHP] <img width="854" height="221" alt="image" src="https://github.com/user-attachments/assets/38870957-5b30-4c44-8c25-f707ceeaa0e5" />

---

## 3. Kesimpulan

Constructor mempermudah proses pembuatan objek, sedangkan konstanta digunakan untuk menyimpan nilai tetap. Anggota statis memungkinkan data tertentu, seperti jumlah rekening, dikelola bersama oleh seluruh objek dalam kelas yang sama.
