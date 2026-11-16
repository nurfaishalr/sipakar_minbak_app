# Sistem Pakar Penentuan Minat dan Bakat Siswa MI AL-MAU’IZHAH

Sistem Pakar Penentuan Minat dan Bakat Siswa MI AL-MAU’IZHAH dengan Metode Forward Chaining merupakan aplikasi yang dikembangkan untuk membantu memberikan rekomendasi minat dan bakat siswa berdasarkan ciri-ciri yang dimiliki.

Aplikasi ini dibuat sebagai **Tugas Akhir Program Studi Teknik Informatika, Fakultas Teknik dan Ilmu Komputer, Universitas Indraprasta PGRI**.

## Teknologi

- **Java**
- **NetBeans**
- **MySQL**
- **Forward Chaining**

## Fitur Aplikasi

Aplikasi terdiri dari dua pengguna, yaitu **Admin/Guru** dan **Siswa**.

### Admin/Guru
- Login Admin
- Mengelola data siswa
- Mengelola data kategori
- Mengelola data ciri-ciri
- Mengelola data rule
- Melihat hasil rekomendasi
- Melihat laporan
- Mencetak laporan

### Siswa
- Memilih ciri-ciri yang dimiliki
- Melihat hasil rekomendasi minat dan bakat
- Mencetak hasil rekomendasi

## Kategori Minat dan Bakat

Sistem memiliki enam kategori:
- Akademik
- Seni
- Olahraga
- Bahasa
- Kepemimpinan
- Keagamaan

## Tampilan Aplikasi

### Halaman Utama

![Halaman Utama](dokumentasi/01-halaman-utama.png)

Halaman utama merupakan halaman awal untuk mengakses aplikasi.

### Admin/Guru

#### Login Admin

![Login Admin](dokumentasi/02-login-admin.png)

Halaman login digunakan Admin untuk masuk ke dalam sistem.

#### Dashboard

![Dashboard](dokumentasi/03-dashboard.png)

Dashboard menampilkan menu utama pengelolaan aplikasi.

#### Data Siswa

![Data Siswa](dokumentasi/04-data-siswa.png)

Halaman untuk mengelola data siswa.

#### Data Kategori

![Data Kategori](dokumentasi/05-data-kategori.png)

Halaman untuk mengelola kategori minat dan bakat.

#### Data Ciri-Ciri

![Data Ciri-Ciri](dokumentasi/06-data-ciri-ciri.png)

Halaman untuk mengelola ciri-ciri siswa.

#### Data Rule

![Data Rule](dokumentasi/07-data-rule.png)

Halaman untuk mengelola rule yang digunakan dalam proses Forward Chaining.

#### Data Hasil Rekomendasi

![Data Hasil Rekomendasi](dokumentasi/08-data-hasil-rekomendasi.png)

Halaman untuk melihat hasil rekomendasi siswa.

#### Detail Hasil Rekomendasi

![Detail Hasil Rekomendasi](dokumentasi/09-detail-hasil-rekomendasi.png)

Halaman untuk melihat detail hasil rekomendasi.

### Laporan

#### Laporan Data Siswa

![Laporan Data Siswa](dokumentasi/10-laporan-data-siswa.png)
![Cetak Laporan Data Siswa](dokumentasi/15-cetak-laporan-data-siswa.png)


Halaman laporan dan cetak laporan data siswa.

#### Laporan Kategori

![Laporan Kategori](dokumentasi/11-laporan-kategori.png)
![Cetak Laporan Kategori](dokumentasi/16-cetak-laporan-data-kategori.png)

Halaman laporan dan cetak laporan data kategori.

#### Laporan Ciri-Ciri

![Laporan Ciri-Ciri](dokumentasi/12-laporan-ciri-ciri.png)
![Cetak Laporan Ciri-Ciri](dokumentasi/17-cetak-laporan-data-ciri-ciri.png)

Halaman laporan dan cetak laporan data ciri-ciri.

#### Laporan Rule

![Laporan Rule](dokumentasi/13-laporan-rule.png)
![Cetak Laporan Rule](dokumentasi/18-cetak-laporan-data-rule.png)

Halaman laporan dan cetak laporan data rule.

#### Laporan Hasil Rekomendasi

![Laporan Hasil Rekomendasi](dokumentasi/14-laporan-hasil-rekomendasi.png)
![Cetak Laporan Hasil Rekomendasi](dokumentasi/19-cetak-laporan-data-hasil-rekomendasi.png)

Halaman laporan dan cetak laporan data hasil rekomendasi.

### Siswa

#### Form Konsultasi

![Form Konsultasi](dokumentasi/20-form-konsultasi.png)

Form konsultasi digunakan siswa untuk memilih ciri-ciri yang dimiliki.

#### Hasil Rekomendasi

![Hasil Rekomendasi](dokumentasi/09-detail-hasil-rekomendasi.png)

Halaman yang menampilkan hasil rekomendasi berdasarkan ciri-ciri yang dipilih.

#### Cetak Hasil

![Cetak Hasil](dokumentasi/21-cetak-detail-laporan-hasil-rekomendasi.png)

Halaman hasil yang dapat digunakan untuk mencetak rekomendasi.

## Metode

Sistem menggunakan metode **Forward Chaining** dalam proses penentuan rekomendasi minat dan bakat siswa.

Ciri-ciri yang dipilih digunakan sebagai fakta awal, kemudian sistem mencocokkannya dengan rule yang telah ditentukan hingga menghasilkan rekomendasi kategori minat dan bakat.

```text
Ciri-Ciri Siswa
       ↓
     Fakta
       ↓
Pencocokan dengan Rule
       ↓
Forward Chaining
       ↓
Hasil Rekomendasi
```

## Catatan

Hasil yang diberikan oleh sistem berupa **rekomendasi dan bahan pertimbangan bagi guru**, bukan sebagai keputusan akhir dalam menentukan minat dan bakat siswa.

## Pengembang

**Nur Faishal Ramdani**

Program Studi Teknik Informatika  
Fakultas Teknik dan Ilmu Komputer  
Universitas Indraprasta PGRI

---

**Tugas Akhir — 2026**
