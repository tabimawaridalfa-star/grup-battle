# Grup Battle

Game web berisi Adu Retri, Tap Cepat, Tes Refleks, dan Cerdas Cermat.

**Pembuat:** Alfa Tabi Mawarid — mahasiswa Teknik Informatika Universitas Muhammadiyah Purwokerto.

## Demo

[Mainkan Grup Battle](https://grupbattle-alfa.netlify.app/?grup=f8tgy3).

## Teknologi

HTML, CSS, JavaScript, dan Firebase Realtime Database untuk fitur online.

## Menjalankan

1. Unduh atau clone repository.
2. Jalankan server statis di direktori ini, misalnya dengan ekstensi Live Server pada editor Anda.
3. Buka index.html melalui URL server lokal.

## Konfigurasi fitur online

Konfigurasi Firebase dari deployment Alfa tidak disertakan. Blok firebaseConfig pada index.html berisi placeholder GANTI_. Isi blok ini dengan konfigurasi Firebase Web proyek Anda sendiri dan siapkan Realtime Database beserta aturan aksesnya. Fitur online seperti duel dan leaderboard memerlukan konfigurasi tersebut. Jangan mengunggah service-account JSON, private key, atau kredensial admin.

## Peran dan proses pengembangan

Saya menyusun ide, alur logika, aturan permainan, bahan, dan memublikasikan aplikasinya. Implementasi kode dikembangkan dengan bantuan Claude dan Antigravity. Bagian yang paling menantang adalah penyiapan server dan database.

## Isi repository

- index.html: antarmuka dan logika aplikasi
- retri.png dan og-image.png: aset tampilan
- .gitignore: pengecualian konfigurasi dan berkas lokal
