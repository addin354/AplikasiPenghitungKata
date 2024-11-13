
# README - Aplikasi Penghitung Kata

## Identitas
- Nama : Addin Husnan Nadhari
- Npm : 2210010037
- Kelas : 2210010037

## Deskripsi
Aplikasi ini adalah **Aplikasi Penghitung Kata** yang dibuat menggunakan Java Swing. Aplikasi ini dapat digunakan untuk menghitung jumlah karakter, kata, kalimat, dan paragraf dalam sebuah teks yang dimasukkan pengguna. Selain itu, aplikasi ini juga menyediakan fitur pencarian kata dalam teks dan menyimpan hasil perhitungan beserta teks ke dalam sebuah file teks.

## Fitur
1. **Hitung Jumlah Karakter**: Menghitung total karakter dalam teks.
2. **Hitung Jumlah Kata**: Menghitung jumlah kata yang terdapat dalam teks.
3. **Hitung Jumlah Kalimat**: Menghitung jumlah kalimat berdasarkan tanda baca seperti titik, tanda seru, dan tanda tanya.
4. **Hitung Jumlah Paragraf**: Menghitung jumlah paragraf yang ada dalam teks berdasarkan pemisah baris baru.
5. **Cari Kata**: Fitur pencarian kata yang memungkinkan pengguna untuk mencari dan menghitung seberapa banyak kata tertentu ditemukan dalam teks.
6. **Simpan Ke File**: Menyimpan teks beserta hasil perhitungan (jumlah karakter, kata, kalimat, paragraf) ke dalam file eksternal.
7. **Keluar**: Menutup aplikasi.

## Penggunaan
1. **Input Teks**: Masukkan teks yang ingin dihitung pada area teks yang disediakan.
2. **Hitung Teks**: Klik tombol **Hitung** untuk menghitung jumlah karakter, kata, kalimat, dan paragraf dalam teks yang dimasukkan. Hasil akan ditampilkan di bawah area input.
3. **Cari Kata**: Masukkan kata yang ingin dicari pada kolom pencarian dan klik tombol **Cari** untuk melihat berapa kali kata tersebut muncul dalam teks.
4. **Simpan Teks dan Hasil**: Klik tombol **Simpan Ke File** untuk menyimpan teks beserta hasil perhitungan ke dalam file teks.
5. **Keluar**: Klik tombol **Keluar** untuk menutup aplikasi.

## Cara Menjalankan Aplikasi
1. Pastikan Anda sudah menginstal Java Development Kit (JDK) di komputer Anda.
2. Kompilasi dan jalankan file `PenghitungKataFrame.java` menggunakan IDE Java seperti NetBeans atau IntelliJ IDEA, atau dengan menggunakan command line dengan perintah:
    ```
    javac PenghitungKataFrame.java
    java PenghitungKataFrame
    ```
3. Aplikasi akan terbuka di jendela GUI, dan Anda dapat mulai memasukkan teks dan menggunakan fitur yang tersedia.

## Struktur Program
Aplikasi ini menggunakan Java Swing untuk membuat antarmuka pengguna grafis (GUI). Berikut adalah penjelasan singkat mengenai beberapa bagian utama dalam program:
- **PenghitungKataFrame.java**: Merupakan kelas utama yang berisi logika aplikasi dan antarmuka pengguna.
- **Fungsi hitungTeks()**: Fungsi ini menghitung jumlah karakter, kata, kalimat, dan paragraf dalam teks yang dimasukkan.
- **Fungsi cariKata()**: Fungsi ini mencari dan menghitung berapa kali kata tertentu muncul dalam teks.
- **Fungsi simpanKeFile()**: Fungsi ini memungkinkan pengguna untuk menyimpan teks beserta hasil perhitungan ke dalam file teks.

## Persyaratan Sistem
- Sistem Operasi: Windows, macOS, atau Linux
- Java Development Kit (JDK) versi 8 atau yang lebih baru.

## Catatan
- Program ini hanya mendukung pencarian kata yang persis sesuai dengan kata yang dimasukkan. Jika pengguna ingin mencari kata dalam variasi huruf besar atau kecil, pencarian tidak membedakan antara keduanya.
- Program ini tidak menangani file besar dengan sangat efisien, jadi disarankan untuk digunakan dengan teks dalam ukuran normal.

