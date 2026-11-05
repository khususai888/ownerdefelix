# DEFelix Atelier Workspace

Paket antarmuka statis untuk workspace DEFelix. Tidak memerlukan framework atau proses build.

## Isi paket

- `index.html` — halaman login dan workspace Dashboard, Proyek & Tugas, Laporan, Dokumen, dan Evaluasi.
- `assets/defelix-logo.png` — logo DEFelix.
- `assets/profile-mark.png` — mark profil.
- `assets/login-watermark.png` — mark latar halaman login.
- `.nojekyll` — dukungan publikasi file statis di GitHub Pages.

## Menjalankan

Ekstrak ZIP dan buka `index.html` di browser. Untuk menyimpan proyek di GitHub, ekstrak isi ZIP ke root repositori lalu commit dan push.

## Catatan autentikasi dan data

Login ini memeriksa kredensial di JavaScript pada browser, bukan di server. Kredensial dapat dilihat dari source halaman, jadi login ini hanya untuk prototipe dan tidak aman untuk melindungi data di situs publik. Gunakan autentikasi server-side sebelum dipakai secara publik.

Data workspace disimpan di browser melalui `localStorage`; aplikasi ini belum tersambung ke backend atau database bersama.
