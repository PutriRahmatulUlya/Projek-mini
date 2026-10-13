# Mini Projek Java: Pendataan Mahasiswa

## Deskripsi Projek
Mini projek ini merupakan program sederhana menggunakan bahasa pemrograman Java 
untuk menginput, menyimpan, dan menampilkan data mahasiswa serta menentukan status kelulusan berdasarkan nilai yang diperoleh.

## Tujuan Projek
- Memahami penggunaan class dan object dalam Java.
- Memahami penggunaan variable dan tipe data.
- Mengimplementasikan constructor dan method.
- Menggunakan array untuk menyimpan beberapa object mahasiswa.
- Menerapkan perulangan untuk input dan menampilkan data.
- Menggunakan percabangan `if-else` untuk menentukan status kelulusan.

## Fitur Program
1. Menginput data 3 mahasiswa.
2. Menyimpan nama, NIM, dan nilai setiap mahasiswa.
3. Menampilkan data seluruh mahasiswa.
4. Memeriksa status kelulusan berdasarkan nilai.
5. Menampilkan status **LULUS** jika nilai minimal 60 dan **TIDAK LULUS** jika nilai kurang dari 60.

## Komponen Pemrograman yang Digunakan
Scanner : Menerima input dari pengguna. 
Class Mahasiswa : Menjadi cetak biru objek mahasiswa. 
Variable : Menyimpan nama, NIM, dan nilai. 
Data type : Menggunakan String dan double. 
Constructor : Menginisialisasi data mahasiswa. 
Object : Membuat objek mahasiswa berdasarkan input. 
Array : Menyimpan 3 objek mahasiswa. 
Method : Menampilkan data dan memeriksa kelulusan. 
if-else : Menentukan status kelulusan. 
for : Mengulang proses input dan output data. 

## Struktur Program
- `Mahasiswa.java` — berisi class `Mahasiswa`, constructor, dan method untuk menampilkan data serta memeriksa kelulusan.
- `MiniProjek.java` — berisi method `main()` sebagai bagian utama program untuk menerima input, membuat array mahasiswa, dan menampilkan hasil.

**Catatan:** Kedua class dapat ditulis dalam satu file bernama `MiniProjek.java`, sesuai kode program yang digunakan. Dalam hal ini, class `Mahasiswa` tidak menggunakan modifier `public`.

## Cara Menjalankan Program

### 1. Persiapan
Pastikan Java Development Kit (JDK) sudah terinstal pada komputer.

### 2. Simpan File
Simpan kode program dengan nama `MiniProjek.java`.

### 3. Buka Terminal
Buka terminal atau Command Prompt pada direktori tempat file program disimpan.

### 4. Kompilasi Program
Jalankan perintah berikut:

```bash
javac MiniProjek.java
```

### 5. Jalankan Program
Setelah kompilasi berhasil, jalankan:

```bash
java MiniProjek
```

### 6. Masukkan Data
Masukkan nama, NIM, dan nilai untuk masing-masing dari tiga mahasiswa sesuai petunjuk yang ditampilkan.

## Contoh Output

```text
=== INPUT DATA MAHASISWA ===

Data Mahasiswa ke-1
Masukkan Nama  : Andi
Masukkan NIM   : 231001
Masukkan Nilai : 85

Data Mahasiswa ke-2
Masukkan Nama  : Budi
Masukkan NIM   : 231002
Masukkan Nilai : 55

Data Mahasiswa ke-3
Masukkan Nama  : Siti
Masukkan NIM   : 231003
Masukkan Nilai : 75

==================================
=== HASIL OUTPUT DATA MAHASISWA ===
==================================

--- Mahasiswa ke-1 ---
Nama  : Andi
NIM   : 231001
Nilai : 85.0
Status: LULUS

--- Mahasiswa ke-2 ---
Nama  : Budi
NIM   : 231002
Nilai : 55.0
Status: TIDAK LULUS

--- Mahasiswa ke-3 ---
Nama  : Siti
NIM   : 231003
Nilai : 75.0
Status: LULUS
```

## Logika Penentuan Kelulusan
Program menggunakan percabangan `if-else` untuk memeriksa nilai mahasiswa.

- Jika nilai lebih besar atau sama dengan 60, mahasiswa dinyatakan **LULUS**.
- Jika nilai kurang dari 60, mahasiswa dinyatakan **TIDAK LULUS**.

## Kesimpulan
Mini projek ini menunjukkan penerapan konsep dasar pemrograman berorientasi objek menggunakan Java. Melalui program ini, pengguna dapat mengelola data sederhana dari tiga mahasiswa dan mengetahui status kelulusan berdasarkan nilai masing-masing. Projek ini juga membantu memahami hubungan antara class, object, array, method, perulangan, dan percabangan dalam pembuatan program Java.

---
**Bahasa Pemrograman:** Java  
**Jenis Projek:** Mini Projek Pemrograman Dasar  
**Nama File Utama:** `MiniProjek.java`
