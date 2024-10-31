# PBO2-LATIHAN-2
# Hidayat Noor Fadillah 2210010060

Aplikasi Penghitung Umur

Aplikasi ini adalah program Java sederhana berbasis GUI (Swing) yang berfungsi untuk menghitung umur seseorang, menampilkan ulang tahun berikutnya, dan memberikan informasi tentang peristiwa bersejarah yang terjadi pada tanggal lahir pengguna.
Fitur Utama

    Perhitungan Umur: Hitung umur dengan akurat berdasarkan tanggal lahir.
    Tanggal Ulang Tahun Berikutnya: Lihat kapan ulang tahun berikutnya, termasuk harinya.
    Info Peristiwa Bersejarah: Ambil data peristiwa penting yang terjadi pada tanggal ulang tahun Anda melalui API eksternal.

Struktur Proyek

Proyek ini terdiri dari beberapa file Java utama:

    PenghitungUmur.java - File utama yang menjalankan antarmuka aplikasi.
    PenghitungUmurHelper.java - File ini berisi logika perhitungan umur, penentuan ulang tahun, dan pemanggilan API untuk data peristiwa.

Cara Menjalankan Aplikasi

    Clone atau Unduh Proyek

    bash

    git clone https://github.com/username/PenghitungUmur.git

    Buka dan Jalankan di IDE
        Buka file PenghitungUmur.java di IDE Java seperti IntelliJ IDEA atau NetBeans.
        Jalankan file tersebut untuk membuka aplikasi.

    Masukkan Tanggal Lahir Anda
        Gunakan pemilih tanggal untuk memilih tanggal lahir Anda.
        Tekan tombol "Hitung Umur" untuk melihat hasil perhitungan.

    Lihat Informasi Lengkap
        Usia Anda ditampilkan pada kolom hasil.
        Tanggal ulang tahun berikutnya serta hari dalam seminggu akan ditampilkan di bagian "Ulang Tahun Berikutnya".
        Peristiwa bersejarah yang terjadi pada tanggal ulang tahun Anda akan muncul di bagian "Peristiwa Penting".

    Menutup Aplikasi: Klik tombol "Keluar" untuk mengakhiri aplikasi.

API yang Digunakan

Aplikasi ini memanfaatkan beberapa API eksternal untuk meningkatkan fungsionalitasnya:

    On This Day API - Menyediakan data tentang peristiwa penting berdasarkan tanggal.
    Lingva Translate API - Mengonversi deskripsi peristiwa ke bahasa Indonesia.

Catatan: Aplikasi memerlukan koneksi internet agar bisa mengambil data dari API eksternal.
