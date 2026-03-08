# Dokumentasi Aplikasi Flutter Pertama

Aplikasi ini merupakan implementasi sederhana menggunakan framework Flutter yang menampilkan pesan "Hello World" di pusat layar. Proyek ini mencakup penggunaan komponen dasar seperti AppBar dan Floating Action Button.

## Fitur Utama
* **AppBar**: Menampilkan judul aplikasi "Aplikasi Pertamaku".
* **Teks Terpusat**: Pesan "Hello World!" diposisikan tepat di tengah layar menggunakan widget `Center`.
* **Kustomisasi Gaya Teks**: Pengaturan ukuran font, jarak antar huruf (*letter spacing*), serta penebalan teks (*bold*).
* **Floating Action Button**: Tombol interaktif yang terletak di sudut bawah layar.
* **Tema Warna**: Penggunaan skema warna kustom dengan perpaduan warna Merah dan Abu-abu.

## Pratinjau Aplikasi
Berikut adalah tampilan antarmuka aplikasi:

![Cuplikan Layar Aplikasi]
<img width="1919" height="822" alt="image" src="https://github.com/user-attachments/assets/60bb77be-c89d-436c-9129-488d3a37ed65" />

## Struktur Kode
Antarmuka pengguna dibangun secara deklaratif di dalam berkas `lib/main.dart` dengan hierarki widget sebagai berikut:

1. **MaterialApp**: Widget utama yang membungkus struktur aplikasi.
2. **Scaffold**: Menyediakan struktur dasar tata letak visual (layout).
3. **AppBar**: Bilah navigasi bagian atas.
4. **Center & Text**: Komponen untuk menampilkan pesan utama.
5. **FloatingActionButton**: Tombol aksi melayang.
