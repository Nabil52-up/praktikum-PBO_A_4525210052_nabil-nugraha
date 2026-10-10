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
![Before RekeningBank.java](<img width="1175" height="931" alt="rekeningbank java" src="https://github.com/user-attachments/assets/3553d660-c99d-4b7a-a2ca-d9085b9ad87f" />
)

- **After**:
![After RekeningBank.java](<img width="1410" height="920" alt="Screenshot 2026-10-10 220835" src="https://github.com/user-attachments/assets/e702649e-fb38-41cb-90b0-8a93c0c32cda" />
)

### 1.2. File: `Main.java`

**Penjelasan Kode:**

> File `Main.java` membuat beberapa objek rekening dan menguji operasi setoran, penarikan, serta penghitungan jumlah rekening menggunakan anggota statis.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java](<img width="1062" height="744" alt="main java" src="https://github.com/user-attachments/assets/38238e51-7bd7-47bc-97aa-3cf71d886ea7" />
)

- **After**:
![After Main.java](<img width="1062" height="744" alt="main java" src="https://github.com/user-attachments/assets/46366022-dc43-44dd-946e-ddef6843510f" />
)

### Output Java

![Output Java](<img width="1009" height="238" alt="Screenshot 2026-10-10 221157" src="https://github.com/user-attachments/assets/5b82cfbe-1e43-411c-8d98-e2c803fe5b98" />
)

---

## 2. Implementasi PHP

### 2.1. File: `RekeningBank.php`

**Penjelasan Kode:**

> Kelas `RekeningBank` menerapkan constructor dengan parameter bawaan dan named constructor untuk menyediakan cara alternatif dalam membuat rekening. Kelas ini juga menggunakan konstanta dan anggota statis untuk mengatur data rekening.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before RekeningBank.php](<img width="885" height="933" alt="rekeningbank php" src="https://github.com/user-attachments/assets/dce87beb-88fd-44f1-aaa0-cf6fbb9b93a5" />
)

- **After**:
![After RekeningBank.php](<img width="1244" height="870" alt="Screenshot 2026-10-10 221553" src="https://github.com/user-attachments/assets/f362e3c4-f0c3-40b2-b44e-64301fb5a023" />
)

### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` membuat objek rekening, menampilkan jumlah rekening, dan menjalankan operasi setoran serta penarikan untuk menunjukkan cara kerja kelas `RekeningBank`.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php](<img width="722" height="470" alt="Screenshot 2026-10-10 221640" src="https://github.com/user-attachments/assets/49d6e412-338d-4743-8da0-b5bf58368057" />
)

- **After**:
![After main.php](<img width="753" height="464" alt="Screenshot 2026-10-10 221706" src="https://github.com/user-attachments/assets/329c4bf5-f31e-467a-b0c2-17550f2c2e5a" />
)

### Output PHP

![Output PHP](<img width="779" height="210" alt="Screenshot 2026-10-10 222208" src="https://github.com/user-attachments/assets/e405185a-764c-4c2d-8f5d-a88945988d6f" />
)

---

## 3. Kesimpulan

Constructor mempermudah proses pembuatan objek, sedangkan konstanta digunakan untuk menyimpan nilai tetap. Anggota statis memungkinkan data tertentu, seperti jumlah rekening, dikelola bersama oleh seluruh objek dalam kelas yang sama.
