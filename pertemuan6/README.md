# LAPORAN PRAKTIKUM PEMROGRAMAN BERBASIS OBJEK

| Informasi Praktikan | Keterangan |
| :--- | :--- |
| **Nama** | Nabil Nugraha |
| **NPM** | 4525210052 |
| **Kelas** | A |
| **Mata Kuliah** | Pemrograman Berbasis Objek (PBO) |
| **Pertemuan** | 06 - Abstract Class, Interface, dan Enum |
| **Tanggal** | Kamis 8 Oktober 2026] |

---

## 1. Implementasi Java

### 1.1. File: `Kendaraan.java`, `Mobil.java`, dan `Sepeda.java`

**Penjelasan Kode:**

> Kelas `Kendaraan` merupakan abstract class yang menyimpan informasi umum kendaraan. Kelas `Mobil` dan `Sepeda` menjadi turunannya dengan karakteristik dan perilaku yang berbeda.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Kendaraan.java] <img width="726" height="478" alt="image" src="https://github.com/user-attachments/assets/3a1692b2-3a2a-4006-97c9-73bca183dc7a" />

- **After**:
![After Kendaraan.java] <img width="831" height="492" alt="image" src="https://github.com/user-attachments/assets/08de3a26-f33a-43ac-8050-66367eca15f9" />

### 1.2. File: `Movable.java` dan `Fuelable.java`

**Penjelasan Kode:**

> Kedua interface mendefinisikan kemampuan yang dapat dimiliki oleh objek. `Movable` mengatur perilaku kendaraan yang dapat bergerak, sedangkan `Fuelable` mengatur perilaku kendaraan yang dapat menggunakan bahan bakar.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Interface] <img width="586" height="237" alt="image" src="https://github.com/user-attachments/assets/a56b69de-f31c-483c-9dd5-35fe04148f66" />

- **After**:
![After Interface] <img width="576" height="237" alt="image" src="https://github.com/user-attachments/assets/06cfea79-2309-4614-b12a-07186f99b86a" />


### 1.3. File: `TipeBahanBakar.java` dan `Main.java`

**Penjelasan Kode:**

> Enum `TipeBahanBakar` menyediakan pilihan jenis bahan bakar yang telah ditentukan. File `Main.java` menjalankan program untuk menampilkan perilaku kendaraan dan menghitung biaya pengisian bahan bakar.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before Main.java] <img width="1052" height="802" alt="image" src="https://github.com/user-attachments/assets/3748d442-5e63-4030-8a67-713a23aca34b" />


- **After**:
![After Main.java] <img width="1021" height="830" alt="image" src="https://github.com/user-attachments/assets/28178ccb-95ae-4c30-a290-8b2be0d41fcf" />

### Output Java

![Output Java] <img width="1019" height="259" alt="image" src="https://github.com/user-attachments/assets/2e10a266-8b77-4cd1-97bc-169f8f2c468a" />


---

## 2. Implementasi PHP

### 2.1. File: `abstraksi.php`

**Penjelasan Kode:**

> File `abstraksi.php` berisi interface, enum, dan kelas kendaraan yang menerapkan konsep abstraksi. Setiap kelas memiliki kemampuan sesuai dengan kontrak yang telah ditentukan.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before abstraksi.php] <img width="847" height="916" alt="image" src="https://github.com/user-attachments/assets/570d5ca0-0d1a-4ba4-8c53-e6e96ca0174a" />
<img width="928" height="898" alt="image" src="https://github.com/user-attachments/assets/0572203f-580f-46f1-b0e1-0de6b50d1763" />
<img width="785" height="563" alt="image" src="https://github.com/user-attachments/assets/9b6e0404-94a6-4888-93e1-8f8c436b5157" />



- **After**:
![After abstraksi.php] <img width="710" height="903" alt="image" src="https://github.com/user-attachments/assets/48f19388-af36-4c83-9b30-9ce8e53ebf41" />
<img width="893" height="874" alt="image" src="https://github.com/user-attachments/assets/681d8bee-bfda-4126-8084-04aebb6876fa" />
<img width="967" height="898" alt="image" src="https://github.com/user-attachments/assets/12c94ac8-07ab-408c-958e-0a0cb57d9fa4" />
<img width="758" height="865" alt="image" src="https://github.com/user-attachments/assets/84ba34f0-bdd6-4de6-88a8-48428f087903" />


### 2.2. File: `main.php`

**Penjelasan Kode:**

> File `main.php` menjalankan program kendaraan, menampilkan kemampuan gerak, serta melakukan pengisian bahan bakar berdasarkan jenis kendaraan dan kapasitas tangkinya.

**Bukti Eksekusi (Screenshot):**

- **Before**:
![Before main.php] <img width="822" height="731" alt="image" src="https://github.com/user-attachments/assets/6cad7d98-1f51-4a64-99ea-8adb9fa4eb27" />

- **After**:
![After main.php] <img width="850" height="810" alt="image" src="https://github.com/user-attachments/assets/b9b59c2d-c547-472c-87fd-1d50b0afdd15" />

### Output PHP

![Output PHP] <img width="829" height="365" alt="image" src="https://github.com/user-attachments/assets/ec390b40-bdbd-4cec-b74c-6dabe16356e1" />


---

## 3. Kesimpulan

Abstract class digunakan untuk menyediakan struktur umum, interface menentukan kemampuan yang harus dimiliki suatu kelas, dan enum membatasi pilihan nilai agar lebih konsisten. Ketiganya membantu membangun program yang terstruktur dan mudah dikembangkan.
