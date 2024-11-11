# Perhitungan Hari dalam Bulan dengan Java Swing


Nama : Lintang Raka Buana  
NPM  : 2210010381  
Kelas: 5A REG Banjarbaru

![image](https://github.com/user-attachments/assets/ca95c166-3b81-4c47-b45b-60df94eaa2b2)

## Deskripsi Program
Program ini menyediakan antarmuka grafis (GUI) yang memungkinkan pengguna memilih bulan dan memasukkan tahun untuk menghitung jumlah hari dalam bulan tersebut. Selain itu, program ini juga memungkinkan pengguna melihat apakah tahun yang dipilih adalah tahun kabisat serta informasi hari pertama dan hari terakhir dari bulan yang dipilih. Program ini juga mendukung fitur perbandingan tanggal untuk menghitung selisih hari antara dua tanggal yang dipilih.

## Fitur
1. **Input Bulan dan Tahun**:
   - Pengguna memilih bulan melalui `JComboBox` dan memasukkan tahun menggunakan `JSpinner`.
   - Integrasi dengan `JCalendar` untuk memastikan sinkronisasi antara bulan dan tahun yang dipilih dengan kalender.
   
2. **Perhitungan Hari**:
   - Menggunakan API `LocalDate` untuk menghitung jumlah hari dalam bulan yang dipilih.
   - Menampilkan apakah tahun tersebut adalah tahun kabisat.
   
3. **Informasi Tambahan**:
   - Menampilkan hari pertama dan hari terakhir pada bulan yang dipilih.
   
4. **Perbandingan Tanggal**:
   - Pengguna dapat memilih tanggal lain menggunakan `JDateChooser` untuk melihat selisih hari antara tanggal yang dipilih dengan tanggal lainnya.
   
## Komponen GUI yang Digunakan
- `JFrame` untuk frame utama aplikasi.
- `JPanel` untuk tata letak komponen.
- `JLabel` untuk label teks.
- `JComboBox` untuk pilihan bulan.
- `JSpinner` untuk input tahun.
- `JButton` untuk tombol "Hitung".
- `JCalendar` untuk pemilihan tanggal.
- `JDateChooser` untuk pemilihan tanggal perbandingan.

## Event Handling
- **ActionListener** pada tombol "Hitung" untuk menjalankan perhitungan saat tombol ditekan.
- **ChangeListener** pada `JSpinner` untuk memperbarui data saat tahun diubah.

## Logika Program
- Menggunakan API `LocalDate` untuk perhitungan jumlah hari dalam bulan dan pengecekan tahun kabisat.
- Menampilkan hari pertama dan terakhir dalam bulan yang dipilih.
- Menghitung selisih hari antara dua tanggal menggunakan `ChronoUnit.DAYS.between`.

## Cara Menggunakan
1. Pilih bulan dari `JComboBox`.
2. Masukkan tahun menggunakan `JSpinner`.
3. Tekan tombol "Hitung" untuk melihat jumlah hari, informasi kabisat, hari pertama dan terakhir, serta hasil perbandingan tanggal (jika dipilih).



