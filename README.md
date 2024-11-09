# AplikasiPerhitunganHari
 Tugas 4 ( Zainal Abidin_2210010087 )
 
Aplikasi GUI sederhana berbasis Java Swing untuk menghitung jumlah hari dalam sebuah bulan dan menampilkan informasi hari pertama dan terakhir dalam bulan tersebut.
Identitas
##NAMA : ZAINAL ABIDIN

##NPM : 2210010087

##KELAS : 5B NONREG BANJARMASIN
## Fitur

- **Pemilihan Bulan dan Tahun**: Pengguna dapat memilih bulan dan tahun melalui dropdown dan spinner.
- **Perhitungan Jumlah Hari**: Dengan menekan tombol "Hitung Hari," aplikasi akan menghitung jumlah hari dalam bulan yang dipilih.
- **Informasi Hari Pertama dan Terakhir**: Menampilkan nama hari untuk tanggal pertama dan terakhir dari bulan yang dipilih.
- **Kalender Terintegrasi**: Menampilkan tanggal pertama dari bulan yang dipilih pada komponen kalender yang terintegrasi.

## Cara Menggunakan

1. Buka aplikasi dan pilih bulan menggunakan `ComboBox` yang disediakan.
2. Masukkan tahun yang diinginkan menggunakan `JSpinner`.
3. Tekan tombol **HITUNG HARI**.
4. Hasil jumlah hari, hari pertama, dan hari terakhir dari bulan yang dipilih akan ditampilkan di bawah tombol.

## Teknologi yang Digunakan

- **Java**: Bahasa pemrograman utama.
- **Java Swing**: Untuk pengembangan antarmuka grafis (GUI).
- **Java Date API (`LocalDate`)**: Untuk manipulasi tanggal.
- **JCalendar Library (`com.toedter.calendar.JCalendar`)**: Untuk menampilkan kalender dalam GUI.

## Keunggulan

- **Mudah digunakan**: Antarmuka yang sederhana memudahkan pengguna untuk memilih bulan dan tahun serta mendapatkan informasi dengan cepat.
- **Informasi lengkap**: Menampilkan jumlah hari serta nama hari untuk tanggal pertama dan terakhir.
- **Komponen kalender**: Memudahkan pengguna dalam melihat tanggal.

## Cara Menjalankan Program

1. **Unduh dependensi**: Pastikan pustaka `JCalendar` tersedia dalam proyek.
2. **Kompilasi kode**:
   ```bash
   javac DateCalculationApp.java
   ```
3. **Jalankan aplikasi**:
   ```bash
   java DateCalculationApp
   ```

Aplikasi akan menampilkan jendela GUI. Pilih bulan dan tahun yang diinginkan, lalu tekan "HITUNG HARI" untuk mendapatkan hasilnya.
