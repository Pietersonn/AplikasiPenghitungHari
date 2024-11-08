# Aplikasi Penghitung Hari

*Aplikasi Penghitung Hari* adalah program berbasis Java Swing yang memudahkan pengguna untuk menghitung jumlah hari dalam bulan tertentu, memeriksa apakah tahun kabisat, serta menghitung selisih hari antara dua tanggal. Aplikasi ini dilengkapi dengan antarmuka pengguna yang ramah dan mudah digunakan.

## Keunggulan Aplikasi

- **Antarmuka yang Intuitif**: Mudah digunakan dengan tampilan yang sederhana namun informatif.
- **Perhitungan Jumlah Hari dalam Bulan**: Menghitung jumlah hari dalam bulan tertentu dan menampilkan apakah tahun tersebut kabisat.
- **Perhitungan Selisih Hari**: Menghitung selisih hari antara dua tanggal yang dipilih pengguna.
- **Penggunaan Kalender**: Menggunakan komponen `JCalendar` dan `JDateChooser` dari library *Toedter* untuk memilih tanggal dengan mudah.

## Fitur Utama

- **Menampilkan Jumlah Hari**: Menghitung dan menampilkan jumlah hari dalam bulan yang dipilih.
- **Pengecekan Tahun Kabisat**: Menampilkan informasi apakah tahun yang dipilih merupakan tahun kabisat.
- **Menampilkan Hari Pertama dan Terakhir dalam Bulan**: Menunjukkan nama hari (contoh: Senin, Selasa) dari hari pertama dan terakhir dalam bulan yang dipilih.
- **Penghitungan Selisih Hari**: Menghitung jumlah hari antara dua tanggal yang dipilih pengguna.
- **Tombol Keluar**: Memungkinkan pengguna menutup aplikasi dengan cepat.

## Cara Menggunakan Aplikasi

1. Pilih bulan dari dropdown dan masukkan tahun menggunakan spinner.
2. Klik tombol **Hitung** untuk menampilkan informasi mengenai bulan yang dipilih:
   - Jumlah hari dalam bulan.
   - Hari pertama dan hari terakhir dalam bulan.
   - Status tahun kabisat.
3. Untuk menghitung selisih hari, pilih dua tanggal menggunakan `JDateChooser` dan klik tombol **Hitung Selisih**.
4. Tekan tombol **Keluar** untuk menutup aplikasi.

## Prasyarat

- Java Development Kit (JDK) 8 atau versi yang lebih baru.
- IDE seperti NetBeans atau IntelliJ untuk menjalankan dan mengedit kode.
- Library tambahan:
  - `jcalendar-1.4.jar` (untuk komponen `JCalendar` dan `JDateChooser`).

## Struktur Kode

- **PenghitungHariFrame.java**: Kelas utama yang berisi antarmuka pengguna dan logika aplikasi.
- **Toedter Calendar**: Menggunakan komponen kalender pihak ketiga (`JCalendar` dan `JDateChooser`).

## DEMO
